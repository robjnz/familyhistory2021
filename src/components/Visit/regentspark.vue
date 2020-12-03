<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Regent's Park</h1>
      <g-link href="https://bit.ly/2XZrGed" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/regentspark.jpg"
          alt   = "regents park"
      /></g-link>
      <p class="text-blue-200">
     Chester Road<br />Camden London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2Kl5a7l"
          target = "_blank"
        >
          NW1 4NR
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
 The park also provides a<br /> warm welcome for wildlife........
<input id="read-more-regentspark-1" class="read-more-regentspark" type="checkbox">

  <div class="read-more-content">
<br />
 It has a large wetland area <br />and is home to around 100 species<br /> of wild bird and a breeding <br />population of hedgehogs.
 </div>
<label class="read-more-regentspark-label postcode hover:text-white" for="read-more-regentspark-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2XZrGed"
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
.read-more-regentspark {
  display: none;
}
.read-more-regentspark-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-regentspark-label:after {
  content: "More";
  display: inline-block;
}
.read-more-regentspark:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-regentspark:checked + .read-more-content + .read-more-regentspark-label:after {
  content: "Less";
}
</style>
