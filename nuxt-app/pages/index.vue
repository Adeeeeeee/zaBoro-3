<template>
  <figure>
    <img class=rectangle-3 src="~/assets/Rectangle3.png" />
  </figure>
  <figure>
    <img class=logo src="~/assets/logo.svg" />
  </figure>
  <figure>
    <img class=lock src="~/assets/Vector.svg" />
  </figure>
  <h1>
    User Management System
  </h1>
  <p class="interns-task1">
    Aeron Labs Interns DEV Task
  </p>
  <p class="interns-task2">
    TaskVersion 1.0 | Last Updated 22 Jun 2022 | Aeron Labs LTD. All rights reserved.
  </p> 
  <h2>
    Register by filling our form.
  </h2>
  <p class="email">
    Email
  </p>
  <div class="box"></div>
  <p class="Passcode">
    Passcode
  </p>
  <div class="box1"></div>
  <p class="Register1">
    Dont have an account?
  </p>
  <a class="Register2" href="http://localhost:3000/register">Register now.</a>
  <a class="btn" href="http://localhost:3001/details ">Log In</a>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;400;600&display=swap');
  .rectangle-3{
    position: absolute;
    width: 784px;
    height: 821px;
    left: 0px;
    top: 0px;  
    }

  .logo{
    position: absolute;
    width: 24px;
    height: 35.59px;
    left: 80px;
    top: 32px;
    }

  h1 {
   position: absolute;
   width: 454px;
   height: 131px;
   left: 80px;
   top: 95px;
   font-family: 'Inter';
   font-style: normal;
   font-weight: 600;
   font-size: 48px;
   line-height: 112%;
   letter-spacing: -0.04em;
   color: #ffffff; 
   } 

   .interns-task1{
    position: absolute;
    width: 454px;
    height: 25px;
    left: 80px;
    bottom: 42px;
    font-family: 'Inter';
    font-style: bold;
    font-weight: 600;
    font-size: 12px;
    line-height: 112%;
    letter-spacing: -0.04em;
    color: #FFFFFF;
    opacity: 0.64;
   }

   .interns-task2{
    position: absolute;
    width: 454px;
    height: 25px;
    left: 80px;
    bottom: 29px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 112%;
    letter-spacing: -0.04em;
    color: #FFFFFF;
    opacity: 0.64;
   }
   
   .lock{
   position: absolute;
   width: 24px;
   height: 32px;
   left: 813px;
   top: 143px;
   }

   h2{
    position: absolute;
    width: 251px;
    height: 67px;
    left: 811px;
    top: 159px; 
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 32px;
    line-height: 96%;
    letter-spacing: -0.04em;
    color: #141414;
   }

   .email{
    position: absolute;
    width: 37px;
    height: 17px;
    left: 811px;
    top: 274px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #141414;
   }

   .box{
    box-sizing: border-box;
    position: absolute;
    width: 346px;
    height: 51px;
    left: 810px;
    top: 315px; 
    background: #F5F5F5;
    border: 1px solid #C7C7C7;
    border-radius: 8px
   }

   .Passcode{
    position: absolute;
    width: 66px;
    height: 17px;
    left: 811px;
    top: 380px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 17px;
    color: #141414;
   }

   .box1{
    box-sizing: border-box;
    position: absolute;
    width: 346px;
    height: 51px;
    left: 810px;
    top: 420px; 
    background: #F5F5F5;
    border: 1px solid #C7C7C7;
    border-radius: 8px
   }

   .Register1{
    position: absolute;
    width: 269px;
    height: 18px;
    left: 813px;
    top: 460px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 15px;
    line-height: 18px;
    color: #141414;
   }

   .Register2{
    position: absolute;
    width: 269px;
    height: 18px;
    left: 980px;
    top: 475px;
    text-decoration: none;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 15px;
    line-height: 18px;
    color:#2592FF;
   }

   .btn{
    position: absolute;
    left: 810px;
    top: 520px;
    width: 117px;
    height: 54px;
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
   
   .btn:hover, .btn:focus, .btn:active {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
   }


</style> 