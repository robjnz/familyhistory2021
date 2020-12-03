<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
       Erith Town
      </h2>
      <g-link href="http://bit.ly/2zRykq3" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/erith.jpg"
          alt   = "Erith Town"
      /></g-link>
      <p class="text-blue-200 text-center">
        Erith Stadium <br />Erith Avenue Road <br />Erith Kent

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3clNVzN"
          target = "_blank"
        >
          DA8 3AT
        </g-link>
        <br /><br />
       <!-- #barkingfc -->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        
    </p>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2zRykq3"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
