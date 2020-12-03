<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        London Canal Museum
</h1
      >
      <g-link href="https://bit.ly/2QM1sHC" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1585238658/canal_i4h6sm.jpg"
          fluid-grow
          alt = "London Canal Museum"
      /></g-link>
      <p class="text-blue-200">
        12-13 New Wharf Road<br /> London
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/39lS6ZF"
          target = "_blank"
        >
          N1 9RT
        </g-link>
      </p>
      
       <h2 class=" mb-4 text-2xl text-pink-300"></h2>
      <article class="text-blue-200">
  Learn about the history of London's<br /> canals the cargoes they carried ....... 
  <input id="read-more-canal-1" class="read-more-canal" type="checkbox">
  <div class="read-more-content">
 the people who lived<br /> worked on the waterways.
  </div>
  <label class="read-more-canal-label postcode hover:text-white" for="read-more-canal-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2QM1sHC"
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
.read-more-canal {
  display: none;
}
.read-more-canal-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-canal-label:after {
  content: "More";
  display: inline-block;
}
.read-more-canal:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-canal:checked + .read-more-content + .read-more-canal-label:after {
  content: "Less";
}
</style>
