<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Buckingham Palace</h1>
      <g-link href="https://bit.ly/3eZ8nXv" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_200,w_300/v1591526855/gallery_uog4fg.jpg"
          alt   = "buckingham palace"
      /></g-link>
      <p class="text-blue-200">
Westminster <br />London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3dSI3OR"
          target = "_blank"
        >
         SW1A 1AA
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
    The Queens gallery<br />is open to the public........
<input id="read-more-gallery-1" class="read-more-gallery" type="checkbox">

  <div class="read-more-content">
<br />
The Royal Collection, featuring <br />old master paintings, <br />rare furniture, <br />decorative arts and <br />images from the <br />vast photograph collection.
</div>
<label class="read-more-gallery-label postcode hover:text-white" for="read-more-gallery-1">Read </label>
</article>

<br />
      <iframe class="h-32 w-full object-fill" title="video The queen's gallery Buckingham Palace 7.07 minute long" src="https://www.youtube.com/embed/-wqtvxIVyMs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3eZ8nXv"
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
.read-more-gallery {
  display: none;
}
.read-more-gallery-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-gallery-label:after {
  content: "More";
  display: inline-block;
}
.read-more-gallery:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-gallery:checked + .read-more-content + .read-more-gallery-label:after {
  content: "Less";
}
</style>
