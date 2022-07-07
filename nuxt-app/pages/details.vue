<template>
 <figure>
    <img class=logo2 src="~/assets/logo2.svg" />
  </figure>
  <p class="jack">
    Hi, Jack
  </p>
  <p class="details">
     Details
  </p>
  <p class="email1">
    Email
  </p>
  <div class="boxd"></div>
  <p class="name">
    Full Name
  </p>
  <div class="boxd1"></div>
  <p class="Phone">
    Telephone
  </p>
  <div class="boxd2"></div>
  <a class="btn2" href="http://localhost:3000/register">Save</a>
  <p class="password">
     Password
  </p>
  <p class="old">
    Old Password
  </p>
  <div class="boxd3"></div>
  <p class="New">
    New Password
  </p>
  <div class="boxd4"></div>
  <p class="RepeatPass">
    Repeat New Password
  </p>
  <div class="boxd5"></div>
  <a class="btn3" href="http://localhost:3000/register">Change Password</a>
  <a class="btn4" href="http://localhost:3000">Logout</a>
</template>

<style>
  .logo2{
    position: absolute;
    width: 24px;
    height: 35.59px;
    left: 80px;
    top: 32px;
  }

  .jack{
    position: absolute;
    top: -25px;
    left:129px;
    width: 454px;
    height: 111px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 48px;
    line-height: 112%;
    letter-spacing: -0.04em;
    color: #141414;
    }

    .details{
    position: absolute;
    width: 100px;
    height: 31px;
    left: 132px;
    top: 237px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 96%;
    letter-spacing: -0.04em;
    color: #141414;
   }

   .email1{
    position: absolute;
    width: 37px;
    height: 17px;
    left: 135px;
    top: 310px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #141414;
   }

   .boxd{
    position: absolute;
    width: 264px;
    height: 43px;
    left: 132px;
    top: 345px; 
    background: #F5F5F5;
    border-radius: 8px
   }

   .name{
    position: absolute;
    width: 67px;
    height: 17px;
    left: 135px;
    top: 385px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #141414;
   }

   .boxd1{
    position: absolute;
    width: 264px;
    height: 43px;
    left: 132px;
    top: 420px; 
    background: #F5F5F5;
    border-radius: 8px
   }

   .Phone{
    position: absolute;
    width: 72px;
    height: 17px;
    left: 135px;
    top: 460px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #141414;
   }

   .boxd2{
    position: absolute;
    width: 264px;
    height: 43px;
    left: 132px;
    top: 495px; 
    background: #F5F5F5;
    border-radius: 8px
   }

   .btn2{
    position: absolute;
    left: 132px;
    top: 560px;
    width: 129px;
    height: 38px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 18px;
    text-decoration: none;
    line-height: 22px;
    color: #ffffff;
    background: #2592FF;
    border-radius: 8px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    cursor: pointer
   }
   
   .btn2:hover, .btn:focus, .btn:active {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
   }

   .password{
    position: absolute;
    width: 143px;
    height: 31px;
    left: 419px;
    top: 237px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 96%;
    letter-spacing: -0.04em;
    color: #141414;
   }

   .old{
    position: absolute;
    width: 94px;
    height: 17px;
    left: 422px;
    top: 310px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #141414;
   }

   .boxd3{
    position: absolute;
    width: 264px;
    height: 43px;
    left: 419px;
    top: 345px; 
    background: #F5F5F5;
    border-radius: 8px
   }

   .New{
    position: absolute;
    width: 101px;
    height: 17px;
    left: 422px;
    top: 385px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #141414;
   }

   .boxd4{
    position: absolute;
    width: 264px;
    height: 43px;
    left: 419px;
    top: 420px; 
    background: #F5F5F5;
    border-radius: 8px
   }

   .RepeatPass{
    position: absolute;
    width: 152px;
    height: 17px;
    left: 422px;
    top: 460px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #141414;
   }

   .boxd5{
    position: absolute;
    width: 264px;
    height: 43px;
    left: 419px;
    top: 495px; 
    background: #F5F5F5;
    border-radius: 8px
   }

   .btn3{
    position: absolute;
    left: 419px;
    top: 560px;
    width: 194px;
    height: 38px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 18px;
    text-decoration: none;
    line-height: 22px;
    color: #ffffff;
    background: #2592FF;
    border-radius: 8px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    cursor: pointer
   }
   
   .btn3:hover, .btn:focus, .btn:active {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
   }

   .btn4{
    position: absolute;
    width: 103px;
    height: 31px;
    left: calc(50% - 103px/2 + 553.5px);
    top: 35px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 96%;
    letter-spacing: -0.04em;
    color: #141414;
    text-decoration: none;
   }

    

</style>