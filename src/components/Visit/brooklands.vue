<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Brooklands Museum </h1>
      <g-link href="https://bit.ly/30s25es" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/brooklands.jpg"
          alt   = "Brooklands Museum"
      /></g-link>
      <p class="text-blue-200">
        Brooklands Drive<br /> Weybridge Surrey 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/33tvqHm"
          target = "_blank"
        >
          KT13 0SL
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £16.30 <br />Concession £15.30 <br />Children: £8.95 
<br />Family: £42.55<br /><br />
   
      Opening Times: <br />Thurs To Sun<br />
      10.00am To 5.00pm  <br />Required To Book Online<br />

      

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

Brooklands Museum celebrates<br /> the history of aviation......
<input id="read-more-brooklands-1" class="read-more-brooklands" type="checkbox">
  
  <div class="read-more-content">
<br />
Loch Ness Wellington Bomber, <br />Concorde, McLaren F1 racing Car <br />amd much more!
</div>
<label class="read-more-brooklands-label postcode hover:text-white" for="read-more-brooklands-1">Read </label>
</article>

<br />
      <iframe class="h-32 w-full object-full" title="video Brooklands Museum 2.13 minute long" src="https://www.youtube.com/embed/lRps-EEo-zw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/30s25es"
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
.read-more-brooklands {
  display: none;
}
.read-more-brooklands-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-brooklands-label:after {
  content: "More";
  display: inline-block;
}
.read-more-brooklands:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-brooklands:checked + .read-more-content + .read-more-brooklands-label:after {
  content: "Less";
}
</style>
