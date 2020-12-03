<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  HMS Belfast </h1>
      <g-link href="https://bit.ly/3eevH2X" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/hmsbelfast.jpg"
          alt   = "hms belfast"
      /></g-link>
      <p class="text-blue-200">
        The Queen's Walk<br />London





        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3cQpfPw"
          target = "_blank"
        >
          SE1 2JH
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
   HMS Belfast is the most <br />significant surviving.......
<input id="read-more-belfast-1" class="read-more-belfast" type="checkbox">

  <div class="read-more-content">
<br />
   Second World War Royal Navy warship.<br /> Since her launch over 82 years ago.

</div>
<label class="read-more-belfast-label postcode hover:text-white" for="read-more-belfast-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3eevH2X"
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
.read-more-belfast {
  display: none;
}
.read-more-belfast-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-belfast-label:after {
  content: "More";
  display: inline-block;
}
.read-more-belfast:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-belfast:checked + .read-more-content + .read-more-belfast-label:after {
  content: "Less";
}
</style>
