<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-football-ball"></i>
        </span>
        Barking
      </h2>
      <g-link href="https://bit.ly/2U9i51T" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/rugby/barkingR.png"
          alt   = "Barking"
      /></g-link>
      <p class="text-blue-200 text-center">
        Gale Street <br />Goresbrook<br />
        Dagenham Essex

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2UuZY5n"
          target = "_blank"
        >
          RM9 4TX
        </g-link>
        <br /><br />
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
       

        <br />
      </p>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/2U9i51T"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
