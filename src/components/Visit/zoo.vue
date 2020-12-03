<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
       
<!--pick --
       <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of <br />places to visit in London is:
          
          </h1>
 -- end-->
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        London Zoo 
</h1>

      <g-link href="https://bit.ly/2xspOPI" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/v1585290413/zoo_bpl1vd.jpg"
          alt = "London zoo"
      /></g-link>
      <p class="text-blue-200">
        Regent's Park Outer Circle<br /> London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2wwYm3r"
          target = "_blank" aria-label="open new window"
        >
          NW1 4RY
        </g-link>
      </p>

     <h2 class=" mb-4 text-base text-orange-300">
        <br />
      Adults: £32.50 <br />Concession £29.25 <br />Children: £21.12 
<br /><br />
   
      Opening Times: <br />Monday To Sunday<br />
      Morning 10am To 2pm <br /> Afternoon 2pm To 6pm <br />Required To Book Online<br />

      

      </h2>
      
      <article class="text-blue-200">
  Collection of 673 species<br /> of animals....... 
  <input id="read-more-zoo-1" class="read-more-zoo" type="checkbox">
  <div class="read-more-content">
  mammals birds, reptiles, <br />fish and insects, including <br />a number of rare and endangered species.
  </div>
  <label class="read-more-zoo-label postcode hover:text-white" for="read-more-zoo-1">Read </label>
</article>

<br />
      <iframe class="h-32 w-full object-fill" title="london zoo video 30 minute long" src="https://www.youtube.com/embed/fygyNQAzRFM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />

      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2xspOPI"
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
.read-more-zoo {
  display: none;
}
.read-more-zoo-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-zoo-label:after {
  content: "More";
  display: inline-block;
}
.read-more-zoo:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-zoo:checked + .read-more-content + .read-more-zoo-label:after {
  content: "Less";
}
</style>
