<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Sutton House </h1>
      <g-link href="http://bit.ly/2QB1TXc" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/sutton.jpg"
          fluid-grow
          alt = "Sutton House"
      /></g-link>
      <p class="text-blue-200">
        2- 4 Homerton High Street<br /> Hackney London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/39NqFJf"
          target = "_blank"
        >
          E9 6JQ
        </g-link>
      </p>
      <h2 class="text-2xl text-pink-300">Closed</h2>

      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        
      </p>
-->
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2QB1TXc"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>

