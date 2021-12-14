<template>
 
  <header class="dc-container">
    <div class="dc-wrapper d-flex justify-content-between align-items-center">
      <div class="header-left">
        <i class="fas fa-clock"></i>
        Open Hours : Mon - Sat - 9:00 - 18:00
      </div>
      <div class="header-right">
        <span>
          <i class="fas fa-phone-alt"></i>
          +1(306) 1234-5678
        </span>
        <span>
          <i class="fas fa-envelope"></i>
          hello@example.com
        </span>
        <span><i class="fab fa-facebook-f"></i></span>
        <span><i class="fab fa-twitter"></i></span>
        <span><i class="fab fa-linkedin-in"></i></span>
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
  color:lighten($primaryColor,60%);
  .dc-wrapper{
    height:40px;
    font-size:10px;
    span{
      margin:0px 10px
    }
  }
}

</style>