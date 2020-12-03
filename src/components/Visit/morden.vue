<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Morden Hall Park</h1>
      <g-link href="https://bit.ly/3dZuw8p" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/mordon.jpg"
          fluid-grow
          alt = "Morden Hall Park"
      /></g-link>

      <p class="text-blue-200">
       Morden Hall Road<br /> Morden London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2yz0WGu"
          target = "_blank"
        >
          SM4 5JD
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
    A green oasis in the city<br />giving you a taste ..... 
  <input id="read-more-morden-1" class="read-more-morden" type="checkbox">
  <div class="read-more-content">
   of a country estate <br />with a glimpse of its<br /> agricultural and industrial history.
  </div>
  <label class="read-more-morden-label postcode hover:text-white" for="read-more-morden-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3dZuw8p"
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
.read-more-morden {
  display: none;
}
.read-more-morden-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-morden-label:after {
  content: "More";
  display: inline-block;
}
.read-more-morden:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-morden:checked + .read-more-content + .read-more-morden-label:after {
  content: "Less";
}
</style>
