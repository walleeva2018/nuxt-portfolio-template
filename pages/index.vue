<template>
  <nav class="navbar">
    <div class="nav-item">
      <nuxt-link to="/">Home</nuxt-link>
    </div>
    <div class="nav-item">
      <nuxt-link to="/mywork">My Work</nuxt-link>
    </div>
    <div class="nav-item">
      <nuxt-link to="/posts">Post</nuxt-link>
    </div>
  </nav>
</template>

<style scoped>
.navbar {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #333;
  color: white;
  height: 60px;
}

.nav-item {
  padding: 10px;
}

/* Add more styling as needed */
</style>
