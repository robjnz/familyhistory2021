<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Lewisham Bouough
      </h2>
      <g-link href="http://bit.ly/32EJRGo" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/lewisham.jpg"
          alt   = "lewisham"
      /></g-link>
      <p class="text-blue-200 text-center">
        Ladywell Arena<br />
      Silvermere Road<br />
      Catford London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2TrGzSA"
          target = "_blank"
        >
          SE6 4QX
        </g-link>
      
        
      </p>

    <br />
       
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/32EJRGo"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
