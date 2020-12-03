<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-futbol"></i>
        </span>
        Walthamstow
      </h2>
      <g-link href="http://bit.ly/2EwPMnp" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/football/walthamstow.jpg"
          alt   = "walthamstow"
      /></g-link>
      <p class="text-blue-200 text-center">
      Wadham Lodge Sports Ground<br />Kitchener Road <br />Walthamstow London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2Ij8u1Y"
          target = "_blank"
        >
          E17 4JP
        </g-link>
        <br /><br />
        <!--#walthamstowfc-->
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
       
      </p>

 
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2EwPMnp"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
