<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
          <i class="fas fa-theater-masks"></i>
        </span> Wilton's Music Hall</h1>
      <g-link href="http://bit.ly/2R9bBf7" target="_blank"
        ><g-image
         
          src = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1594204774/wiltons_tqat0q.jpg"
          alt = "Wilton's Music Hall Poster"
      /></g-link>

      <p class="text-blue-200">
        1 Graces Alley<br />Whitechapel London

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/39UczFL"
          target = "_blank"
        >
         E1 8JB
        </g-link>
      </p>
      <h3 class="text-2xl text-red-400">Closed</h3>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--Wed 25 March - Wed 1 April-->
      </p>
<!--
      <article class="text-blue-200">
       Turn of the Screw is a curious story<br /> Set in an old English country house.....
        <input
          id    = "read-more-wilton-1"
          class = "read-more-wilton"
          type  = "checkbox"
        />
        <div class="read-more-content mt-2 ">
         The housekeeper and two young <br />orphaned children welcome <br />an eager new governess.<br /> <br />When she arrives from London<br /> to look after them <br />a ghostly tale unfolds.  
        </div>
        <label
          class = "read-more-wilton-label text-red-700 hover:text-white"
          for   = "read-more-wilton-1"
          >Read
        </label>
      </article>
-->
      <br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2R9bBf7"
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
.read-more-wilton {
  display: none;
}
.read-more-wilton-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : 0.5em;
  font-size  : 16px;
}
.read-more-wilton-label:after {
  content: "More";
  display: inline-block;
}
.read-more-wilton:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-wilton:checked + .read-more-content + .read-more-wilton-label:after {
  content: "Less";
}
</style>
