<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">

    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Carlye House</h1>

      <g-link href="https://bit.ly/3aTRif7" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/v1588431500/carlyle_fkvpex.jpg"
          alt   = "carlye house"
      /></g-link>

      <p class="text-blue-200">
       24 Cheyne Row<br /> Chelsea London  



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/35rmBwA"
          target = "_blank"
        >
          SW3 5HL
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
The home of Thomas and <br />Jane Carlyle......
<input id="read-more-carlye-1" class="read-more-carlye" type="checkbox">

  <div class="read-more-content">
<br />
victorian writer and historian.

</div>
<label class="read-more-carlye-label postcode hover:text-white" for="read-more-carlye-1">Read </label>
</article>

<br />
     <iframe class="h-32 w-full object-fill" title="video virtual tour of " src="" frameborder="0" allow="accelerometer; fullplay; encrypted-media; gyroscope; picture-in-picture" allowfullfull></iframe>

<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3aTRif7"
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
.read-more-carlye {
  display: none;
}
.read-more-carlye-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-carlye-label:after {
  content: "More";
  display: inline-block;
}
.read-more-carlye:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-carlye:checked + .read-more-content + .read-more-carlye-label:after {
  content: "Less";
}
</style>
