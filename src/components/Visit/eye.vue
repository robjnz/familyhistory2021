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
        </span>  London Eye</h1>
      <g-link href="https://bit.ly/31rwCJX" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1598429442/eye_xftyp0.jpg"
          alt   = "London Eye"
      /></g-link>
      <p class="text-blue-200">
        Riverside Building<br /> County Hall London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2Eyonmo"
          target = "_blank"
        >
          SE1 7PB
        </g-link>
      </p>
      
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £31.00 <br />Children: £25.00 
    <br /><br />
   
      Opening Times: <br />Monday To Sunday<br />
      10.00am To 6.00pm  <br />Required To Book Online<br />

      

      </h2>
    
      <article class="text-blue-200">
   Observation wheel giving passengers<br /> a bird's-eye view of Londons landmarks.......
<input id="read-more-eyek-1" class="read-more-eyek" type="checkbox">

  <div class="read-more-content">
<br />
......
</div>
<label class="read-more-eyek-label postcode hover:text-white" for="read-more-eyek-1">Read </label>
</article>

<br />
<iframe class="h-32 w-full object-fill" src="https://www.youtube.com/embed/e6TH2wJQD4g" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/31rwCJX"
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
.read-more-eyek {
  display: none;
}
.read-more-eyek-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-eyek-label:after {
  content: "More";
  display: inline-block;
}
.read-more-eyek:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-eyek:checked + .read-more-content + .read-more-eyek-label:after {
  content: "Less";
}
</style>
