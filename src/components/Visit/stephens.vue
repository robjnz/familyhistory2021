<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Stephens House
</h1>
      <g-link href="https://bit.ly/2R0v5oP" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/stephans.jpg"
          alt = "Stephens House & Gardens"
      /></g-link>

      <p class="text-blue-200">
        17 East End Road<br /> London
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2WHAx3n"
          target = "_blank"
        >
           N3 3QE 
        </g-link>
      </p>
       <h2 class=" mb-4 text-2xl text-pink-300">Gardens Open</h2>
        <h2 class=" mb-4 text-base text-orange-300">
     Admission free<br />
     
     <br />
      Opening Times: Mon To Sun <br />8.00am To 6.00pm
<br />
       

     </h2>

      <article class="text-blue-200">
  Grade ll listed house <br /> & landscaped gardens......<br /> 
  <input id="read-more-stephens-1" class="read-more-stephens" type="checkbox">
  <div class="read-more-content">
        gifted for the use <br />and enjoyment of the people<br /> by Henry Charles 'Inky' Stephens<br /> of the Stephens' Ink Company.

  </div>
  <label class="read-more-stephens-label postcode hover:text-white" for="read-more-stephens-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2R0v5oP"
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
.read-more-stephens {
  display: none;
}
.read-more-stephens-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-stephens-label:after {
  content: "More";
  display: inline-block;
}
.read-more-stephens:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-stephens:checked + .read-more-content + .read-more-stephens-label:after {
  content: "Less";
}
</style>
