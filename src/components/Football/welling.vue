<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Welling United
      </h2>
      <g-link href="http://bit.ly/2EtqTqf" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/welling.png"
          alt   = "Welling United"
      /></g-link>
      <p class="text-blue-200 text-center">
        Park View Road <br />Welling Kent

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2T7OHJ2"
          target = "_blank"
        >
          DA16 1SY
        </g-link>
        <br /><br />
        <!--#WUFC -->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
       
        
      </p>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2EtqTqf"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
