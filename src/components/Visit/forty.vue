<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Forty Hall
</h1
      >
      <g-link href="https://bit.ly/3aw80SF" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/fortyhill.jpg"
          alt = "Forty Hall"
      /></g-link>
      <p class="text-blue-200">
        Forty Hill<br /> Enfield Middlesex  
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2ybi3OD"
          target = "_blank"
        >
           EN2 9HA
        </g-link>
      </p>
      
       <h2 class=" mb-4 text-2xl text-pink-300"></h2>
      <article class="text-blue-200">
  Grade 1 Listed Jacobean Manor House<br /> 
....... 
  <input id="read-more-forty-1" class="read-more-forty" type="checkbox">
  <div class="read-more-content">
      <br />
 Landscaped with an Ornamental lake<br /> medieval fishing ponds and streams,<br /> a walled garden.

  </div>
  <label class="read-more-forty-label postcode hover:text-white" for="read-more-forty-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3aw80SF"
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
.read-more-forty {
  display: none;
}
.read-more-forty-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-forty-label:after {
  content: "More";
  display: inline-block;
}
.read-more-forty:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-forty:checked + .read-more-content + .read-more-forty-label:after {
  content: "Less";
}
</style>
