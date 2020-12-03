<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Elizabeth's Hunting Lodge</h1>
      <g-link href="http://bit.ly/2Sgs9D9" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/elizabeth.jpg"
          fluid-grow
          alt = "Elizabeth's Hunting Lodge"
      /></g-link>
      <p class="text-blue-200">
         Hunting Lodge 6 Rangers Road<br /> Chingford London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/33bTP2g"
          target = "_blank"
        >
         E4 7QH
        </g-link>
      </p>

           <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2Sgs9D9"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
