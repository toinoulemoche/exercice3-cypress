<script setup>
import {ref} from "vue";
const compt = 0;
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
     
    </div>
  </header>

    <p>{{compt}}</p>
    <button v-on:click="compt=++">incr</button>
</template>































































