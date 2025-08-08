<template>
    <div>
      <h1>{{ name }}</h1>
        <input v-model="name" />
    </div>
</template>

<script setup>
import { ref } from 'vue'

const name = ref("soosee")
</script>