<template>
  <div id="item">
    <img :src="require('@/assets/' + 'img/' + img + '')" alt="">
    <h3>{{ text }}</h3>
  </div>
</template>

<script>
export default {
  name: "item",
  props: {
    text: String,
    img: String
  }
}
</script>

<style scoped src="../style/item.css" />