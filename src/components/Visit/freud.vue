<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Freud Museum
</h1
      >
      <g-link href="https://bit.ly/3dqVsxw" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/freud.jpg"
          alt = " Freud Museum"
      /></g-link>
      <p class="text-blue-200">
        20 Maresfield Gardens<br />Hampstead London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2xvMdvn"
          target = "_blank"
        >
         NW3 5SX 
        </g-link>
      </p>
      
       <h2 class=" mb-4 text-2xl text-pink-300"></h2>
       <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £14.00 <br />Concession: £12.00 <br />Young Persons 12 – 16: £9.00<br />Children: Under 12 Free 
<br /><br />
   
      Opening Times: <br />
      Wed 10.30am To 5.00pm<br />
      Sat 10.30am to 5.00pm <br />
      Sun 10.30am To 5.00pm <br />
      Required To Book Online<br />

      

      </h2>


      <article class="text-blue-200">
 Discover the story<br /> of Phychoannalysis.....
  <input id="read-more-freud-1" class="read-more-freud" type="checkbox">
 
  <div class="read-more-content">
       and see Sigmund Freud iconic couch.
  </div>
  <label class="read-more-freud-label postcode hover:text-white" for="read-more-freud-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3dqVsxw"
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
.read-more-freud {
  display: none;
}
.read-more-freud-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-freud-label:after {
  content: "More";
  display: inline-block;
}
.read-more-freud:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-freud:checked + .read-more-content + .read-more-freud-label:after {
  content: "Less";
}
</style>
