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


    <section class="fourth-section">
      <div class="top-fourth-section text-center">
        <p><strong> HOW IT WORK IN PRACTICE</strong></p>
        <div class="d-flex my-3 justify-content-center">
          <h2><strong>Process</strong></h2>
          <h2><strong>Menagement</strong></h2>
        </div>
        <p class="my-3">
          We work with innovative methodologies to ensure that the entire reformatting process is done from start to finish
        </p>
      </div>
      <div class="bottom-fourth-section">
        <div class="container">
          <div class="item">
            <div class="d-flex justify-content-center align-items-center">
              <strong >01</strong>
            </div>
            <h6 class=""><strong>Collections of infoemation</strong> </h6>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
          <div class="item">
            <div class="d-flex justify-content-center align-items-center">
              <strong >02</strong>
            </div>
            <h6 class=""><strong>Strategic Planning</strong> </h6>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
          <div class="item">
            <div class="d-flex justify-content-center align-items-center">
              <strong >03</strong>
            </div>
            <h6 class=""><strong>Assignment of responsibilities</strong> </h6>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
          <div class="item">
            <div class="d-flex justify-content-center align-items-center">
              <strong >04</strong>
            </div>
            <h6 class=""><strong>Formating process</strong> </h6>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
          <div class="item">
            <div class="d-flex justify-content-center align-items-center">
              <strong >05</strong>
            </div>
            <h6 class=""><strong>Continuity formalizzation</strong> </h6>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
          </div>
        </div>
      </div>
    </section>


    <section class="fifth-section">
      <div class="dc-wrapper">
        <div class="row">

          <div class="fifth-section-left col-8">
            <!-- top fifth section left -->
            <p><strong> WE LIKE WHAT WE DO</strong></p>
            <div class="d-flex my-3 ">
              <h2><strong>Team</strong></h2>
              <h2><strong>of expert</strong></h2>
            </div>
            <p class="my-3 text-white">
              We work with innovative methodologies to ensure that the entire reformatting process is done from start to finish
            </p>
            <!-- bottom fifth section left list of items-->
            
             <Team
             :membersTeam="team"
             />            
            
          </div>


          <div class="fifth-section-right col-4 p-4 text-white">
            <h5><strong>President Speech</strong></h5>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi natus optio quia.</p>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam obcaecati voluptatem suscipit, reprehenderit nam quod in, illo qui accusantium iusto fugit distinctio voluptates deleniti maxime!</p>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Culpa porro suscipit perferendis laboriosam neque maxime explicabo quo aliquid dolor! Harum, quo dolorem.</p>
            <p class="d-flex justify-content-between">
              <strong>T.Johonson</strong>
              <span><i class="fas fa-quote-right"></i></span>
            </p>
          </div>
        </div>
      </div>
    </section>
    <section></section>
  
  </main>
       
            
           
            
      
            
</template>
<script>
import MainMenu from './mainComponents/MainMenu.vue';
import Team from './mainComponents/Team.vue'
export default {
  name:'Main',
  components:{
    MainMenu,
    Team
  },
  data(){
    return{
      menu:['HOME','ABOUT','SERVICE','PROCESS','TEAM','BLOG'],
      team:[{
        name:'David Cooper',
        role:'CTO & CO-FOUNDER',
        photo:require('../assets/img/team-1.jpg')
      },
      {
        name:'Olivier Jones',
        role:'CHIEF PROCUREMENT',
        photo:require('../assets/img/team-3.jpg')
      },
      {
        name:'Emma Lopez',
        role:'CHIEF MARKETING',
        photo:require('../assets/img/team-2.jpg')
      },
      {
        name:'T.Johonson',
        role:'CEO & PRESIDENT',
        photo:require('../assets/img/team-4.jpg')
      },
      ],
      
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
       @include general();
       h2{
         color:white !important;
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


.third-section{
  background-color:lighten($primaryColor, 85%);
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


.fourth-section{
  .top-fourth-section{
    padding:100px 0 60px 0;
    border-bottom:2px solid lighten($primaryColor, 80%);
    @include general();
    }
  
  .bottom-fourth-section{
    margin-bottom:100px;
    .container{
      display:flex;
      justify-content: space-evenly;
      .item{
        width:15%;
        text-align: center;
        position:relative;
        div{
          position:absolute;
          top:-19px;
          left:50%;
          transform: translateX(-50%);
          background-color: lighten($primaryColor, 80%);
          color:$secondaryColor;
          border-radius:50%;
          width: 35px;
          height:35px;
        }
        h6{
          margin:30px 0px;
        }
        p{
          font-size:12px;
          color:lighten($primaryColor,50%)
        }
      }
    }
  }
 
}

.fifth-section{
  padding:100px 0px;
   background-color:lighten($primaryColor, 5%);
  .fifth-section-left{
    padding-right:50px;
    @include general();
    h2{
        color:white !important;
      }
  }
  .fifth-section-right{
    margin-top:50px;
    background-color:$secondaryColor;
    p{
      font-size: 12px;
      margin:20px 0px;
    }
    p:last-child{
      span{
        color:darken($secondaryColor, 10%);
        font-size:14px;
      }
    }
  }
}
</style>
