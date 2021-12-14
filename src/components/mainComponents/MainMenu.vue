<template>
  <ul >
    <li v-for="(voce,index) in listMenu" :key="index">{{voce}}</li>
  </ul>
</template>

<script>
export default {
 name:'MainMenu',
 props:{
   listMenu:Array,
 }
}
</script>

<style lang="scss" scoped>
@import'../../assets/style/mixin.scss';
ul{
  @include center();
  list-style: none;
  li{
    font-size:12px;
    margin:0 20px;

  }
}
</style>