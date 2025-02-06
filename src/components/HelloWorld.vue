<script setup>
import { ref } from 'vue'

const eggCount = ref(0)
const tortillaCount = ref(0)
const chocolateCount = ref(0)

</script>

<template>
  <div>
    Eggs
    <button type="button" @click="eggCount--">-</button>
    <button type="button" @click="eggCount++">+</button>
    {{ eggCount }}
    <p>
    Tortilla
    <button type="button" @click="tortillaCount--">-</button>
    <button type="button" @click="tortillaCount++">+</button>
    {{ tortillaCount }}
    </p>
    chocolate
    <button type="button" @click="chocolateCount--">-</button>
    <button type="button" @click="chocolateCount++">+</button>
    {{ chocolateCount }}
  </div>
</template>
