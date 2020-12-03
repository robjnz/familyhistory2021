<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Mayesbrook Park </h1>
      <g-link href="http://bit.ly/2Q7ZlO3" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/mayesbrook.jpg"
          fluid-grow
          alt = "Mayesbrook Park"
      /></g-link>
      <p class="text-blue-200">
        Lodge Avenue<br /> Dagenham Essex

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/33efo23"
          target = "_blank"
        >
          RM8 2JA
        </g-link>
      </p>

      <br /><br /><br />

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2Q7ZlO3"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
