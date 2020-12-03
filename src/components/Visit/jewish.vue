<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Jewish Museum
</h1>
      <g-link href="https://bit.ly/2JjppSy" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/jewish.jpg"
          alt = "Jewish Museum"
      /></g-link>
      <p class="text-blue-200">
        129–131 Albert Street<br /> Camden Town London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/39ow5t0"
          target = "_blank"
        >
           NW1 7N
        </g-link>
      </p>
      
       <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>
      <article class="text-blue-200">
  Social history of Jewish people<br /> across London....... 
  <input id="read-more-jewish-1" class="read-more-jewish" type="checkbox">
  <div class="read-more-content">
 and preserving the <br />disappearing heritage<br /> of London’s East End.
  </div>
  <label class="read-more-jewish-label postcode hover:text-white" for="read-more-jewish-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2JjppSy"
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
.read-more-jewish {
  display: none;
}
.read-more-jewish-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-jewish-label:after {
  content: "More";
  display: inline-block;
}
.read-more-jewish:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-jewish:checked + .read-more-content + .read-more-jewish-label:after {
  content: "Less";
}
</style>
