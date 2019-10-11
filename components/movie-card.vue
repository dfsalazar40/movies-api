<template>
    <b-card
        title="{{title}}"
        img-src="https://wallpapersite.com/images/pages/pic_w/15948.jpg"
        img-alt="Image"
        img-top
      >
        <b-card-text>
          This is a wider card with supporting text below as a natural lead-in to additional content.
          This content is a little bit longer.
        </b-card-text>
        <b-button to="/detail">View Detail</b-button>
      </b-card>
</template>

<script>
export default {
    name: 'MovieCard',
    props: ['title']
}
</script>

<style scoped>
    
</style>