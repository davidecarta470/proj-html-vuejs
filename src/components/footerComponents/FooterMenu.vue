<template>
  <div>
    <div class="dc-grid-item title"
    v-for="(menu,index) in footerMenuItems" :key="index"
    >
      <h5>
        <strong>
          {{menu.title}}
        </strong>
      </h5>

      <div class="element"
      v-for="(item,index) in menu.items" :key="index"
      >
        <i class="fas fa-chevron-right m-1"></i>
        {{item}}
      </div>
    </div>
  </div>
</template>

<script>
export default {
 name:'FooterMenu',
 props:{
   footerMenuItems:Array
 }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/generals.scss';
@import '../../assets/style/vars.scss';
@import '../../assets/style/mixin.scss';

.dc-grid-item{
  h5{
    color:white;
    margin-bottom:10px;
  }
  color:lighten($primaryColor, 50%);
  margin-left:20px;
  background-color:lighten($primaryColor,10%);
  border-radius:10px;
  padding:20px;
  float: left;
  width:calc(25% - 20px);
  
  }

</style>