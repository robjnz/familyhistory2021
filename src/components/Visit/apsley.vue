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
        </span>  Apsley House </h1>
      <g-link href="https://bit.ly/2Dwwijt" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1596361693/apsley_etjixy.jpg"
          alt   = "apsley house"
      /></g-link>
      <p class="text-blue-200">
       149 Piccadilly Hyde Park Corner<br /> London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3gnjpHh"
          target = "_blank" aria-label="open new window"
        >
          W1J 7NT
        </g-link>
      </p>
      
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £11.30 <br />Concession £10.20 <br />Children: £6.80 
<br />Family: £29.40<br /><br />
   
      Opening Times: <br />Monday To Sunday<br />
      <br />Required To Book Online<br />

      

      </h2>

        <h2 class="text-2xl event"> Events:</h2>
      <!--events-->
      <!--
      <h2 class="text-2xl text-teal-400">Operation black Door</h2>

      <p class="text-teal-400">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       <br />Thurs 26 November 2020<br />
        6.45pm to 10.15pm
       <br /><br />
      
      Uncover the secrets of Churchill’s <br />wartime bunker and encounter figures<br /> from the past, as you explore <br />the rooms where real wartime<br />history happened.
      </p>
      --end-->
      <br />

      <article class="text-blue-200">
    Built in the 1820s for <br />the Duke of Wellington....... 
<input id="read-more-apsley-1" class="read-more-apsley" type="checkbox">

  <div class="read-more-content">
<br />
collection of paintings, <br />silver and porcelain <br />many of the items <br />were presented to <br />the 1st Duke of Wellington<br /> after Waterloo.
</div>
<label class="read-more-apsley-label postcode hover:text-white" for="read-more-apsley-1">Read </label>
</article>

<br />
      <iframe  class="h-32 w-full object-fill" title="video virtual tour of the The Apsley House 0.39 minute long" src="https://www.youtube.com/embed/0iMBvabZKc4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2Dwwijt"
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
.read-more-apsley {
  display: none;
}
.read-more-apsley-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-apsley-label:after {
  content: "More";
  display: inline-block;
}
.read-more-apsley:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-apsley:checked + .read-more-content + .read-more-apsley-label:after {
  content: "Less";
}
</style>
