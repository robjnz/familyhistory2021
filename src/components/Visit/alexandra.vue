<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">

<!--pick 

       <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i aria-hidden="true" role="none" class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of <br />places to visit in London is:
          
          </h1>

  end-->

      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i aria-hidden="true" role="none" class="fas fa-landmark"></i>
        </span>
        Alexandra Palace 
</h1>

      <g-link href="https://bit.ly/2vTGGyw" target="_blank" aria-label="open new window" 
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/v1585222919/alexandra_d4foln.jpg"
          alt = "Alexandra Palace "
      /></g-link>

      
      <p class="text-blue-200">
        Alexandra Palace Way<br /> London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2xtJORT"
          target = "_blank" aria-label="open new window"
        >
           N22 7AY
        </g-link>
      </p>

       <h2 class="text-2xl event"> Events:</h2>
      
       
      <article class="text-blue-200">
  Grade II listed entertainment<br /> and sports venue....... 
  <input id="read-more-alexandra-1" class="read-more-alexandra" type="checkbox">
  <div class="read-more-content">
 and park with views across london.
  </div>
  <label class="read-more-alexandra-label postcode hover:text-white" for="read-more-alexandra-1">Read </label>
</article>

      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2vTGGyw"
        target = "_blank" aria-label="open new window"
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
.read-more-alexandra {
  display: none;
}
.read-more-alexandra-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-alexandra-label:after {
  content: "More";
  display: inline-block;
}
.read-more-alexandra:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-alexandra:checked + .read-more-content + .read-more-alexandra-label:after {
  content: "Less";
}
</style>
