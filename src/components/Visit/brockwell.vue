<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Brockwell Park</h1>
      <g-link href="https://bit.ly/35uUEnE" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1588606892/brockwell_eqfeyv.jpg"
          alt   = "brockwell park"
      /></g-link>
      <p class="text-blue-200">
        Brockwell Park Gardens<br />Brixton London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/35yWYtV"
          target = "_blank"
        >
          SE24 9BJ 
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
Historic park located between Brixton<br /> Dulwich and Herne Hill.......
<input id="read-more-brockwell-1" class="read-more-brockwell" type="checkbox">

  <div class="read-more-content">
<br />
 has ornamental ponds, formal flower beds,<br /> a walled 'Old English' <br />herbaceous flower garden<br /> and a 19th century clock tower.

</div>
<label class="read-more-brockwell-label postcode hover:text-white" for="read-more-brockwell-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/35uUEnE"
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
.read-more-brockwell {
  display: none;
}
.read-more-brockwell-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-brockwell-label:after {
  content: "More";
  display: inline-block;
}
.read-more-brockwell:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-brockwell:checked + .read-more-content + .read-more-brockwell-label:after {
  content: "Less";
}
</style>
