<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Kenneth More Theatre</h1>
      <g-link href="http://bit.ly/39VrEaj" target="_blank"
        ><g-image
          src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594204063/kmt_ilford_nwn8mb.jpg"
          alt = "Kenneth More Theatre poster"
      /></g-link>

      <p class="text-blue-200">
        Oakfield Road<br />
        Ilford Essex

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2xHi1hb"
          target = "_blank"
        >
          IG1 1BT
        </g-link>
      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Wed 1 - Sun 5 April
      </p>

      <article class="text-blue-200">
        Bugsy Malone, Dandy Dan and the rest <br />of the gangsters.....
        <input
          id    = "read-more-ilford-1"
          class = "read-more-ilford"
          type  = "checkbox"
        />
        <div class="read-more-content">
          They take to the streets <br />with Splurge Guns and cream pies.
        </div>
        <label
          class = "read-more-ilford-label text-red-700 hover:text-white"
          for   = "read-more-ilford-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/39VrEaj"
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
.read-more-ilford {
  display: none;
}
.read-more-ilford-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : 0.5em;
  font-size  : 16px;
}
.read-more-ilford-label:after {
  content: "More";
  display: inline-block;
}
.read-more-ilford:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-ilford:checked + .read-more-content + .read-more-ilford-label:after {
  content: "Less";
}
</style>
