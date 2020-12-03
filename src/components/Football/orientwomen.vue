<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Orient<span class="ml-2 text-pink-200">Women's Team</span>
      </h2>
      <g-link href="http://bit.ly/2IjjrAF" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/orient.jpg"
          alt   = "leyton orient"
      /></g-link>
      <p class="text-blue-200 text-center">
        Mile End Stadium<br />190 Burdett Road <br />Mile End London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2uFKXVA"
          target = "_blank"
        >
          E3 4HL
        </g-link>
        <br /><br />
        <!-- #leytonorientfc -->
         <!--OrientWFC-->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
       
      </p>

   
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2IjjrAF"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
