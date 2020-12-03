<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Bethune Nature Reserve</h1>
        
      <g-link href="https://bit.ly/3asPxGc" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1585076334/bethune_c02oyh.jpg"
          fluid-grow
          alt = "Bethune Nature Reserve"
      /></g-link>
      <p class="text-blue-200">
        Beaconsfield Road<br />
        Friern Barnet London


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2WEXqEx"
          target = "_blank"
        >
          N11 3BB
        </g-link>
      </p>
      <br />
      <article class="text-blue-200">
  Nature Reserve and Wildlife Interest<br /> adjoins with ......<br /> 
  <input id="read-more-bethune-1" class="read-more-bethune" type="checkbox">
  <div class="read-more-content">
        Bethune Recreation Ground

  </div>
  <label class="read-more-bethune-label postcode hover:text-white" for="read-more-bethune-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3asPxGc"
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
.read-more-bethune {
  display: none;
}
.read-more-bethune-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-bethune-label:after {
  content: "More";
  display: inline-block;
}
.read-more-bethune:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-bethune:checked + .read-more-content + .read-more-bethune-label:after {
  content: "Less";
}
</style>
