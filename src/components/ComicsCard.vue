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
    <div class="card" >
      <img :src="comicUrl" :alt="comicSeries">
      <div class="card-body">
        <a href="#" class="card-title" >{{ comicSeries }} <br> <span>{{ comicType }}</span></a>
      </div>
    </div>
  </li>
</template>

<style  scoped>
a {
    text-decoration: none;
    font-size: 12pxpx;
    color: black;
}

img {
  height: 230px;
}

span {
  font-size: 6pxpx;
    color: gray;
}

li{
  margin-top: 20px;
  display: flex;
  flex-basis: calc(100% / 4);
}

</style>
