<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Stratford East</h1>
      <g-link href="http://bit.ly/2JjU3Kr" target="_blank"
        ><g-image
          src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594204283/stratford_east_u1hkxu.jpg"
          alt = "Theatre Royal Stratford East Poster"
      /></g-link>

      <p class="text-blue-200">
        Gerry Raffles Square <br />Stratford London
        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/38WkDo6"
          target = "_blank"
        >
          E15 1BN
        </g-link>
      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       <!-- Tues 24 - Fri 27 March 7 pm-->
      </p>
<!--
      <article class="text-blue-200">
        The National Theatre Connections<br /> festival is a celebration.....
        
        <input
          id    = "read-more-stratford-1"
          class = "read-more-stratford"
          type  = "checkbox"
        />
        <div class="read-more-content ">
           of young people theatre-making
        </div>
        <label
          class = "read-more-stratford-label text-red-700 hover:text-white"
          for   = "read-more-stratford-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2JjU3Kr"
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
.read-more-stratford {
  display: none;
}
.read-more-stratford-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : 0.5em;
  font-size  : 16px;
}
.read-more-stratford-label:after {
  content: "More";
  display: inline-block;
}
.read-more-stratford:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-stratford:checked + .read-more-content + .read-more-stratford-label:after {
  content: "Less";
}
</style>
