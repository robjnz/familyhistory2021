<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <!--pick -->
       <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of <br />places to visit in London is:
          
          </h1>
  <!--end-->
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> British Museum</h1>
      <g-link href="https://bit.ly/2KckjaU" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1587052674/british_vexfwb.jpg"
          alt   = "British Museum"
      /></g-link>
      <p class="text-blue-200">
      Great Russell Street<br />London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2K8ALZI"
          target = "_blank" aria-label="open new window"
        >
          WC1B 3DG
        </g-link>
      </p>
      
           <h2 class=" mb-4 text-base text-orange-300">
        
     Admission free<br /><br />
   
      Opening Times: <br />Wednesday To Sunday<br />
      10.00am – 5.00pm
      <br />
      Required To Book Online<br />

      

      </h2>
      <h2 class="text-2xl event"> Events:</h2>
      <h2 class="text-2xl event">Tantra Enlightenment <br />To revolution</h2>


      <p class="event">

         <g-link href="https://bit.ly/2G97AHd" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1600925729/tantra_bxmva7.jpg"
          alt   = "Tantra Enlightenment poster"
      /></g-link>
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thursday 24 Sept 2020
        <br />to  <span><br />
          <i class="far fa-calendar-alt"></i>
        </span> Sunday 24 Jan 2021
      <br /><br />
      Tantra Enlightenment To Revolution<br />
      Explore the radical force that <br />transformed the religious,<br /> cultural and political landscape of India.

      </p>
      <br />
      <iframe class="h-32 w-full object-fill" title="video virtual tour of the The British Museum Tantra Enlightenment To Revolution 2.20 minute long" src="https://www.youtube.com/embed/iMxzzuR9ZZ0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
      <article class="text-blue-200">
The British Museum was founded in 1753<br /> opened its doors in 1759.......
<input id="read-more-british-1" class="read-more-british" type="checkbox">

  <div class="read-more-content">
<br />
 It was the first national museum <br />to cover all fields of human knowledge.
 </div>
<label class="read-more-british-label postcode hover:text-white" for="read-more-british-1">Read </label>
</article>

<br />
      <iframe class="h-32 w-full object-fill" title="video virtual tour of the The British Museum 1.13 minute long" src="https://www.youtube.com/embed/kMQgBAaUNs4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2KckjaU"
        target = "_blank" aria-label="open new window"
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
.read-more-british {
  display: none;
}
.read-more-british-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-british-label:after {
  content: "More";
  display: inline-block;
}
.read-more-british:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-british:checked + .read-more-content + .read-more-british-label:after {
  content: "Less";
}
</style>
