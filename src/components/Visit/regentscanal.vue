<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Regents Canal</h1>
      <g-link href="https://bit.ly/3535DEI" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/regents.jpg"
          alt   = "regents canal"
      /></g-link>
      <p class="text-blue-200">
     
Pool of Little Venice<br />London


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2VWhMXP"
          target = "_blank"
        >
          W9 2PF
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
Built in the 1810s<br /> this waterway runs for 8.6 miles ......
<input id="read-more-regentscanal-1" class="read-more-regentscanal" type="checkbox">

  <div class="read-more-content">
<br />

through east and north-central <br />London between the Grand Union<br />canal at Paddington and the<br /> River Thames at Limehouse.
 </div>
<label class="read-more-regentscanal-label postcode hover:text-white" for="read-more-regentscanal-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3535DEI"
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
.read-more-regentscanal {
  display: none;
}
.read-more-regentscanal-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-regentscanal-label:after {
  content: "More";
  display: inline-block;
}
.read-more-regentscanal:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-regentscanal:checked + .read-more-content + .read-more-regentscanal-label:after {
  content: "Less";
}
</style>
