<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Mudchute</h1>
      <g-link href="http://bit.ly/2CXL8ON" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/mudchute.jpg"
          fluid-grow
          alt = "Mudchute"
      /></g-link>
      <p class="text-blue-200">
        Pier Street<br />
        Isle of Dogs London

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2QaOYJd"
          target = "_blank"
        >
          E14 3HP
        </g-link>
        <br /><br /><br />
      </p>
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2CXL8ON"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
