<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'

function myAlert() {
  let responseOfUser = confirm("Hello World!");
}

</script>

<template>
  <!-- <WelcomeItem>
  </WelcomeItem> -->

  <button class="my-button"  v-on:click="myAlert()">
    Click Me
  </button>

</template>


<style scoped>
  .my-container {
    background-color: red;
    font-size: 20px;

  }

  .my-button {

  }
</style>
