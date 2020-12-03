<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Hackney Empire</h1>
      <g-link href="http://bit.ly/2JnhX7Z" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594203822/hackney_empire_dol68i.jpg"
          alt   = "Hackney Empire Poster"
      /></g-link>

      <p class="text-blue-200">
        291 Mare Street<br />Hackney London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2w0dgPr"
          target = "_blank"
        >
        E8 1EJ 
        </g-link>
      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Sun 22 March 7.30pm
      </p>

      <article class="text-blue-200">
Once again we fuse together the best<br /> in musical talent.....<input
          id    = "read-more-hackney-1"
          class = "read-more-hackney"
          type  = "checkbox"
        />
        <div class="read-more-content ">
             with the UK’s finest comedians <br />to give you an action packed<br /> non stop night of entertainment.
        </div>
        <label
          class = "read-more-hackney-label text-red-700 hover:text-white"
          for   = "read-more-hackney-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2JnhX7Z"
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
.read-more-hackney {
  display: none;
}
.read-more-hackney-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-hackney-label:after {
  content: "More";
  display: inline-block;
}
.read-more-hackney:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-hackney:checked + .read-more-content + .read-more-hackney-label:after {
  content: "Less";
}
</style>