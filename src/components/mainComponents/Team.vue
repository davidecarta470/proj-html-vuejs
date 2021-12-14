<template>
<div class="items d-flex flex-wrap">
  <div 
  v-for="(memberTeam,index) in membersTeam" :key="index"
  class="item d-flex">
    <div class="image"><img :src="memberTeam.photo" alt=""></div>
    <div class="member-info">
      <h5>{{memberTeam.name}}</h5>
      <p>{{memberTeam.role}}</p>
      <span><i class="fab fa-facebook-f"></i></span>
      <span><i class="fab fa-twitter"></i></span>
      <span><i class="fab fa-linkedin-in"></i></span>
    </div>
  </div>
 
</div>  
</template>

<script>
export default {
  name:'Team',
  props:{
    membersTeam:Array
  } 
}
</script>

<style lang="scss" scoped>
@import'../../assets/style/mixin.scss';
@import'../../assets/style/vars.scss';
 .item{
  margin-top:40px;
  min-width: 250px;
  color:white;
  img{
    width: 80px;
    margin-right:10px;
    border-radius: 10px;
  }
  p{
    color:lighten($primaryColor, 50%);
    margin:10px 0px;
    font-size: 10px;
  }
  span{
    display:inline-block;
    width:30px;
    height:30px;
    text-align: center;
    line-height: 30px;
    background-color:rgba($secondaryColor, .2);
    color:$secondaryColor;
    border-radius:50%;
    margin-left:4px;
  }

}
</style>