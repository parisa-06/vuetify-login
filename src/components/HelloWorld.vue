<template>
  <v-app id="inspire">
    <v-content>
      <v-container class="fill-height  byd-background-image " fluid>
        <v-row align="center" justify="center">
          <v-col cols="12" sm="8" md="8">
            <div class="byd-main">
                 <v-row>
                    <v-col cols="12" md="5" class="byd-part-form">
                      <v-card-text class="mt-12">
                        <h2
                          class="text-center  teal--text text--accent-3 my-6  "
                        >ورود به سهمان</h2>
                        <div class="text-center mt-1">
                         <v-icon>fab fa-linkedin-in</v-icon>
                         <p class="text-center grey--text darken-1" >اطلاعات وارد شده درست نمی‌باشد. </p>
                        </div>
                       
                       <div class="byd-form " >
                       <v-form>
                          <v-text-field
                            label="نام کاربری"
                            name="user"
                           type="text"
                            color="teal accent-3"
                          />

                          <v-text-field
                            id="password"
                            label="پسورد"
                            name="password"
                            type="password"
                            color="teal accent-3"
                          />
                        </v-form>
                        </div>
                        <p class="text-center  grey--text lighten-1 display-6 mt-5" >
                        
                      رمز عبورتان را فراموش کرده‌اید؟‌‌‌‌‌‌‌‌‌  <a href="#" class="text-center teal--text accent-3 byd-forget-link"><b> کلیک کنید. </b></a></p>
                      </v-card-text>
                      <div class="text-center mt-3 mb-12">
                        <v-btn rounded color="teal accent-4"  dark class="ml-4 px-6"> ورود </v-btn>
                        <v-btn rounded color="teal accent-3" dark> ثبت نام</v-btn>
                      </div>
                    </v-col>
                    <v-col cols="12" md="7" class="teal accent-3 ta">
                      <v-card-text class="white--text mt-12">
                        <h2 class="text-center "> سلام دوست من </h2>
                        <h3
                          class="text-center"
                        >
                        مشخصات شخصی خود را وارد کنید و عضوی از خانواده سهمان شوید.
                        </h3>
                      </v-card-text>
                      <div class="text-center">
                      
                      </div>
                    </v-col>
                  </v-row>
               
            
            </div>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>



<style>
 *{
  font-family: 'Vazir';
  }
  .byd-background-image {
background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' version='1.1' xmlns:xlink='http://www.w3.org/1999/xlink' xmlns:svgjs='http://svgjs.com/svgjs' width='1000' height='900' preserveAspectRatio='none' viewBox='0 0 1000 900'%3e%3cg mask='url(%26quot%3b%23SvgjsMask1030%26quot%3b)' fill='none'%3e%3cpath d='M-176.51 56.5 a233.01 233.01 0 1 0 466.02 0 a233.01 233.01 0 1 0 -466.02 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float1'%3e%3c/path%3e%3cpath d='M-192.77 72.77 a265.54 265.54 0 1 0 531.08 0 a265.54 265.54 0 1 0 -531.08 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M-188.96 68.97 a257.93 257.93 0 1 0 515.86 0 a257.93 257.93 0 1 0 -515.86 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M654.73 45.28 a210.55 210.55 0 1 0 421.1 0 a210.55 210.55 0 1 0 -421.1 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M660.47 39.53 a199.06 199.06 0 1 0 398.12 0 a199.06 199.06 0 1 0 -398.12 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M744.14 -44.14 a31.72 31.72 0 1 0 63.44 0 a31.72 31.72 0 1 0 -63.44 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M-99.18 699.19 a78.37 78.37 0 1 0 156.74 0 a78.37 78.37 0 1 0 -156.74 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M-136.82 736.81 a153.63 153.63 0 1 0 307.26 0 a153.63 153.63 0 1 0 -307.26 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M-152.67 752.67 a185.34 185.34 0 1 0 370.68 0 a185.34 185.34 0 1 0 -370.68 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M704.46 715.54 a111.08 111.08 0 1 0 222.16 0 a111.08 111.08 0 1 0 -222.16 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M696.88 723.12 a126.24 126.24 0 1 0 252.48 0 a126.24 126.24 0 1 0 -252.48 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3cpath d='M696.55 723.45 a126.9 126.9 0 1 0 253.8 0 a126.9 126.9 0 1 0 -253.8 0z' fill='rgba(29%2c 233%2c 182%2c 1)' class='triangle-float2'%3e%3c/path%3e%3c/g%3e%3cdefs%3e%3cmask id='SvgjsMask1030'%3e%3crect width='1000' height='900' fill='white'%3e%3c/rect%3e%3c/mask%3e%3cstyle%3e %40keyframes float1 %7b 0%25%7btransform: translate(0%2c 0)%7d 50%25%7btransform: translate(-10px%2c 0)%7d 100%25%7btransform: translate(0%2c 0)%7d %7d .triangle-float1 %7b animation: float1 5s infinite%3b %7d %40keyframes float2 %7b 0%25%7btransform: translate(0%2c 0)%7d 50%25%7btransform: translate(-5px%2c -5px)%7d 100%25%7btransform: translate(0%2c 0)%7d %7d .triangle-float2 %7b animation: float2 4s infinite%3b %7d %40keyframes float3 %7b 0%25%7btransform: translate(0%2c 0)%7d 50%25%7btransform: translate(0%2c -10px)%7d 100%25%7btransform: translate(0%2c 0)%7d %7d .triangle-float3 %7b animation: float3 6s infinite%3b %7d %3c/style%3e%3c/defs%3e%3c/svg%3e");
background-position: center;
    background-repeat  : no-repeat;
    background-size    : cover;
}

 
  .byd-form{
    width:200px;
    margin: 0 auto;
}
.byd-main{
  box-shadow: 4px 4px 10px 1px rgba(0, 0, 255, .2);
}
.byd-forget-link{
   text-decoration: none;
}
 @media only screen and (max-width:995px) {
   .ta{
     display:none
   }
  .byd-main{
   box-shadow:0px 0px 0px 0px rgba(0, 0, 255, .2);
  }
    
 }

</style>

<script>
export default {

};
</script>