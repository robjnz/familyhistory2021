<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Fairlop Waters Park</h1>
      <g-link href="http://bit.ly/3cvMXRv" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/fairlop.jpg"
          fluid-grow
          alt = "Fairlop Waters Park"
      /></g-link>
      <p class="text-blue-200">
        Forest Road<br />
Barkingside Essex 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2vNapsT"
          target = "_blank"
        >
          IG6 3HN
        </g-link>
          <h2 class=" mb-4 text-2xl text-pink-300"></h2>
      <article class="text-blue-200">
  Fairlop Waters Country Park <br />is part of the larger Fairlop Plain........ 
  <input id="read-more-fairlop-1" class="read-more-fairlop" type="checkbox">
  <div class="read-more-content">
      <br />
 The famous Fairlop Oak was reputedly<br /> the largest tree in Hainault Forest,<br /> the site of a famous fair held <br />on the first Friday<br /> in July until around 1892.
  </div>
  <label class="read-more-fairlop-label postcode hover:text-white" for="read-more-fairlop-1">Read </label>
</article>
    
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/3cvMXRv"
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
.read-more-fairlop {
  display: none;
}
.read-more-fairlop-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-fairlop-label:after {
  content: "More";
  display: inline-block;
}
.read-more-fairlop:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-fairlop:checked + .read-more-content + .read-more-fairlop-label:after {
  content: "Less";
}
</style>
