<script setup>
import { useRouter } from "vue-router";
const router = useRouter();
const login = () => {
  router.push("/login");
};
</script>

<template>
  <h1>Movies Inc.</h1>
  <button @click="login">Login</button>
</template>

<style scoped>
h1 {
  text-align: center;
  font-size: 100px;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  color: black;
}
</style>