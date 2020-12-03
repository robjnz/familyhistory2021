<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
           <i class="fas fa-arrow-alt-circle-chislehurst"></i>
        </span> Chislehurst Caves</h1>
      <g-link href="https://bit.ly/2UHY5ni" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/chislehurst.jpg"
          alt = "Chislehurst Caves"
      /></g-link>
      <p class="text-blue-200">
        Old Hill<br /> Chislehurst Kent

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/39GYlXR"
          target = "_blank"
        >
          BR7 5NL
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £7.00 <br />Senior Concession £5.00 <br />Children: £5.00 
     <br /><br />
   
      Opening Times: <br />Wed To Sun<br />
      10.00 am To 4.00 pm 

      

      </h2>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
  The caves have been carved<br />out, over hundreds of years...... 
  <input id="read-more-chislehurst-1" class="read-more-chislehurst" type="checkbox">
  <div class="read-more-content">
        They were dug for the chalk to<br /> use in lime burning<br /> and brick making of<br /> Building London<br /> as well as for flints<br /> to fire the tinderboxes<br /> and flintlock guns.

  </div>
  <label class="read-more-chislehurst-label postcode hover:text-white" for="read-more-chislehurst-1">Read </label>
</article>

        <iframe class="h-32 w-full object-fill" aria-label="youtube-video" title="video of Chislehurst Caves 1.40 minutes" src="https://www.youtube.com/embed/yCkmwuYQxAY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2UHY5ni"
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
.read-more-chislehurst {
  display: none;
}
.read-more-chislehurst-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-chislehurst-label:after {
  content: "More";
  display: inline-block;
}
.read-more-chislehurst:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-chislehurst:checked + .read-more-content + .read-more-chislehurst-label:after {
  content: "Less";
}
</style>
