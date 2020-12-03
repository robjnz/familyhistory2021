<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Aldwych Theatre</h1>
      <g-link href="https://bit.ly/2Pzll3z" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1596875438/adelphi_l3dkbk.jpg"
       alt   = "Aldwych Theatre poster"
      /></g-link>
       
      <p class="text-blue-200"> 
      49 Aldwych<br /> London 
 
 <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/31vEHwb"
          target = "_blank"
        >
          WC2B 4DF
        </g-link>
        
      
      </p>
      <h3 class="text-2xl text-red-400">Closed <!--The Tina Turner Musica--></h3>
  <!--    
      <p class="text-orange-300">

          <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        
        Mon: 7.30pm<br />
        Tues: 7.00pm<br />
        Wed – Sat: 7.30pm<br />
        Thurs & Sat: 2.30pm<br />
      </p>
    -->
<!--
<article class="text-blue-200">
   Mary Poppins, a mystical nanny returns <br />to London....
  <input id="read-more-angel-1" class="read-more-angel" type="checkbox">
  <div class="read-more-content">
         To save the day in this musical dance <br />show suitable for all.

  </div>
  <label class="read-more-angel-label text-red-700 hover:text-white" for="read-more-angel-1">Read </label>
</article>
    -->

<br />
<g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2Pzll3z"
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
.read-more-angel {
  display: none;
}
.read-more-angel-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-angel-label:after {
  content: "More";
  display: inline-block;
}
.read-more-angel:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-angel:checked + .read-more-content + .read-more-angel-label:after {
  content: "Less";
}
</style>