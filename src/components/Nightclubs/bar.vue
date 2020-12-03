<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-glass-cheers"></i>
        </span> Bar300</H2>
      <g-link href="http://bit.ly/2tAKwYs" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/nightclubs/bar.jpg"
          fluid-grow
          alt = "Bar300"
      /></g-link>
      <p class="text-blue-200">
        300 Hoe Street<br />
        Walthamstow London

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/2PoH7Hq"
          target = "_blank"
        >
          E17 9QD
        </g-link>
      </p>
      <br /><br /><br />
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2tAKwYs"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
