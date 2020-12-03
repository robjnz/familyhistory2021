<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Clarence House</h1>
      <g-link href="https://bit.ly/30h8lGd" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/clarence.jpg"
          alt   = "Clarence House"
      /></g-link>
      <p class="text-blue-200">
      St. James's<br />London




        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3762VPZ"
          target = "_blank"
        >
         SW1A 1BA
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300">Reopens August 2021</h2>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
    Official residence of The Prince of Wales<br /> and The Duchess of Cornwall.......
<input id="read-more-clarence-1" class="read-more-clarence" type="checkbox">

  <div class="read-more-content">
<br />
Built by John Nash in 1825-27 <br />for George III’s third son.
</div>
<label class="read-more-clarence-label postcode hover:text-white" for="read-more-clarence-1">Read </label>
</article>

        <iframe class="h-32 w-full object-fill" aria-label="youtube-video" title="video of Clarence House 4.37 minutes" src="https://www.youtube.com/embed/6TfKtSSmv8Q" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/30h8lGd"
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
.read-more-clarence {
  display: none;
}
.read-more-clarence-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-clarence-label:after {
  content: "More";
  display: inline-block;
}
.read-more-clarence:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-clarence:checked + .read-more-content + .read-more-clarence-label:after {
  content: "Less";
}
</style>
