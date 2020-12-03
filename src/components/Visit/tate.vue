<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Tate Modern</h1>
      <g-link href="https://bit.ly/2Xg61wi" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/tate.jpg"
          alt   = "Tate Modern"
      /></g-link>
      <p class="text-blue-200">
        Bankside<br /> Soutwark London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3bPDgf1"
          target = "_blank"
        >
           SE1 9TG
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
         <h2 class=" mb-4 text-base text-orange-300">
     
      Admission free<br />
      Required To Book Online
<br />
         </h2>
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
 British art from the <br />16th century.......
<input id="read-more-tate-1" class="read-more-tate" type="checkbox">

  <div class="read-more-content">
<br />
  to the present day<br /> and of international modern<br /> and contemporary art.

</div>
<label class="read-more-tate-label postcode hover:text-white" for="read-more-tate-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2Xg61wi"
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
.read-more-tate {
  display: none;
}
.read-more-tate-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-tate-label:after {
  content: "More";
  display: inline-block;
}
.read-more-tate:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-tate:checked + .read-more-content + .read-more-tate-label:after {
  content: "Less";
}
</style>
