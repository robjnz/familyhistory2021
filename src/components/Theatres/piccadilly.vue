<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Piccadilly Theatre</h1>
      <g-link href="https://bit.ly/32Nb635" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1600711155/piccadilly_duq5xh.jpg"
       alt   = "Piccadilly Theatre"
      /></g-link>
       <p class="text-blue-200"> 
      16 Denman Street<br /> Soho London 
 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2Ek438v"
          target = "_blank"
        >
          W1D 7DY
        </g-link>

      </p>
       <h2 class="text-2xl event"> Whats On:</h2>
       <h2 class="text-2xl text-red-400">Closed</h2>

       <!--
        <g-link href="https://bit.ly/2ZPFw2O" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1600423482/potter_cppeei.jpg"
       alt   = "Harry Potter The Cursed Child Poster"
      /></g-link>
      -->
     
      <h2 class="text-2xl event"> Coming Soon:</h2>
        <g-link href="https://bit.ly/32PL3bF" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1600711566/moulin_fydxdg.jpg"
       alt   = "Moulin Rouge Poster"
      /></g-link>
      <br />
      <h2 class="text-2xl event">Moulin Rouge </h2>

      <p class="event">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Autumn 2021<br />
       <!--
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        Mon 8 May 2021
       <br />

       -->
       </p>
    


      


<article class="event">
Bohemians and aristocrats rub elbows<br /> and revel in electrifying enchantment.......

  <input id="read-more-piccadilly-1" class="read-more-piccadilly" type="checkbox">
  <div class="read-more-content">
     
 Pop the champagne and prepare for<br /> the spectacular spectacular.  </div>
  <label class="read-more-piccadilly-label postcode hover:text-white" for="read-more-piccadilly-1">Read </label>
</article>
   


<iframe width="290" height="200" src="https://www.youtube.com/embed/wlEaUz-5JpM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
<g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/32Nb635"
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
.read-more-piccadilly {
  display: none;
}
.read-more-piccadilly-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-piccadilly-label:after {
  content: "More";
  display: inline-block;
}
.read-more-piccadilly:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-piccadilly:checked + .read-more-content + .read-more-piccadilly-label:after {
  content: "Less";
}
</style>
