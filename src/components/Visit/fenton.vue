<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Fenton House
</h1>
      <g-link href="https://bit.ly/2Jl8df6" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1585240608/fenton_lxmlul.jpg"
          fluid-grow
          alt = "Fenton house"
      /></g-link>
      <p class="text-blue-200">
        Hampstead Grove<br /> London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3bqy9Ce"
          target = "_blank"
        >
          NW3 6RT
        </g-link>
      </p>
      
       <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>
      <article class="text-blue-200">
  17th-century house with walled garden ....... 
  <input id="read-more-fenton-1" class="read-more-fenton" type="checkbox">
  <div class="read-more-content">
 .....
  </div>
  <label class="read-more-fenton-label postcode hover:text-white" for="read-more-fenton-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2Jl8df6"
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
.read-more-fenton {
  display: none;
}
.read-more-fenton-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-fenton-label:after {
  content: "More";
  display: inline-block;
}
.read-more-fenton:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-fenton:checked + .read-more-content + .read-more-fenton-label:after {
  content: "Less";
}
</style>
