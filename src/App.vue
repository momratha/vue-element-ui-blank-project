<template>
<div>
   <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">Cryto</router-link>
    </div>
    <router-view />
</div>
</template>

<script>
export default {
  name: "app",
  components: {}
};
</script>

<style>
</style>
