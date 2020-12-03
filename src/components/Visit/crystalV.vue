<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
           <i class="fas fa-arrow-alt-circle-crystalV"></i>
        </span> Crystal Palace Park</h1>
      <g-link href="https://bit.ly/2UGgiSc" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/crystal.jpg"
          alt = "Crystal Palace Park"
      /></g-link>
      <p class="text-blue-200">
        Thicket Road<br />London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2UIr8Y4"
          target = "_blank"
        >
          SE19 2GA
        </g-link>
      </p>
      
      <!--<h2 class=" mb-4 text-2xl text-pink-300">Closed</h2>-->
      <br />
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
  South London park with<br /> full-size model dinosaurs..... 
  <input id="read-more-crystalV-1" class="read-more-crystalV" type="checkbox">
  <div class="read-more-content">
        an outdoor concert stage,<br />  a maze children's farm<br /> and playground.<br /> including a lake which<br /> is valuable for water birds. 

  </div>
  <label class="read-more-crystalV-label postcode hover:text-white" for="read-more-crystalV-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2UGgiSc"
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
.read-more-crystalV {
  display: none;
}
.read-more-crystalV-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-crystalV-label:after {
  content: "More";
  display: inline-block;
}
.read-more-crystalV:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-crystalV:checked + .read-more-content + .read-more-crystalV-label:after {
  content: "Less";
}
</style>
