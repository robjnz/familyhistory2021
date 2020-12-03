<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Orient
      </h2>
      <g-link href="http://bit.ly/2GsFU02" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/orient.jpg"
          alt   = "leyton orient"
      /></g-link>
      <p class="text-blue-200 text-center">
        Matchroom Stadium<br>Brisbane Road <br />Leyton London 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2PA8PRD"
          target = "_blank"
        >
          E10 5NF
        </g-link>
        <br /><br />
        <!-- #leytonorientfc -->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        
      </p>

       <!--

Sat 25 April 2020 @ 3pm <br>V<br>Exeter City <br>
-->
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2GsFU02"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
