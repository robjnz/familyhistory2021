<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Serpentine Galleries</h1>
      <g-link href="https://bit.ly/3f7XFyH" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/serpentine.jpg"
          alt   = " Serpentine Galleries"
      /></g-link>
      <p class="text-blue-200">
     
     Kensington Gardens<br /> London


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2KIY4K4"
          target = "_blank"
        >
          W2 3XA
        </g-link>
      </p>
            <h2 class=" mb-4 text-2xl text-pink-300"></h2>

        <h2 class=" mb-4 text-base text-orange-300">
      
  
      Admission free<br /><br />

      Opening Times: <br />Tues To Sun<br />
      10.00am to 6.00pm<br />
      Required To Book Online
<br />
         </h2>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
 The serpentine Galleries is<br />championing new ideas .....
<input id="read-more-serpentine-1" class="read-more-serpentine" type="checkbox">

  <div class="read-more-content">
<br />
 in contemporary art.<br />
ecology, climate emergency,<br />and the impact of <br />digital and new technologies. 
</div>
<label class="read-more-serpentine-label postcode hover:text-white" for="read-more-serpentine-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3f7XFyH"
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
.read-more-serpentine {
  display: none;
}
.read-more-serpentine-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-serpentine-label:after {
  content: "More";
  display: inline-block;
}
.read-more-serpentine:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-serpentine:checked + .read-more-content + .read-more-serpentine-label:after {
  content: "Less";
}
</style>
