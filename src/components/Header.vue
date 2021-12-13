<template>
 
  <header class="dc-container">
    <div class="dc-wrapper d-flex justify-content-between align-items-center">
      <div class="header-left">Open Hours : Mon - Sat - 9:00 - 18:00</div>
      <div class="header-right">
        <span>+1(306) 1234-5678</span>
        <span>hello@example.com</span>
        <span></span>
        <span></span>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name:'Header',
}
</script>

<style lang="scss" scoped>
@import '../assets/style/generals.scss';
@import '../assets/style/vars.scss';


.dc-container{
  background-color: $primaryColor;
  color:lighten($primaryColor,70%);
  .dc-wrapper{
    height:30px;
    font-size:8px;
    span{
      margin:0px 10px
    }
  }
}

</style>