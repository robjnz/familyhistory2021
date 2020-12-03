<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
       Forest Hill Park 
      </h2>
      <g-link href="http://bit.ly/2TqiECK" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/forest.jpg"
          alt   = "Forest Hill Park"
      /></g-link>
      <p class="text-blue-200 text-center">
        Ladywell Arena<br />
      Silvermere Road
      <br />Catford London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2Wso6bq"
          target = "_blank"
        >
          SE6 4QX
        </g-link>
        <br /><br />
       <!-- #barkingfc -->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Sat 11 April 3 pm  <br /><span class="text-red-700">V</span> <br />Sporting Club Thamesmead
     -->
      </p>
       

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2TqiECK"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
