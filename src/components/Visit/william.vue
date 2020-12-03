<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> William Morris Gallery</h1>
      <g-link href="http://bit.ly/2IHVzGL" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/william.jpg"
          fluid-grow
          alt = "William Morris Gallery"
      /></g-link>
      <p class="text-blue-200">
        Forest Road<br />
Walthamstow London


        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2TMbUAL"
          target = "_blank"
        >
         E17 4PP 
        </g-link>
      </p>
             <h2 class=" mb-4 text-2xl text-pink-300"></h2>

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2IHVzGL"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>




  <b-card
    bg-variant   = "dark"
    text-variant = "white"
    title        = "William Morris Gallery & Park"
  >
    <g-link href="https://kutt.it/william-morris" target="_blank"
      ><b-img
        src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1521646578/williammorris_kvmpj8.jpg"
        fluid-grow
        alt = "William Morris Gallery"
    /></g-link>
  </b-card>
</template>
