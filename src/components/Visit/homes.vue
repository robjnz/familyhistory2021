<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Sherlock Holmes Museum </h1>
      <g-link href="https://bit.ly/2D9dxT0" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/homes.jpg"
          alt   = "Sherlock Holmes Museum"
      /></g-link>

      <p class="text-blue-200">
        221b Baker Street<br /> Marylebone London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/32YCLhU"
          target = "_blank"
        >
          NW1 6XE
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £15.00 <br />Children: £10.00 
<br /><br />
   
      Opening Times: <br />Wed To Thurs<br />
      11.00am To 3.00pm  <br /><br />
      Fri To Sun <br />
      11.00am To 5.00pm<br />
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
   The consulting rooms of <br />detective Sherlock Holmes........
<input id="read-more-homes-1" class="read-more-homes" type="checkbox">

  <div class="read-more-content">
<br />
Who lived at 221b Baker Street,<br /> between 1881-1904, <br />according to the stories<br /> written by Sir Arthur Conan Doyle.
</div>
<label class="read-more-homes-label postcode hover:text-white" for="read-more-homes-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2D9dxT0"
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
.read-more-homes {
  display: none;
}
.read-more-homes-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-homes-label:after {
  content: "More";
  display: inline-block;
}
.read-more-homes:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-homes:checked + .read-more-content + .read-more-homes-label:after {
  content: "Less";
}
</style>
