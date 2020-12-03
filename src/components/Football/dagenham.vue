<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Dagenham
      </h2>
      <g-link href="http://bit.ly/2FRgg4A" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/dagenham.jpg"
          alt   = "dagenham"
      /></g-link>
      <p class="text-blue-200 text-center">
        Dagenham Football Centre<br />
      138 Manor Road<br />
      Dagenham Essex

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3863055"
          target = "_blank"
        >
          RM10 8BJ
        </g-link>
        
      </p>

      <br />

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/3a14ejS"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
