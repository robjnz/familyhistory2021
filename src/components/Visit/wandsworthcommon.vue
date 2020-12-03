<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Wandsworth Common  </h1>
      <g-link href="https://bit.ly/2UQCF7I" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/wandsworthcommon.jpg"
          alt   = "wandsworth Common"
      /></g-link>
      <p class="text-blue-200">
      Trinity Road <br />Wandsworth London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2UR5Vv2"
          target = "_blank"
        >
          SW18 3RT
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
There are woods<br /> lakes, and heath.....
<input id="read-more-wandsworthcommon-1" class="read-more-wandsworthcommon" type="checkbox">
  <div class="read-more-content">

 as well as playgrounds,<br /> café, bowls and tennis,<br /> and a trim trail.
  </div>
 <label class="read-more-wandsworthcommon-label postcode hover:text-white" for="read-more-wandsworthcommon-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2UQCF7I"
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
.read-more-wandsworthcommon {
  display: none;
}
.read-more-wandsworthcommon-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-wandsworthcommon-label:after {
  content: "More";
  display: inline-block;
}
.read-more-wandsworthcommon:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-wandsworthcommon:checked + .read-more-content + .read-more-wandsworthcommon-label:after {
  content: "Less";
}
</style>
