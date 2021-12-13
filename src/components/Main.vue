<template>
  <main>
    <div class="dc-container">
      <div class="dc-wrapper">
        <FirstForm/>
      </div>
    </div>
  </main>
</template>
<script>
import FirstForm from './mainComponents/FirstForm.vue'
export default {
  name:'Main',
  components:{
    FirstForm
  }
}

</script>

<style scoped lang="scss" >
@import '../assets/style/generals.scss';
@import '../assets/style/vars.scss';

.dc-container{
  min-height:80vh;
  background-image:url(../assets/img/bg-6.jpg);
  background-position: center;
  background-size: cover;
}
</style>
