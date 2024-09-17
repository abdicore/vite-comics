<script >
import AppHeader from './components/AppHeader.vue';
import AppMain   from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue' ;




export default {
  data() {
    return {
      count: 0
    }
  },
  components:{
    AppHeader,
    AppMain,
    AppFooter
  }
}

</script>

<template>
<AppHeader/>
<AppMain/>
<AppFooter/>


</template>

<style scoped>

</style>
