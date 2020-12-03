<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Palace Theatre</h1>
      <g-link href="https://bit.ly/3c8KDQB" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1600421936/palace_sz9m3e.jpg"
       alt   = "Palace Theatre"
      /></g-link>
       <p class="text-blue-200"> 
      113 Shaftesbury Avenue<br /> Soho London 
 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2ZKLWzZ"
          target = "_blank"
        >
          W1D 5AY
        </g-link>

      </p>
       <h2 class="text-2xl event"> Whats On:</h2>
       <h2 class="text-2xl text-red-400"></h2>


      <g-link href="https://bit.ly/2ZPFw2O" target="_blank"
        ><g-image
       class = "w-auto h-auto"
       src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1600423482/potter_cppeei.jpg"
       alt   = "Harry Potter The Cursed Child Poster"
      /></g-link>
      
      
      <h2 class="text-2xl event">Harry Potter <br />The Cursed Child </h2>

      <p class="event">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Ends Sun 26 September 2021<br /><br />
       </p>
    
     
    

<article class="event">
   Harry Potter and the Cursed Child is <br />one play presented in two Parts..... 

  <input id="read-more-palace-1" class="read-more-palace" type="checkbox">
  <div class="read-more-content">
       which are intended to be <br />seen in order on the same day<br /> matinee and evening <br />or on two consecutive evenings.

  </div>
  <label aria-label="open read more or less" class="read-more-palace-label postcode hover:text-white" for="read-more-palace-1">Read </label>
</article>

<h2 class="text-2xl event">video of behind the scenes</h2>
<iframe aria-label="iframe youtube video" width="290" height="200" src="https://www.youtube.com/embed/UjFaRoumUbA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
<g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3c8KDQB"
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
.read-more-palace {
  display: none;
}
.read-more-palace-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-palace-label:after {
  content: "More";
  display: inline-block;
}
.read-more-palace:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-palace:checked + .read-more-content + .read-more-palace-label:after {
  content: "Less";
}
</style>
