
<script setup>
// const image ='https://images.unsplash.com/photo-1701600713431-01e520efca61?q=80&w=3024&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D'
// const title = 'Dark night image'
// const link = 'https://unsplash.com/photos/a-view-of-a-city-skyline-at-dusk-DEKef3v8KJA'
const images=[{
    image:'https://images.unsplash.com/photo-1701600713431-01e520efca61?q=80&w=3024&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
    title:'Dark night image',
    link:'https://unsplash.com/photos/a-view-of-a-city-skyline-at-dusk-DEKef3v8KJA'
}]

</script>
<template>
<img :src="images[0].image">
<h3>{{ images[0].title }}</h3>
<a :href="images[0].link">Click to view City Skyline image</a>
</template>

<style scoped>
img{
    width: 400px;
}
</style>


