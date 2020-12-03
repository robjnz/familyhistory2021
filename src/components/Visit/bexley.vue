<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Bexley Park Wood</h1>
      <g-link href="http://bit.ly/2E7182l" target="_blank"
        ><g-image class="h-32 w-full object-fill"
          src = "@/images/visit/bexleywoods.jpg"
          fluid-grow
          alt = "Bexley Park Wood"
      /></g-link>
      <p class="text-blue-200">
        Brigden Road <br />Bexley London

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/39yBiiQ"
          target = "_blank"
        >
          DA5 3PT
        </g-link>
        
      </p>


       <h2 class=" mb-4 text-2xl text-pink-300"></h2>
      <article class="text-blue-200">
   An ancient Hornbeam woods<br /> west of Bexley....... 
  <input id="read-more-bexley-1" class="read-more-bexley" type="checkbox">
  <div class="read-more-content">
      <br />
 village Site of Importance <br />for Nature Conservation.
  </div>
  <label class="read-more-bexley-label postcode hover:text-white" for="read-more-bexley-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2E7182l"
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
.read-more-bexley {
  display: none;
}
.read-more-bexley-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-bexley-label:after {
  content: "More";
  display: inline-block;
}
.read-more-bexley:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-bexley:checked + .read-more-content + .read-more-bexley-label:after {
  content: "Less";
}
</style>

