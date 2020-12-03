<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Queen's Theatre</h1>
      <g-link href="http://bit.ly/2Soh3MB" target="_blank"
        ><g-image
          src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594204179/queens_hornchurch_fkwwei.jpg"
          alt = "Queen's Theatre Hornchurch poster"
      /></g-link>

      <p class="text-blue-200">
        Billet Lane<br />
        Hornchurch Essex
        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/38TuPOf"
          target = "_blank"
        >
          RM11 1QT
        </g-link>
      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
      <!--  Fri 13 – Sat 28 March-->
      </p>
<!--
      <article class="text-blue-200">
        Maggie and Gordon first met in 1971 <br />dancing to the sound of Rod
        Stewart.....<input
          id    = "read-more-hornchurch-1"
          class = "read-more-hornchurch"
          type  = "checkbox"
        />
        <div class="read-more-content">
          <br />Maggie is feeling foggy <br />and can’t always find the
          words.<br /><br />
          Her son and new girlfriend <br />are coming to dinner and her
          <br />best friend is asking questions.<br /><br />
          Perhaps it’s time everyone learned<br />
          a bit more about some family secrets?
        </div>
        <label
          class = "read-more-hornchurch-label text-red-700 hover:text-white"
          for   = "read-more-hornchurch-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2Soh3MB"
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
.read-more-hornchurch {
  display: none;
}
.read-more-hornchurch-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : 0.5em;
  font-size  : 16px;
}
.read-more-hornchurch-label:after {
  content: "More";
  display: inline-block;
}
.read-more-hornchurch:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-hornchurch:checked + .read-more-content + .read-more-hornchurch-label:after {
  content: "Less";
}
</style>
