<template>
  <div class="d-flex flex-column justify-space-between align-center home pa-6">
    <h1 class="heading">STEPHEN WILLIAM HALKING</h1>
    <em>"Remember to look up at the stars and not down at your feet. Try to make sense of what you see and wonder about what makes the universe exist. Be curious. And however difficult life may seem there is always something you can do and succeed at. It matters that you don't just give up."</em>
    <v-img
      :aspect-ratio="16/9"
      :width="width"
      src="https://ichef.bbci.co.uk/images/ic/1920x1080/p060hzgt.jpg"
      gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"
    ></v-img>
  </div>
</template>

<style>
.heading {
  margin-top: 100px;
  color: crimson;
}
  .home {
    height: 100px;
    text-align: center;
  }
  em {
    margin: 100px;
    font-size: 20px;
    
    color: rgb(100, 100, 100);
  }
</style>

<script>

  export default {
    name: 'Home',
    data: () => ({
      width: 1000,
    }),
    
  }
</script>
