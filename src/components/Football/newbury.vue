<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Newbury Forest
      </h2>
      <g-link href="http://bit.ly/2ueptve" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/newbury.jpg"
          alt   = "Newbury Forest"
      /></g-link>
      <p class="text-blue-200 text-center">
           Oakside Stadium<br />Station Road <br />Barkingside Essex

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/3dlHcGf"
          target = "_blank"
        >
          IG6 1NB
        </g-link>
        <br /><br />
       <!-- #NewburyForestFC -->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
       <!-- Mon 13 April 3 pm <br /><span class="text-red-700">V</span>
        <br />May & Baker
        -->
      </p>

  
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2ueptve"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
