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
        </span>  Shreks Adventure </h1>
      <g-link href="https://bit.ly/32vJMF0" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/shrek.jpg"
          alt   = "Shreks Aadventure"
      /></g-link>
      <p class="text-blue-200">
        County Hall<br />Westminster London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2YyXlCH"
          target = "_blank" aria-label="open new window"
        >
          SE1 7PB
        </g-link>
      </p>
      
        <h2 class=" mb-4 text-base text-orange-300">
    
        
      Adult: 28.50 <br />Children: £23.00
<br />Family: £70.00<br /><br />
   
      Opening Times: <br />Monday To Sunday<br />
      10.00am To 3.00pm  <br />Required To Book Online<br />

      

      </h2>
      
      <article class="text-blue-200">
   Visit the magical world <br />of Shreks Adventure.......
<input id="read-more-shreksadventure-1" class="read-more-shreksadventure" type="checkbox">

  <div class="read-more-content">
<br />
  The swamp, <br />Rumplestilskin's carriage,<br /> the poison apple pub, <br />and the mirror maze.

</div>
<label class="read-more-shreksadventure-label postcode hover:text-white" for="read-more-shreksadventure-1">Read </label>
</article>

<br />
<iframe class="h-32 w-full object-fill" title="video virtual tour of shreks adventure 12.50 minute long " src="https://www.youtube.com/embed/rmPyxjYXlp4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />

      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/32vJMF0"
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
.read-more-shreksadventure {
  display: none;
}
.read-more-shreksadventure-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-shreksadventure-label:after {
  content: "More";
  display: inline-block;
}
.read-more-shreksadventure:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-shreksadventure:checked + .read-more-content + .read-more-shreksadventure-label:after {
  content: "Less";
}
</style>
