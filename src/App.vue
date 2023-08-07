<template>
  <nav data-v-17acfb5a="" aria-label="Main navigation"
    class="nav navbar theme navbar-expand-xl bg-white iq-navbar navbar-scroll">
    <div data-v-17acfb5a="" class="container p-0">
      <div data-v-17acfb5a="" class="header-left d-flex align-itens-center">
        <router-link to="./"  class="router-link-exact-active router-link-active" aria-current="page"> <img
            data-v-17acfb5a=""
            src="https://uploads-ssl.webflow.com/601cb0d9755ccaac7ff62f03/60a82e320e890baf5f957fc6_Copy%20of%20Untitled%20(3).png"
            alt="logo" class="img-fluid logo"> </router-link>
      </div>
      <div data-v-17acfb5a="" class="header-right d-flex align-itens-center">
        <div data-v-17acfb5a="" class="location-device-lg" role="button" tabindex="0">
          <div data-v-17acfb5a="" class="header-address"><span data-v-17acfb5a="" class="icon"><svg data-v-17acfb5a=""
                width="18" height="20" viewBox="0 0 18 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path data-v-17acfb5a="" fill-rule="evenodd" clip-rule="evenodd"
                  d="M11.5 8.50051C11.5 7.11924 10.3808 6 9.00051 6C7.61924 6 6.5 7.11924 6.5 8.50051C6.5 9.88076 7.61924 11 9.00051 11C10.3808 11 11.5 9.88076 11.5 8.50051Z"
                  stroke="green" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
                <path data-v-17acfb5a="" fill-rule="evenodd" clip-rule="evenodd"
                  d="M8.99951 19C7.80104 19 1.5 13.8984 1.5 8.56329C1.5 4.38664 4.8571 1 8.99951 1C13.1419 1 16.5 4.38664 16.5 8.56329C16.5 13.8984 10.198 19 8.99951 19Z"
                  stroke="green" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
              </svg></span> <span data-v-17acfb5a="" class="ps-2">Search for your area</span></div>
        </div>
        <div data-v-17acfb5a="" class="input-group search-text search-device-lg" style="width: auto;">
          <input data-v-17acfb5a="" type="text" placeholder="Search" data-bs-toggle="dropdown" aria-expanded="false"
            class="form-control nav-item dropdown">
          <svg data-v-17acfb5a="" width="18" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"
            class="search-icon">
            <circle data-v-17acfb5a="" cx="11.7669" cy="11.7666" r="8.98856" stroke="currentcolor" stroke-width="1.5"
              stroke-linecap="round" stroke-linejoin="round"></circle>
            <path data-v-17acfb5a="" d="M18.0186 18.4851L21.5426 22" stroke="currentcolor" stroke-width="1.5"
              stroke-linecap="round" stroke-linejoin="round"></path>
          </svg>
          <ul data-v-17acfb5a="" aria-labelledby="dropdownMenuButton1"
            class="top-width dropdown-menu dropdown-menu-end user-dropdown ">
            <li data-v-17acfb5a="">
              <!---->
            </li>
            <li data-v-17acfb5a="">
              <!---->
            </li>
          </ul>
        </div>
        <div class="d-flex align-items-center header-buttons header-buttons-desktop ">
          <router-link to="register" class="btn btn-primary btn-register"> Register </router-link>
          <router-link to="login" class="btn btn-primary ml-3"> Login </router-link>
        </div>
      </div>
    </div>
    
  </nav>
  <router-view/>
</template>

<style>
@import "../public/css/frontend.min.css";
@import "../public/css/slick.css";
@import "../public/css/style.css"
</style>
