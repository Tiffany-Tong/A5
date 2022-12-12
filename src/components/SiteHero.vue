<script setup></script>

<template>
  <div class="image-container">
    <div class="text-container">
      <h2>This website helps you learn about trending movies!</h2>
      <p>Ready to learn about movies you might enjoy watching?</p>
      <p2>Click the "Login" button on top to get started!</p2>
    </div>
    <img
      src="https://external-preview.redd.it/Z-mdOCdgw53wluJKQdklW2-WwJEcd3zXoER3YNl-euI.jpg?auto=webp&s=9da2a0406734c547c7bc489c5fa20b091c7ee86c" />
  </div>
</template>

<style scoped>
img {
  width: 60%;
  margin-left: -150px;
}
.image-container {
  position: relative;
  text-align: center;
  color: white;
  text-size-adjust: 100px;
  font-family: 'Times New Roman', Times, serif;
  font-size: x-large;
}
.text-container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: black;
}
</style>