<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
           <i class="fas fa-arrow-alt-circle-minster"></i>
        </span> Croydon Minster</h1>
      <g-link href="https://bit.ly/3aKv2VT" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/minster.jpg"
          fluid-grow
          alt = "Croydon Minster"
      /></g-link>
      <p class="text-blue-200">
        Church Street<br />  Croydon Surrey

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/34b85bS"
          target = "_blank"
        >
          CR0 1RN
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300">Open</h2>
      <h2 class=" mb-4 text-lg text-pink-300">personal prayer and devotion </h2>

      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
  Croydon Minster has a long <br />and distinguished history....... 
  <input id="read-more-minster-1" class="read-more-minster" type="checkbox">
  <div class="read-more-content">
 It is believed to have been founded<br /> in Saxon times. There <br /> is a record of a<br /> priest of Croydon in 960. <br />The first record of<br /> a church building<br /> is in Domesday Book of 1086. 
  </div>
  <label class="read-more-minster-label postcode hover:text-white" for="read-more-minster-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3aKv2VT"
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
.read-more-minster {
  display: none;
}
.read-more-minster-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-minster-label:after {
  content: "More";
  display: inline-block;
}
.read-more-minster:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-minster:checked + .read-more-content + .read-more-minster-label:after {
  content: "Less";
}
</style>
