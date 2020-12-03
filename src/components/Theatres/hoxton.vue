<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Hoxton Hall</h1>
      <g-link href="http://bit.ly/2EX7IsG" target="_blank"
        ><g-image
          src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594203918/hockton_hall_cjieoo.jpg"
          alt = "hoxton hall poster"
      /></g-link>

      <p class="text-blue-200">
        130 Hoxton Street<br />Hoxton London

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/3d6cLnE"
          target = "_blank"
        >
          N1 6SH
        </g-link>
      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        Sat 21 March 7.30 pm
      </p>

      <article class="text-blue-200">
        The Swing Time Dance Company <br />return to Hoxton Hall.....
        <input
          id    = "read-more-hoxton-1"
          class = "read-more-hoxton"
          type  = "checkbox"
        />
        <div class="read-more-content">
          DJ Andrew Willis Davenport will be<br />spinning music throughout the
          evening <br />that is guaranteed to get you moving. <br />Specializing
          in the Lindy Hop and the <br />American Jitterbug, Swing Time
          <br /><br />The Dance Company offer you <br />a fantastic opportunity to learn
          <br />at your own pace.
        </div>
        <label
          class = "read-more-hoxton-label text-red-700 hover:text-white"
          for   = "read-more-hoxton-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2EX7IsG"
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
.read-more-hoxton {
  display: none;
}
.read-more-hoxton-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : 0.5em;
  font-size  : 16px;
}
.read-more-hoxton-label:after {
  content: "More";
  display: inline-block;
}
.read-more-hoxton:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-hoxton:checked + .read-more-content + .read-more-hoxton-label:after {
  content: "Less";
}
</style>
