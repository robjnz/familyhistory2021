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
  --end-->
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Kew Gardens</h1>
      <g-link href="https://bit.ly/2VmFjRH" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1586788794/kew_huxnq3.jpg"
          alt   = "Kew Gardens"
      /></g-link>
      <p class="text-blue-200">
        Kew <br />Richmond London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2RwJwRw"
          target = "_blank" aria-label="open new window"
        >
          TW9 3AE
        </g-link>
      </p>
      
       <h2 class=" mb-4 text-base text-orange-300">
       
      Adults: £9.00 <br />Concession £8.00 <br />Children: £4.50
<br />Family: £21.00<br />
   <br />
      Opening Times:<br /> Monday To Sunday<br />
      10am To 6pm <br />
      Required To Book Online<br />

      

      </h2>
    
      <article class="text-blue-200">
Discover the world of science behind <br />the botanical collections.....
<input id="read-more-kew-1" class="read-more-kew" type="checkbox">

  <div class="read-more-content">
<br />
 with over 50,000 living plants<br /> to be found at <br />this World Heritage site.
 </div>
<label class="read-more-kew-label postcode hover:text-white" for="read-more-kew-1">Read </label>
</article>

<br />
     <iframe class="h-32 w-full object-fill" aria-label="youtube-video" title="video trailer of tour of kew 2.39 minutes" src="https://www.youtube.com/embed/ft4mXomLWqw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2VmFjRH"
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
.read-more-kew {
  display: none;
}
.read-more-kew-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-kew-label:after {
  content: "More";
  display: inline-block;
}
.read-more-kew:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-kew:checked + .read-more-content + .read-more-kew-label:after {
  content: "Less";
}
</style>
