<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Wansted Park</h1>
      <g-link href="http://bit.ly/2Jda6JW" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/wanstead.jpg"
          fluid-grow
          alt = "Wansted Park"
      /></g-link>
      <p class="text-blue-200">
        Warren Road <br />Wanstead London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/38Qiz0S"
          target = "_blank"
        >
         E11 2LU
        </g-link>
      </p>
     <br /><br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2Jda6JW"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>



