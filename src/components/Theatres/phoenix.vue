<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Phoenix Theatre</h1>
      <g-link href="https://bit.ly/3hKDaZe" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1600587286/phonix_lhwp6d.jpg"
       alt   = "Phoenix Theatre"
      /></g-link>
       <p class="text-blue-200"> 
      Charing Cross Road<br /> West End London 
 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2Enchgk"
          target = "_blank"
        >
          WC2H 0JP
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
        <g-link href="https://bit.ly/32Kjlg7" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1600589526/comeaway_hsf05x.jpg"
       alt   = "Harry Potter The Cursed Child Poster"
      /></g-link>
      <br />
      <h2 class="text-2xl event">Come From Away </h2>

      <p class="event">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       4 Jan 2021<br />
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        Mon 8 May 2021
       <br />
       </p>
    


      


<article class="event">
 Real-life story of the 7,000 <br />air passengers from all over the world..... 
  <input id="read-more-phoenix-1" class="read-more-phoenix" type="checkbox">
  <div class="read-more-content">
     
 Who were grounded in Canada <br />during the wake of 9/11.
  </div>
  <label class="read-more-phoenix-label postcode hover:text-white" for="read-more-phoenix-1">Read </label>
</article>
   



<iframe width="290" height="200" src="https://www.youtube.com/embed/tGrPEJIMyqM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
<g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3hKDaZe"
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
.read-more-phoenix {
  display: none;
}
.read-more-phoenix-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-phoenix-label:after {
  content: "More";
  display: inline-block;
}
.read-more-phoenix:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-phoenix:checked + .read-more-content + .read-more-phoenix-label:after {
  content: "Less";
}
</style>
