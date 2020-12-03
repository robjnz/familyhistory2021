<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
<!--pick 
       <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of <br />places to visit in London is:
          
          </h1>
  --end-->

      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> War Rooms</h1>

      <g-link href="https://bit.ly/2Agb347" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/warrooms.jpg"
          alt   = "Churchill War Rooms"
      /></g-link>

      

      <p class="text-blue-200">
        Clive Steps King Charles Street<br />Westminster London





        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2B8o67T"
          target = "_blank" aria-label="open new window"
        >
          SW1A 2AQ
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £22.00 <br />Concession £17.60 <br />Children: £11.00 
<br />Family: £57.25<br /><br />
   
      Opening Times: <br />Monday To Sunday<br />
      9.30am To 6.00pm  <br />Required To Book Online<br />

      

      </h2>
      <h1 class="text-2xl event"> Events:</h1>
      <!--events-->
      <h2 class="text-2xl event">Operation black Door</h2>
  
    <g-link href="https://bit.ly/3cphdxL" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/temp/blackdoor.jpg"
          alt   = "Churchill War Rooms operation black door poster"
      /></g-link>

      <p class="event">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thursday 26 November 2020<br />
        6.45pm to 10.15pm
       <br /><br />
      
      Uncover the secrets of Churchill’s <br />wartime bunker and encounter figures<br /> from the past, as you explore <br />the rooms where real wartime<br />history happened.
      </p>
      <!--end-->
      <br />
      
      
      <article class="text-blue-200">
   Discover Life in Churchill's<br /> War Bunker.......
<input id="read-more-warrooms-1" class="read-more-warrooms" type="checkbox">

  <div class="read-more-content">
<br />
  See historic images, objects<br /> and interviews with <br />the men and women<br /> who worked in the<br /> underground hideaway,<br /> revealing what it<br /> was like to work<br /> in secret alongside <br />Winston Churchill<br /> during the Second World War.

</div>
<label class="read-more-warrooms-label postcode hover:text-white" for="read-more-warrooms-1">Read </label>
</article>

<br />
     <iframe class="h-32 w-full object-fill" title="video virtual tour of Churchill War Rooms 1.50 minute long" src="https://www.youtube.com/embed/P7X79asos74" frameborder="0" allow="accelerometer; fullplay; encrypted-media; gyroscope; picture-in-picture" allowfullfull></iframe>

<br />

      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2Agb347"
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
.read-more-warrooms {
  display: none;
}
.read-more-warrooms-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-warrooms-label:after {
  content: "More";
  display: inline-block;
}
.read-more-warrooms:checked + .read-more-content {
  display: block;
  /* css animation won't work with "full"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-warrooms:checked + .read-more-content + .read-more-warrooms-label:after {
  content: "Less";
}
</style>
