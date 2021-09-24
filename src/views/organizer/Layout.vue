<template>

    <h1>{{ GStore.organizer.name }}</h1>
    <img v-for="url in GStore.organizer.imageUrls" :key="url" :src="url" />
</template>
<script>
export default {
  inject: ['GStore']
}
</script>
