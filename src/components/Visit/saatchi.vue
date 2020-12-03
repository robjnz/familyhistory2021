<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Saatchi Gallery</h1>
      <g-link href="https://bit.ly/3cTg8xc" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/saatchi.jpg"
          alt   = " Saatchi Gallery"
      /></g-link>
      <p class="text-blue-200">
King's Road<br />Chelsea London



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3f0Y466"
          target = "_blank"
        >
          SW3 4RY
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Tickets: £3.00
      <br /><br />
   
      Opening Times: <br />Wed To Sun<br />
      10.00am To 6.00pm  <br />Required To Book Online<br />

      

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
 Contemporary art presenting<br /> work of young artists..... 
<input id="read-more-saatchi-1" class="read-more-saatchi" type="checkbox">

  <div class="read-more-content">
<br />
and international artists<br /> who have never <br />exhibited in the UK.
</div>
<label class="read-more-saatchi-label postcode hover:text-white" for="read-more-saatchi-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3cTg8xc"
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
.read-more-saatchi {
  display: none;
}
.read-more-saatchi-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-saatchi-label:after {
  content: "More";
  display: inline-block;
}
.read-more-saatchi:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-saatchi:checked + .read-more-content + .read-more-saatchi-label:after {
  content: "Less";
}
</style>
