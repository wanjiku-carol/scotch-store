<template>
  <div id="app">
    <nav class="navbar navbar-expand-sm bg-light">
        <ul class="navbar-nav">
          <li class="list-group-item"><router-link to="/">Home</router-link></li>
          <li class="list-group-item"><router-link to="/admin">Admin</router-link></li>
          <li class="list-group-item"><router-link to="/cart">Cart</router-link></li>
        </ul>
    </nav>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>
