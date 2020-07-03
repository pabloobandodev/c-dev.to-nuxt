<template>
  <div class="container">
    <Nuxt keep-alive />
  </div>
</template>

<style>
html {
  padding: 0;
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
    Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  color: #131415;
}
.container {
  max-width: 50rem;
  padding: 2rem 1rem;
  min-height: 100vh;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  background-color: yellow;
}
</style>
