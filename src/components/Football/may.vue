<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        May & Bakers
      </h2>
      <g-link href="http://bit.ly/32CuiyT" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/football/may.jpg"
          alt   = "May & Bakers"
      /></g-link>
      <p class="text-blue-200 text-center">
        M & B Sports<br />
      Dagenham Road<br />
      Romford Essex 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2U5q7c2"
          target = "_blank"
        >
          RM7 0QX
        </g-link>
        <br /><br />
        
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
      <!--  Fri 17 April 7.45 pm <br /><span class="text-red-700">V</span>
        <br />Hackney Wick
        -->
      </p>

     

      

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/32CuiyT"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
