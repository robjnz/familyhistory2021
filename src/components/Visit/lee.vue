<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Lee Valley</h1>
      <g-link href="http://bit.ly/2AiFQuA" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/lee.jpg"
          fluid-grow
          alt = "Lee Valley"
      /></g-link>
      <p class="text-blue-200">
       Lea Bridge Road<br /> Leyton London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2vjyLdy"
          target = "_blank"
        >
           E10 7QL
        </g-link>
      </p>

     <br /><br /><br />

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2AiFQuA"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>




