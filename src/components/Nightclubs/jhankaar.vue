<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-glass-cheers"></i>
        </span> Jhankaar Club</H2>
      <g-link href="http://bit.ly/2EsnHfH" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/nightclubs/jhankaar.jpg"
          fluid-grow
          alt = "Jhankaar Club"
      /></g-link>
      <p class="text-blue-200">
        27 Broadway<br />
Stratford London 

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/32txb4Q"
          target = "_blank"
        >
          E15 4BQ
        </g-link>
      </p>
     <br /><br /><br />
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2EsnHfH"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
