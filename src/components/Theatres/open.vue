<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Open Air Theatre</h1>
      <g-link href="https://bit.ly/34FHMwN" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1598697106/open_twtnh5.jpg"
       alt   = "Open Air Theatre"
      /></g-link>
       <p class="text-blue-200"> 
      The Regent's Park<br /> Inner Cir London 
 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2QyNtUO"
          target = "_blank"
        >
          NW1 4NU
        </g-link>

      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <!--
      <p class="text-orange-300">
          <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Sun 15 - Sat 28 March
      </p>
    

<article class="text-blue-200">
   Mary Poppins, a mystical nanny returns <br />to London....
  <input id="read-more-open-1" class="read-more-open" type="checkbox">
  <div class="read-more-content">
         To save the day in this musical dance <br />show suitable for all.

  </div>
  <label class="read-more-open-label text-red-700 hover:text-white" for="read-more-open-1">Read </label>
</article>
    --> 

<br />
<g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/34FHMwN"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>



<style>


.read-more-content {
  max-height: 0;
  overflow  : hidden;
  transition: max-height .5s ease;
}
.read-more-open {
  display: none;
}
.read-more-open-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-open-label:after {
  content: "More";
  display: inline-block;
}
.read-more-open:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-open:checked + .read-more-content + .read-more-open-label:after {
  content: "Less";
}
</style>
