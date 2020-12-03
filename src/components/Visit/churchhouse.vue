<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
           <i class="fas fa-arrow-alt-circle-churchhouse"></i>
        </span> Church House Gardens</h1>
      <g-link href="https://bit.ly/3dYTjt6" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/churchhouse.jpg"
          alt = "church house gardens"
      /></g-link>
      <p class="text-blue-200">
        Lodge Church Road<br /> Bromley Kent

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3bQLSCp"
          target = "_blank"
        >
          BR2 0EG
        </g-link>
      </p>
      
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
  Ornamental gardens and<br /> sports fields...... 
  <input id="read-more-churchhouse-1" class="read-more-churchhouse" type="checkbox">
  <div class="read-more-content">
    a playground are the draw <br />at this quiet, lakefront park.

  </div>
  <label class="read-more-churchhouse-label postcode hover:text-white" for="read-more-churchhouse-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3dYTjt6"
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
.read-more-churchhouse {
  display: none;
}
.read-more-churchhouse-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-churchhouse-label:after {
  content: "More";
  display: inline-block;
}
.read-more-churchhouse:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-churchhouse:checked + .read-more-content + .read-more-churchhouse-label:after {
  content: "Less";
}
</style>
