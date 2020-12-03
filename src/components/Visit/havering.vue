<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Havering Country Park</h1>
      <g-link href="http://bit.ly/2vYTVxT" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/haveringpark.jpg"
          fluid-grow
          alt = "Havering Country Park"
      /></g-link>
      <p class="text-blue-200">
       Pinewood Road<br /> Havering-Atte-Bower Essex 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2Q6imjC"
          target = "_blank"
        >
          RM4 1PB
        </g-link>
      </p>
<h2 class=" mb-4 text-2xl text-pink-300"></h2>
      <article class="text-blue-200">
  Havering Country Park <br />is a varied environment....... 
  <input id="read-more-havering-1" class="read-more-havering" type="checkbox">
  <div class="read-more-content">
      <br />
 It includes 100 acres of woodland.
  </div>
  <label class="read-more-havering-label postcode hover:text-white" for="read-more-havering-1">Read </label>
</article>
     
      
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2vYTVxT"
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
.read-more-havering {
  display: none;
}
.read-more-havering-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-havering-label:after {
  content: "More";
  display: inline-block;
}
.read-more-havering:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-havering:checked + .read-more-content + .read-more-havering-label:after {
  content: "Less";
}
</style>

