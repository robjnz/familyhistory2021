<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Marble Hill House</h1>
      <g-link href="https://bit.ly/3ab7wAo" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1586773061/mablehouse_schira.jpg"
          alt   = "marble hill house"
      /></g-link>
      <p class="text-blue-200">
        Richmond Road<br /> Twickenham London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3b6zdvc"
          target = "_blank"
        >
          TW1 2NL
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300">Gardens Open</h2>
       <h2 class=" mb-4 text-base text-orange-300">
        
      Gardens Are Free To Visit
<br /><br />
   
      Opening Times:<br /> Mon To Sun<br />
      7.00am To 7.30pm

      

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
Marble Hill was built for Henrietta Howard<br /> mistress of King George II.....
<input id="read-more-marblehouse-1" class="read-more-marblehouse" type="checkbox">

  <div class="read-more-content">
<br />
  when he was Prince of Wales,<br />  The house and gardens were intended<br /> as an Arcadian retreat<br /> from crowded 18th-century London.
 </div>
<label class="read-more-marblehouse-label postcode hover:text-white" for="read-more-marblehouse-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3ab7wAo"
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
.read-more-marblehouse {
  display: none;
}
.read-more-marblehouse-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-marblehouse-label:after {
  content: "More";
  display: inline-block;
}
.read-more-marblehouse:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-marblehouse:checked + .read-more-content + .read-more-marblehouse-label:after {
  content: "Less";
}
</style>
