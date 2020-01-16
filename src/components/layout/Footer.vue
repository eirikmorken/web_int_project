<template>
  <footer class="footer">
    <h1>TodoList</h1>
    <div id="nav">
        <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>
.footer {
  position: absolute;
  bottom: 0;
  width: 100%;
  background: #333;
  color: #fff;
  text-align: center;
  padding: 5px;
}

.footer a {
  color: #fff;
  padding-right: 5px;
  text-decoration: none;
}

#nav {
  padding: 15px;
}

#nav a {
  font-weight: bold;
  color: #ccc;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

