<script>
import ComicsList from "./ComicsList.vue";
import BannerList from "./BannerList.vue";



export default {
  data() {
    return {
    }
  },
  components:{
    ComicsList,
    BannerList,
  }
}
</script>

<template>
<main>
    <div class="jumbotron">
        <img src="../assets/img 7/jumbotron.jpg" alt="">
    </div>
    <div class="cards"></div>
</main>
<ComicsList/>
<BannerList/>
</template>

<style scoped>
h1 {
    color: #ffffff;
}

.jumbotron {
    background-size: cover;
    height: 200px;
}
img {
    height: 200px;
}

</style>
