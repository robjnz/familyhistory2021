<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Geffrye Museum</h1>
      <g-link href="http://bit.ly/3cU96J8" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/geffrye.jpg"
          alt = "Geffrye Museum"
      /></g-link>
      <p class="text-blue-200">
       136 Kingsland Road<br />Hackney London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/38KPSTg"
          target = "_blank"
        >
          E2 8EA
        </g-link>
      </p>
            <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>

     
    
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/3cU96J8"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
