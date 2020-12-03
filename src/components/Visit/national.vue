<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  The National Gallery</h1>
      <g-link href="https://bit.ly/3eFkpoT" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1591109173/national_nxwlnj.jpg"
          alt   = "the national gallery"
      /></g-link>
      <p class="text-blue-200">
        Trafalgar Square<br /> London



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3gNVeSY"
          target = "_blank"
        >
          WC2N 5DN
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
       <h2 class=" mb-4 text-base text-orange-300">
        <br />
      Admission free<br />
      Required To Book Online
<br /><br />
   
      Opening Times: <br />Mon To Sun<br />
      11am to 4pm<br />
      Friday closes 9pm<br />
      

      </h2>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thursday 9 July 2020 4:00pm<br />
      Bellini’s The Assassination of <br />Saint Peter Martyr
      </p>
      -->
 <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2ZGgGSf"
        target = "_blank"
      >
        Book Online For Free Tickets
      </g-link>
      <br /><br />

      <article class="text-blue-200">
   Houses over 2,600 paintings........
<input id="read-more-national-1" class="read-more-national" type="checkbox">

  <div class="read-more-content">
<br />
 ....
</div>
<label class="read-more-national-label postcode hover:text-white" for="read-more-national-1">Read </label>
</article>


<br />
     <iframe class="h-32 w-full object-fill" title="video virtual tour of " src="" frameborder="0" allow="accelerometer; fullplay; encrypted-media; gyroscope; picture-in-picture" allowfullfull></iframe>

<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3eFkpoT"
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
.read-more-national {
  display: none;
}
.read-more-national-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-national-label:after {
  content: "More";
  display: inline-block;
}
.read-more-national:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-national:checked + .read-more-content + .read-more-national-label:after {
  content: "Less";
}
</style>
