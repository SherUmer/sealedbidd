<template>
  <main class="login main-content">
    <h1>This is a Login View ?</h1>
    <p>Todo id: {{ todoId }}</p>
    <button @click="todoId++">Fetch next todo</button>
    <p v-if="!todoData">Loading...</p>
    <pre v-else>{{ todoData }}</pre>
    <footerComponent />
  </main>
</template>

<script>
import footerComponent from '@/components/IncludeComponents/footerComponent.vue';

export default {
  name: 'Login',
  components:{
    footerComponent
  },
  data() {
    return {
      todoId: 1,
      todoData: null
    }
  },
  methods: {
    async fetchData() {
      this.todoData = null
      const res = await fetch(
        `https://jsonplaceholder.typicode.com/todos/${this.todoId}`
      )
      this.todoData = await res.json()
    }
  },
  mounted() {
    this.fetchData()
  },
  watch: {
    todoId() {
      this.fetchData()
    }
  }
}

</script>

