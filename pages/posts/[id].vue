<script setup lang="ts">
const route = useRoute()
console.log(route.params.id)
</script>

<template>
    <h2 v-if="route.params.id == '1'"><NuxtLink to="/posts/1"> C'est l'heure du duel</NuxtLink></h2>
    <h3 v-if="route.params.id == '2'"><NuxtLink to="/posts/2">Let's go Baki</NuxtLink></h3>
</template>

<script>

</script>