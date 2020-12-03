<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Hall Place & Gardens</h1>
      <g-link href="http://bit.ly/2QyDQ6A" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/hallplace.jpg"
          fluid-grow
          alt = "Hall Place & Gardens"
      /></g-link>
      <p class="text-blue-200">
        Bourne Road<br />
        Bexley Kent

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2ve9T6S"
          target = "_blank"
        >
          DA5 1PQ
        </g-link>
      </p>

     <h2 class="text-2xl text-pink-300">Gardens Open</h2>
     <h2 class=" mb-4 text-base text-orange-300">
        <br />
      Adults: £8.00 <br />Concession £7.00 <br />Children: £4.00<br /> Family: £20.00 
<br />
      Gardens Are Free To Visit<br /><br />
      Opening Times: Mon To Sun <br />9am To 9:30pm

      

      </h2>
<!--
     <br />
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>

      </p>
-->
<br />
       <article class="text-blue-200">

          Hall Place is a Grade I listed<br /> country house built in 1537...... 
<input id="read-more-hall-1" class="read-more-hall" type="checkbox">
  <div class="read-more-content">
<br />
The Secret Wartime History <br />of Hall Place explores<br /> how American soldiers stationed <br />at Hall Place – code name Santa Fe –<br /> intercepted encoded messages <br />sent by the Germans.
  </div>
<label class="read-more-hall-label postcode hover:text-white" for="read-more-hall-1">Read </label>
</article>

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2QyDQ6A"
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
.read-more-hall {
  display: none;
}
.read-more-hall-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-hall-label:after {
  content: "More";
  display: inline-block;
}
.read-more-hall:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-hall:checked + .read-more-content + .read-more-hall-label:after {
  content: "Less";
}
</style>
