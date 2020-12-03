<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  London Transport Museum </h1>
      <g-link href="https://bit.ly/3i9rRu3" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/transport.jpg"
          alt   = "London Transport Museum"
      /></g-link>
      <p class="text-blue-200">
        Covent Garden Piazza <br />London




        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/30zw9Fn"
          target = "_blank"
        >
          WC2E 7BB 
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £15.00 <br />Children: £7.50 
      <br /><br />
   
      Opening Times: <br />Wed & Sun<br />
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
   Explore the story of London's <br />transport system.......
<input id="read-more-transport-1" class="read-more-transport" type="checkbox">

  <div class="read-more-content">
<br />
   Over the last 200 years.

</div>
<label class="read-more-transport-label postcode hover:text-white" for="read-more-transport-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3i9rRu3"
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
.read-more-transport {
  display: none;
}
.read-more-transport-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-transport-label:after {
  content: "More";
  display: inline-block;
}
.read-more-transport:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-transport:checked + .read-more-content + .read-more-transport-label:after {
  content: "Less";
}
</style>
