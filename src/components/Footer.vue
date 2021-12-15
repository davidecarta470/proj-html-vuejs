<template>
  <footer>
    <div class="dc-wrapper ">
      <div class="dc-grid-container clearfix">
        <div class="dc-grid-item">
          <div class="logo">
            <img src="../assets/img/nexgen-logo.svg" alt="">
          </div>
          <div>A Functional HTML Template for Corporate & Business</div>
          <div>
              <i class="fas fa-phone-alt"></i>
              +1(306) 1234-5678
          </div>
          <div>
              <i class="fas fa-envelope"></i>
              hello@example.com
          </div> 
          <div >
            <i class="fas fa-clock"></i>
            Main Avenue ,987
          </div>
          <button class="dc-button-empty">GET IN TOUCH</button> 
        </div>  
        <FooterMenu
        :footerMenuItems="foorerMenuItems"
        /> 
      </div>
    </div>
  </footer>
</template>
        
         

<script>
import FooterMenu from './footerComponents/FooterMenu.vue'
export default {
  name:'Footer',
  components:{

    FooterMenu
  },
  data(){
    return{
      foorerMenuItems:[{
        title:'About',
        items:['The Company','Institutional','Social & Events','Innovation','Enviroment','Technology']
        
      },{
        title:'Service',
        items:['Audit & Assurance','Financial Advisor','Analytic M&A','Middle Marketing','Legal Consulting','Regulatory Risk']
      ,
      },{
        title:'Support',
        items:['Responsability','Terms of Use','About Cookies','Privacy Policy','Accessibility','Information']
      }
      ]
    }
  }
}
</script>
        
       
     
        

<style lang="scss" scoped>
@import '../assets/style/generals.scss';
@import '../assets/style/vars.scss';
@import '../assets/style/mixin.scss';
footer{
background-color:$primaryColor;
font-size: 12px;
padding:80px 0;
  .dc-wrapper{
    .dc-grid-container {
    width:100%;
      .dc-grid-item {
       float: left;
       width:calc(25% - 20px);
      
      .logo{
        img{
          width:70%;
        }
      }
      }
      
      .dc-grid-item{
        color:lighten($primaryColor,50%);
        div{
          margin-bottom:10px;
        }
        button{
          color:white;
        }
      }
    }
  
  }
}
</style>
