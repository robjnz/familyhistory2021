<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Royal Museums </h1>
        
      <g-link href="http://bit.ly/2yibjM1" target="_blank"
        ><g-image class="h-32 w-full object-fill"
          src = "@/images/visit/greenwich.jpg"
          fluid-grow
          alt = "Royal Museums Greenwich"
      /></g-link>
      <p class="text-blue-200">
        Romney Road<br /> Greenwich London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/39NF5sD"
          target = "_blank"
        >
          SE10 9NF
        </g-link>
      </p>

        <h2 class=" mb-4 text-2xl text-pink-300"></h2>

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2yibjM1"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>


