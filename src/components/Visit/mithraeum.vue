<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> London Mithraeum</h1>
      <g-link href="https://bit.ly/2K51A14" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1586881665/mithraeus_hpngpn.jpg"
          alt   = "London Mithraeum"
      /></g-link>
      <p class="text-blue-200">
       12 Walbrook<br />London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3a4Vrg1"
          target = "_blank"
        >
          EC4N 8AA 
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
       <h2 class=" mb-4 text-base text-orange-300">
        
      
   
      Opening Times: <br />Tues To Sat<br />
      10.00am To 6.00pm  <br />
      Sun <br /> 12.00pm – 5.00pm<br />
      First Thursday of the month <br />10.00am – 8.00pm<br />
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
Ancient temple<br /> found during the recent excavations,.....
<input id="read-more-mithraeum-1" class="read-more-mithraeum" type="checkbox">

  <div class="read-more-content">
<br />
 a selection of the <br />remarkable Roman artefacts. 
 </div>
<label class="read-more-mithraeum-label postcode hover:text-white" for="read-more-mithraeum-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2K51A14"
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
.read-more-mithraeum {
  display: none;
}
.read-more-mithraeum-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-mithraeum-label:after {
  content: "More";
  display: inline-block;
}
.read-more-mithraeum:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-mithraeum:checked + .read-more-content + .read-more-mithraeum-label:after {
  content: "Less";
}
</style>
