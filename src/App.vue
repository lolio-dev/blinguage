<template>
  <div id="app">
    <img src="@/assets/img/bg.jpg" alt="" class="bg-img">
    <navbar />

    <div class="hero-banner">
      <h1>
        Learn <br>
        Japanese
      </h1>

      <p>
        Visiting the temples in Kyoto, getting a <br>
        new job , or making a personal connection <br>
        --no matter why you want to learn, we <br>
        have the right course for you
      </p>

      <button>Get Starded</button>
    </div>

    <div class="items">
      <item img="book.png" text="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam et vestibulum nisl. Aenean gravida nec nisi vel dignissim. Nullam dapibus, nibh sed pulvinar maximus, dui eros dictum dui, sit amet viverra arcu lorem id nisl. Duis odio nibh, finibus vitae euismod molestie, vestibulum in ante. Proin vitae quam sed erat luctus ornare. Donec at sapien eget felis molestie accumsan a hendrerit diam. Praesent molestie eros arcu. Praesent id tellus quis diam ultrices laoreet sed ut mauris. Vestibulum nisl elit, blandit at facilisis ac, lobortis eget sem. "/>
      <item img="headset.png" text="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam et vestibulum nisl. Aenean gravida nec nisi vel dignissim. Nullam dapibus, nibh sed pulvinar maximus, dui eros dictum dui, sit amet viverra arcu lorem id nisl. Duis odio nibh, finibus vitae euismod molestie, vestibulum in ante. Proin vitae quam sed erat luctus ornare. Donec at sapien eget felis molestie accumsan a hendrerit diam. Praesent molestie eros arcu. Praesent id tellus quis diam ultrices laoreet sed ut mauris. Vestibulum nisl elit, blandit at facilisis ac, lobortis eget sem. "/>
      <item img="loop.png" text="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam et vestibulum nisl. Aenean gravida nec nisi vel dignissim. Nullam dapibus, nibh sed pulvinar maximus, dui eros dictum dui, sit amet viverra arcu lorem id nisl. Duis odio nibh, finibus vitae euismod molestie, vestibulum in ante. Proin vitae quam sed erat luctus ornare. Donec at sapien eget felis molestie accumsan a hendrerit diam. Praesent molestie eros arcu. Praesent id tellus quis diam ultrices laoreet sed ut mauris. Vestibulum nisl elit, blandit at facilisis ac, lobortis eget sem. "/>
    </div>
  </div>
</template>

<script>
import navbar from "@/components/navbar";
import item from "@/components/item";

export default {
  name: 'App',
  components: {
    item,
    navbar
  },
  data() {
    return{

    }
  }
}
</script>

<style>
@import "style/font.css";
@import "style/reset.css";
@import "style/main.css";
</style>
