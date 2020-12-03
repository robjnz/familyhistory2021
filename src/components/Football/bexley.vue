<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Bexley United
      </h2>
      <g-link href="http://bit.ly/3a7andQ" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/bexley.jpg"
          alt   = "Bexley"
      /></g-link>
      <p class="text-blue-200 text-center">
         Metrogas <br />40 Foot Way Avery Hill Road<br />Eltham London 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/396WTyD"
          target = "_blank"
        >
          SE9 2EX
        </g-link>
        <br />
      
      </p>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/3a7andQ"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
