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
    -- {{ comicSeries }} -- {{ comicPrice }} -- {{ comicType }}
  </li>
</template>

<style  scoped>
h1 {
    font-size: 30px;
    color: black;
}

</style>
