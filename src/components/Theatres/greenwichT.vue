<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Greenwich Theatre</h1>
      <g-link href="http://bit.ly/2v7lp3D" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594203687/greenwich_theatre_uv7ons.jpg"
          alt   = "Greenwich Theatre Poster"
      /></g-link>

      <p class="text-blue-200">
        Crooms Hill<br />Greenwich London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/3aBsF7d"
          target = "_blank"
        >
         SE10 8ES
        </g-link>
      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        Sun 22 March 1pm & 3 pm
      </p>

      <article class="text-blue-200">
        The moonlight is beautiful, shining <br /> across the......
        <input
          id    = "read-more-greenwich-1"
          class = "read-more-greenwich"
          type  = "checkbox"
        />
        <div class="read-more-content ">
           bedroom floor as Poppy Diddle dozes off. <br />But is all as calm as it seems?<br /><br />
          Suddenly, Poppy wakes up to discover <br />that the MoonMoo<br /><br /> has got stuck
          on the Moon! <br />Poppy’s mission is clear!
        </div>
        <label
          class = "read-more-greenwich-label text-red-700 hover:text-white"
          for   = "read-more-greenwich-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2v7lp3D"
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
  transition: max-height 0.5s ease;
}
.read-more-greenwich {
  display: none;
}
.read-more-greenwich-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : 0.5em;
  font-size  : 16px;
}
.read-more-greenwich-label:after {
  content: "More";
  display: inline-block;
}
.read-more-greenwich:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-greenwich:checked + .read-more-content + .read-more-greenwich-label:after {
  content: "Less";
}
</style>
