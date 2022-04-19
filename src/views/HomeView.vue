<script setup>
import { ref } from "@vue/reactivity";
import { useCounterStore } from "../stores/counter";


const counterStore = useCounterStore();

</script>

<template>
  <div class="d-flex align-items-center justify-content-center flex-column vh-100">
    <h5>My Counter Application</h5>
    <h1> {{counterStore.count}} </h1>
    <div>
      <button class="btn m-1 btn-info" @click = "counterStore.add(5)">+</button>
      <button class="btn m-1 btn-info" @click = "counterStore.decrement">-</button>
    </div>
      <RouterLink to="notes">Go to Notes </RouterLink>
      <RouterLink to="login">Go to Login </RouterLink>
  </div>
</template>
