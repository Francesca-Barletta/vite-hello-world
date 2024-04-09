<script>
 import AppTitle from './components/AppTitle.vue';
 import AppHero from './components/AppHero.vue';
 export default {
    components:{
      AppTitle,
      AppHero
    }
 }
</script>

<template>
  <AppTitle/>
  <AppHero/>
</template>
<style>
div {
 margin: 0 auto;
 width: 900px;
}
img {
  width: 100%;
}
</style>
