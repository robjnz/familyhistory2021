<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Museum Of London</h1>
      <g-link href="https://bit.ly/2yaS7mj" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/museumlondon.jpg"
          alt   = "museum of london"
      /></g-link>
      <p class="text-blue-200">
       150 London Wall<br /> London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3acQbGV"
          target = "_blank"
        >
          EC2Y 5HN
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
     Admission free<br /><br />
   
      Opening Times: <br />Mon To Fri<br />
      11.30am To 3.30pm  <br /><br />
      
       Sat To Sun <br />
       10.00am To 6.00pm<br /><br />
      Required To Book Online<br />

      

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
The Museum of London <br />tells the story.....
<input id="read-more-museumlondon-1" class="read-more-museumlondon" type="checkbox">

  <div class="read-more-content">
<br />
 of the capital from its <br />first settlers to modern times. 
 </div>
<label class="read-more-museumlondon-label postcode hover:text-white" for="read-more-museumlondon-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2yaS7mj"
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
.read-more-museumlondon {
  display: none;
}
.read-more-museumlondon-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-museumlondon-label:after {
  content: "More";
  display: inline-block;
}
.read-more-museumlondon:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-museumlondon:checked + .read-more-content + .read-more-museumlondon-label:after {
  content: "Less";
}
</style>
