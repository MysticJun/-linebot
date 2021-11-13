<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>|
    <img src="https://lh3.googleusercontent.com/proxy/o-x9e8U1KhCJveTktKtauoLkeZ5pVD3uzMfvKd3zeb7x4S4M6WQYYBZ6B162LnB9ex3qFwADtueP0zNB5fBsbDfxhlKTv1SKs9Q5Fu_x55m5iyy0lw" alt="good" width="50" height="50">
      <router-link to="/Photo">圖片</router-link>
  </div>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #0d0d0d;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
