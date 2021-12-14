<template>
  <main>
    <section class="first-section">
      <div class="dc-container">
        <div class="dc-wrapper">

          <div class="first-section-top">
            <div class="logo">
              <img src="../assets/img/nexgen-logo.svg" alt="">
            </div>
            <div class="first-section-top-right">
              <MainMenu
              :listMenu="menu"
              />
              <button class="dc-button-fill">
                GET IN TOUCH
              </button>
            </div>
          </div>
          
          <div class="first-section-bottom col-6 offset-6">
             <p>FUSION AND ACQUISITION</p>
             <h1>Insurance Consulting</h1>
             <form>
                 <div class="row">
                   <input type="text " class="col-5" placeholder="NAME">
                   <input type="text " class="col-5" placeholder="EMAIL">
                   <input type="text " class="col-5" placeholder="PHONE">
                   <input type="text " class="col-5" placeholder="MORE INFO">
                 </div>
             </form>
             <button class="dc-button-fill ">GET IN TOUCH</button>
             <button class="dc-button-empty ms-3">READ MORE</button>
          </div>
        </div>
      </div>
    </section>


    <section class="second-section ">
      <div class="dc-wrapper">
        <div class="row">
          <div class="col-6 left"> 
            <p>ABOUT THE NETWORK</p>
            <div class="d-flex my-3">
              <h2><strong>The</strong></h2>
              <h2><strong>Companie</strong></h2>
            </div>
            <p class="my-3">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Blanditiis, laudantium. Culpa tenetur maxime eveniet deleniti ipsa corporis, eos quis quam.
            </p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nobis, veritatis?</p>
          </div>
          <div class="col-6 second-section-right">
            <div class="row">
              <div class="col-6 my-3">
                <h5 class="mb-3"><span><i class="fas fa-medal"></i></span><strong> Tradition</strong></h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
              </div>
              <div class="col-6 my-3">
                <h5 class="mb-3"><span><i class="fas fa-lock"></i></span><strong> Security</strong></h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
              </div>
              <div class="col-6 my-3">
                <h5 class="mb-3"><span><i class="far fa-edit"></i></span><strong> Certificate</strong></h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
              </div>
              <div class="col-6 my-3">
                <h5 class="mb-3"><span><i class="fas fa-graduation-cap"></i></span><strong> Expertise</strong></h5>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
              </div>
      
        
            </div>
          </div>
        </div>
      </div>
    </section>


    <section class="third-section">
      <div class="dc-wrapper">
        <p class="our-business"><strong>OUR BUSINESS AREA</strong> </p>
        <div class="d-flex my-3">
          <h2><strong>Excellence in </strong></h2>
          <h2 class="px-3"><strong>Services</strong></h2>
        </div>
        <div class="row">
          <div class="col-8">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Blanditiis, laudantium. Culpa tenetur maxime eveniet deleniti ipsa corporis, eos quis quam.
          </div>
          <div class="col-4 d-flex justify-content-end"> <button class="dc-button-fill">SEE ALL</button></div>
        </div>
        <div class="services d-flex">
          
            <div class=" service">
                <div class="d-flex justify-content-between ">
                  <i class="fas fa-chart-bar"></i>
                  <i class="fas fa-arrow-right"></i>
                </div>
                <h5 class="my-3"><strong>Audit & Assurance</strong></h5>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
            </div>
            <div class=" service">
                <div class="d-flex justify-content-between ">
                  <i class="fas fa-briefcase"></i>
                  <i class="fas fa-arrow-right"></i>
                </div>
                <h5 class="my-3"><strong>Financial Advisory</strong></h5>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
            </div>
            <div class=" service">
              <div class="d-flex justify-content-between ">
                <i class="fas fa-chart-bar"></i>
                <i class="fas fa-arrow-right"></i>
              </div>
              <h5 class="my-3"><strong>Analytics and M&A</strong></h5>
              <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
            </div>
         
        </div>
        <div class="services d-flex">
          
            <div class=" service">
                <div class="d-flex justify-content-between ">
                  <i class="fas fa-plane"></i>
                  <i class="fas fa-arrow-right"></i>
                </div>
                <h5 class="my-3"><strong>Middle Marketing</strong></h5>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
            </div>
     
            <div class=" service">
                <div class="d-flex justify-content-between ">
                  <i class="fas fa-globe-asia"></i>
                  <i class="fas fa-arrow-right"></i>
                </div>
                <h5 class="my-3"><strong>Legal Consulting</strong></h5>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
            </div>
            <div class=" service">
                <div class="d-flex justify-content-between ">
                  <i class="fas fa-globe-asia"></i>
                  <i class="fas fa-arrow-right"></i>
                </div>
                <h5 class="my-3"><strong>Regulatory Risk</strong></h5>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
            </div>
     
         
        </div>
      </div>
    </section>
    <section></section>
    <section></section>
    <section></section>
  
  </main>
            
           
            
      
            
</template>
<script>
import MainMenu from './mainComponents/MainMenu.vue'
export default {
  name:'Main',
  components:{
    MainMenu
  },
  data(){
    return{
      menu:['HOME','ABOUT','SERVICE','PROCESS','TEAM','BLOG']
    }
  }
}

</script>

<style scoped lang="scss" >
@import '../assets/style/generals.scss';
@import '../assets/style/vars.scss';
@import '../assets/style/mixin.scss';

.first-section{
  .dc-container{
  min-height:80vh;
  background-image:url(../assets/img/bg-6.jpg);
  background-position: center;
  background-size: cover;
      .dc-wrapper{
        .first-section-top{
        padding-top :20px;
        @include center();
        .logo{
          img{
            width: 100px;
          }
        }
        .first-section-top-right{
          @include center();
        }
      }
      .first-section-bottom{
        padding-top:10%;
        p{
          color:$secondaryColor;
        }
        h1{
          font-weight: 900;
          font-size:50px;
        }
        form{
          .row{
            input{
              margin:12px;
              padding:10px 10px;
              background-color:rgba($color: transparent, $alpha: 0.1);
              border:none;
              font-size:10px;
              color: lighten($primaryColor,30%);
            }
          }
        }
        
      }
    }
  }
}


.second-section{
  background-color:lighten($primaryColor, 5%);
  color:lighten($primaryColor, 60%);
  font-size:12px;
  padding:60px 0;
  .dc-wrapper{
    .row{
      .col-6{
        p:first-child{
          color:$secondaryColor
        }
        div{
          h2,h5{
            color:white;
          }
          h2{
            padding: 5px 10px;
          }
          h2:first-child{
            background-color: rgba($secondaryColor,  .2); 
            border-radius: 5px;
          }
          h5{
            span{
              color:$secondaryColor;
            }
          }     
        }
      }
    }
  }
}

.third-section{
  background-color:lighten($secondaryColor, 70%);
  padding:100px 0px;
  .dc-wrapper{
    .our-business{
     color:$secondaryColor;
    }
    div{
      font-size:12px !important;
      h2{
        padding:5px 0px;

      }
      h2:last-child{
        background-color: rgba($secondaryColor, .2);
        color:$secondaryColor;
        margin-left:10px;
        border-radius:5px;
      }
    }
    div{
      .col-8{
        color:lighten($primaryColor, 50%);
      }
    }
    .services{
      padding-top:21px;
        .service:nth-child(2){
          margin:0 21px;
        }
        .service{
          background-color:white;
          padding:40px;
          width:calc(33.33333% - 14px);
          border-radius:10px;
          p{
            color:lighten($primaryColor, 50%);
          }
          div{
            i:first-child{
              color:darken($secondaryColor, 5%);
              font-size:30px;
            }
            i:last-child{
              color:lighten($secondaryColor, 5%);
              font-size:15px;
            }
          }
        }
      
    }
  }
}

</style>
