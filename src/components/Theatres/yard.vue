<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> The Yard Theatre</h1>
      <g-link href="http://bit.ly/2OYFsdx" target="_blank"
        ><g-image
          src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594204577/yarn_theatre_w8tzao.jpg"
          alt = "The Yard Theatre poster"
      /></g-link>

      <p class="text-blue-200">
       White Post Lane<br />Hackney London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/33ktAGT"
          target = "_blank"
        >
          E9 5EN
        </g-link>
      </p>
      <h3 class="text-2xl text-pink-400">Closed</h3>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Thurs 2 April-->
      </p>
<!--
      <article class="text-blue-200">
         Man Up, Lipsync 1000 and <br />magnificent melange.....
        <input
          id    = "read-more-yard-1"
          class = "read-more-yard"
          type  = "checkbox"
        />
        <div class="read-more-content mt-2">
          The most exciting up and <br />coming performance makers <br />from the London scene.
        </div>
        <label
          class = "read-more-yard-label text-red-700 hover:text-white"
          for   = "read-more-yard-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2OYFsdx"
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
.read-more-yard {
  display: none;
}
.read-more-yard-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : 0.5em;
  font-size  : 16px;
}
.read-more-yard-label:after {
  content: "More";
  display: inline-block;
}
.read-more-yard:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-yard:checked + .read-more-content + .read-more-yard-label:after {
  content: "Less";
}
</style>
