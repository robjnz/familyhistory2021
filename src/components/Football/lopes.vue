<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Lopes Tavares
      </h2>
      <g-link href="http://bit.ly/2QxsJ2w" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/lopes.png"
          alt   = "Lopes Tavares"
      /></g-link>
      <p class="text-blue-200 text-center">
        Terence Mcmillan Stadium <br />
      281 Prince Regent Lane<br />London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2x9OXi1"
          target = "_blank"
        >
          E13 8SD
        </g-link>
        <br /><br />
        
      </p>
      

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        
      </p>

      


      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2QxsJ2w"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
