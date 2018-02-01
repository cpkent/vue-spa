<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <router-link class="navbar-item" to="/category/front-end" exact>
        <img src="http://bit.ly/vue-img"
          alt="Vue SPA" />
      </router-link>
    </div>
    <div class="navbar-menu">
      <router-link class="navbar-item is-tab" to="/category/front-end" exact="">Front End</router-link>
      <router-link class="navbar-item is-tab" :to="{ name: 'category', params: { id: 'mobile' } }" exact="">Mobile</router-link>
      <router-link class="navbar-item is-tab" to="/login" exact="">Login</router-link>
    </div>
  </nav>
</template>
