<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-glass-cheers"></i>
        </span> ATIK</H2>
      <g-link href="http://bit.ly/2V7L97A" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "@/images/nightclubs/atik.jpg"
          fluid-grow
          alt = "ATIK"
      /></g-link>
      <p class="text-blue-200">
        108 South Street<br />
        Romford Essex

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "http://bit.ly/3a3Bx5l"
          target = "_blank"
        >
          RM1 1SS
        </g-link>
      </p>
      <h5 class="text-2xl text-pink-300">Closed</h5>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Fri 20 March 10 pm- 4 am-->
      </p>
      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "http://bit.ly/2V7L97A"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
