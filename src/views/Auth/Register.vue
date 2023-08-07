<template>
    <main class="register main-content">
        <h1>This is a Register View</h1>
        <footerComponent />
    </main>
</template>

<script>
import footerComponent from '@/components/IncludeComponents/footerComponent.vue';


export default {
    name: 'Register',
    components: {
        footerComponent
    }
}

</script>

