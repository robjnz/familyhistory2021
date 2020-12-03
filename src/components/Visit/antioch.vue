<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> St. Margaret of Antioch </h1>
      <g-link href="http://bit.ly/2W9FpxW" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/antioch.jpg"
          alt = "St. Margaret of Antioch"
      /></g-link>
      <p class="text-blue-200">
        North Street<br />
        Barking Essex

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/39Q9NBk"
          target = "_blank"
        >
          IG11 8AS
        </g-link>
      </p>
      <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>


      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2W9FpxW"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
