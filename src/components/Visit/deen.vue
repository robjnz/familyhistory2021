<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Deen City Farm </h1>
      <g-link href="https://bit.ly/2V7oB8O" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/deen.jpg"
          alt = "Deen City Farm"
      /></g-link>
      <p class="text-blue-200">
       39 Windsor Avenue Merton Abbey<br />Merton London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/34h2FbL"
          target = "_blank"
        >
          SW19 2RR
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
    Educational petting farm <br />with cattle and rare..... 
  <input id="read-more-deen-1" class="read-more-deen" type="checkbox">
  <div class="read-more-content">

        British animal breeds.<br /> A riding school and a cafe. 

  </div>
 <label class="read-more-deen-label postcode hover:text-white" for="read-more-deen-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2V7oB8O"
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
.read-more-deen {
  display: none;
}
.read-more-deen-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-deen-label:after {
  content: "More";
  display: inline-block;
}
.read-more-deen:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-deen:checked + .read-more-content + .read-more-deen-label:after {
  content: "Less";
}
</style>
