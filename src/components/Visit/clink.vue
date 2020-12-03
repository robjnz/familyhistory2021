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
  end-->
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Clink Prison Museum </h1>
      <g-link href="https://bit.ly/2LQZOkS" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/clink.jpg"
          alt   = "clink Prison Museum"
      /></g-link>

      <p class="text-blue-200">
        1 clink Street <br />Southwark London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3gfGKef"
          target = "_blank"
        >
          SE1 9DG
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £8.50 <br />Concession £6.50 <br />Children: £6.50 
<br />Family: £24.20<br /><br />
   
      Opening Times: <br />Mon To Sun<br />
      10.00am To 9.00pm  <br />Required To Book Online<br />

      

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
   The clink Prison dates back to 1144 <br />making it one of England’s oldest.......
<input id="read-more-clink-1" class="read-more-clink" type="checkbox">

  <div class="read-more-content">
<br />
   and most notorious prisons.<br /><br />There are opportunities to view <br />archaeological artefacts, <br />experience the sights, sounds <br />and smells of the prison.

</div>
<label class="read-more-clink-label postcode hover:text-white" for="read-more-clink-1">Read </label>
</article>

        <iframe class="h-32 w-full object-fill" aria-label="youtube-video" title="video of Clink prison 9.22 minutes" src="https://www.youtube.com/embed/7U3343jbRuU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2LQZOkS"
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
.read-more-clink {
  display: none;
}
.read-more-clink-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-clink-label:after {
  content: "More";
  display: inline-block;
}
.read-more-clink:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-clink:checked + .read-more-content + .read-more-clink-label:after {
  content: "Less";
}
</style>
