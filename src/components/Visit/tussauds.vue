<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">

      <!--pick-
       <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of <br />places to visit in London is:
          
          </h1>
  --end-->
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
       Madame Tussauds
</h1>
      <g-link href="https://bit.ly/2Dl68jE" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/tussauds.jpg"
          fluid-grow
          alt = "Madame Tussauds"
      /></g-link>
      <p class="text-blue-200">
        Marylebone Road<br />London

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2Dl7eMi"
          target = "_blank" aria-label="open new window"
        >
          NW1 5LR
        </g-link>
      </p>

        <h2 class=" mb-4 text-base text-orange-300">
        <br />
      Standard Ticket Entry: From £28.50
<br />Family Standard Entry From £26.50<br /><br />
   
      Opening Times: <br />Saturday To Tuesday<br />
      10.00am To 4.00pm  <br />Required To Book Online<br />

      

      </h2>
     
      <article class="text-blue-200">
   Wax replicas of famous celebrities<br /> & historic icons in themed galleries.....
  <input id="read-more-tussauds-1" class="read-more-tussauds" type="checkbox">
  
  <div class="read-more-content">
    <br />
   Royals, World Leaders, <br />A-List celebrities & Sports 
  </div>
  <label class="read-more-tussauds-label postcode hover:text-white" for="read-more-tussauds-1">Read </label>
</article>

<br />
      <iframe class="h-32 w-full object-fill" title="video virtual ture around madam tussauds 19.12 minute long" src="https://www.youtube.com/embed/erIIHHr_ZE0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />

      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2Dl68jE"
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
.read-more-tussauds {
  display: none;
}
.read-more-tussauds-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-tussauds-label:after {
  content: "More";
  display: inline-block;
}
.read-more-tussauds:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-tussauds:checked + .read-more-content + .read-more-tussauds-label:after {
  content: "Less";
}
</style>
