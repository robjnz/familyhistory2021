<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Newham City Farm</h1>
      <g-link href="http://bit.ly/2Q8dkDk" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/newham.jpg"
          fluid-grow
          alt = "Newham City Farm"
      /></g-link>
      <p class="text-blue-200">
        Stansfeld Road<br />
        Beckton London

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2W86YaM"
          target = "_blank"
        >
          E6 5LT
        </g-link>
      </p>
              <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>

      
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2Q8dkDk"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
