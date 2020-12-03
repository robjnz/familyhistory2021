<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Red House </h1>
      <g-link href="http://bit.ly/2OK74SV" target="_blank"
        ><g-image class="h-32 w-full object-fill"
          src = "@/images/visit/red.jpg"
          alt = "Red House"
      /></g-link>
      <p class="text-blue-200">
        Red House Lane<br /> Bexleyheath London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/3aLrxho"
          target = "_blank"
        >
          DA6 8JF
        </g-link>
      </p>

       <h2 class="text-2xl text-pink-300">Closed</h2>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Sat 4 to Sat 18 April-->
      </p>
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2OK74SV"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>

