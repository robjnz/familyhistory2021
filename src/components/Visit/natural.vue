<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Natural History Museum</h1>
      <g-link href="https://bit.ly/353O5s9" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/natural.jpg"
          alt   = " Natural History Museum"
      /></g-link>
      <p class="text-blue-200">
     
      Cromwell Road<br />Kensington London

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3eITo4C"
          target = "_blank"
        >
          SW7 5BD
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
       <h2 class=" mb-4 text-base text-orange-300">
        
     Admission free<br /><br />
   
      Opening Times: <br />Wed To Sun<br />
      11.00am To 6.00pm  <br />Required To Book Online<br />

      

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
The Museum is a world-class <br />as a science research centre.......
<input id="read-more-natural-1" class="read-more-natural" type="checkbox">

  <div class="read-more-content">
<br />
Housing over 80 million specimens<br /> spanning billions of years.
</div>
<label class="read-more-natural-label postcode hover:text-white" for="read-more-natural-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/353O5s9"
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
.read-more-natural {
  display: none;
}
.read-more-natural-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-natural-label:after {
  content: "More";
  display: inline-block;
}
.read-more-natural:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-natural:checked + .read-more-content + .read-more-natural-label:after {
  content: "Less";
}
</style>
