<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Museum Of Childhood</h1>
      <g-link href="https://bit.ly/2yKcvL2" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/childhood.jpg"
          alt = "Museum of Childhood"
      /></g-link>


      <p class="text-blue-200">
        Cambridge Heath Road<br /> Bethnal Green London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/37oAEWN"
          target = "_blank"
        >
         E2 9PA
        </g-link>
        
            <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>

        
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2yKcvL2"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>


