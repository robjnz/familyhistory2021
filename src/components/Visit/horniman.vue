<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Horniman Museum</h1>
      <g-link href="http://bit.ly/2ykLEm0" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/horniman.jpg"
          fluid-grow
          alt = "Horniman Museam & Park"
      /></g-link>
      <p class="text-blue-200">
        100 London Road<br />Forest Hill London

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2TJinfz"
          target = "_blank"
        >
          SE23 3PQ
        </g-link>
      </p>

            <h2 class=" mb-4 text-2xl text-pink-300"></h2>
 <h2 class=" mb-4 text-base text-orange-300">
        
    Admission free<br /><br />
      Opening Times: <br />Mon To Sun<br />
      10.00am To 5.30pm  <br />Required To Book Online<br />
      </h2>

       <article class="text-blue-200">
   The Horniman connects <br />us all with global cultures........
<input id="read-more-horniman-1" class="read-more-horniman" type="checkbox">

  <div class="read-more-content">
<br />
    The natural environment, <br />encouraging us to shape <br />a positive future for <br />the world we all share

</div>
<label class="read-more-horniman-label postcode hover:text-white" for="read-more-horniman-1">Read </label>
</article>

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2ykLEm0"
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
.read-more-horniman {
  display: none;
}
.read-more-horniman-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-horniman-label:after {
  content: "More";
  display: inline-block;
}
.read-more-horniman:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-horniman:checked + .read-more-content + .read-more-horniman-label:after {
  content: "Less";
}
</style>

