<template>
  <nav>
    <img src="@/assets/HKLogo.png" alt="" />

    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>

<style>
@import url(//fonts.googleapis.com/css?family=Lato:300:400);

#app {
  font-family: "Lato", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 15px;
  display: flex;
  flex-direction: row;
  align-items: center;
}

nav img {
  width: 50px;
  height: 50px;
  justify-content: left;
  position: absolute;
}

nav a {
  font-weight: bold;
  font-size: 22px;
  color: #2c3e50;
  text-decoration: none;
  position: relative;
  float: none;
}

nav a.router-link-exact-active {
  color: rgba(199, 107, 15, 1);
}
</style>
