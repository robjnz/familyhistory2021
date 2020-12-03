<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <H2 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-glass-cheers"></i>
        </span> The Underworld</H2>
      <g-link href="https://bit.ly/2X1jiu2" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1585733601/underworld_vltsqb.jpg"
          alt   = "The Underworld"
      /></g-link>
      <p class="text-blue-200">
        174 Camden High Street<br /> Camden Town London 
       

        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2yihC4W"
          target = "_blank"
        >
         NW1 0NE 
        </g-link><br />
         
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
        to     = "https://bit.ly/2X1jiu2"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
