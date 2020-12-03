<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-glass-cheers"></i>
        </span> Faces</H2>
      <g-link href="http://bit.ly/2wL0pAh" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/nightclubs/faces.jpg"
          fluid-grow
          alt = "Faces"
      /></g-link>
      <p class="text-blue-200">
        458-462 Cranbrook Road <br />Gants Hill Ilford Essex

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3a5iCak"
          target = "_blank"
        >
          IG2 6LE
        </g-link>
      </p>
      <h5 class="text-2xl text-pink-300">Closed</h5>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Fri 3 April 8 pm - 3 am-->
      </p>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2wL0pAh"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
