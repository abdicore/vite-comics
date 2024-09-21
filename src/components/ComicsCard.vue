<script >


export default {
  data() {
    return {
    }
  },
  props:{
    comicUrl: {
      require: true,
      type: String,
    },
    comicPrice: {
      require: true,
      type: String,
    },
    comicSeries: {
      require: true,
      type: String,
    },
    comicType: {
      require: true,
      type: String,
    },
  },
  components:{
 
  }
}

</script>

<template>
  <li>
    <img :src="comicUrl" :alt="comicSeries">
    <h3>
      {{ comicSeries }} 
    </h3> 
  </li>
</template>

<style  scoped>
h1 {
    font-size: 30px;
    color: black;
}

img {
  max-height: 100px;
}

</style>
