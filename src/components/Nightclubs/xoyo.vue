<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-glass-cheers"></i>
        </span> XOYO</H2>
      <g-link href="http://bit.ly/2U4qK37" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/nightclubs/xoyo.jpg"
          fluid-grow
          alt = "XOYO"
      /></g-link>
      <p class="text-blue-200">
        32-37 Cowper Steet<br />
        Shoredich London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3a55TUV"
          target = "_blank"
        >
          EC2A 4AW
        </g-link>
      </p>
      <h5 class="text-2xl text-pink-300">Closed</h5>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Fri 27 March 21.30 - 04.00-->
      </p>


      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2U4qK37"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
