<template>
  <footer>
    <div class="top-footer">
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
    </div>


    <div class="bottom-footer">
      <div class="dc-wrapper d-flex justify-content-between">
        <div class="left-bottom-footer">
          Enjoy the low price .We are tracking any intention of piracy
        </div>
        <div class="right-bottom-footer">
          <i class="far fa-copyright"></i>
          <span>2020 NEXGEN is Proudly Powered by</span> 
          <span>Codings</span>
        </div>
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
  .top-footer{
  background-color:$primaryColor;
  font-size: 12px;
  padding:80px 0;
    .dc-wrapper{
      .dc-grid-container {
      width:100%;
        .dc-grid-item {
        float: left;
        width:25%;
        
        .logo{
          img{
            width:60%;
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
  .bottom-footer{
    background-color:darken($primaryColor, 5%);
    height: 60px;
    font-size: 10px;
    color:lighten($primaryColor,50%);
    .dc-wrapper{
    div{
      line-height: 60px;
      i{
        font-size:8px;
        margin-right:3px;
      }
    }
    div:last-child{
      span:last-child{
        color:$secondaryColor;
        margin-left:3px;
      }
    }
    }
  }
  

}
</style>
