<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Wellcome Collection </h1>
      <g-link href="https://bit.ly/2OZhpce" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1595760554/wellcome_vkh03r.jpg"
          alt   = "Wellcome Collection"
      /></g-link>
      <p class="text-blue-200">
        183 Euston Road<br /> London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2WYzLOS"
          target = "_blank"
        >
          NW1 2BE 
        </g-link>
      </p>
      
        <h2 class=" mb-4 text-base text-orange-300">
        
      Admission free
<br /><br />
   
      Opening Times: <br />Mon To Sun<br />
      

      

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
   Wellcome Collection <br />museum and library.........
<input id="read-more-wellcome-1" class="read-more-wellcome" type="checkbox">

  <div class="read-more-content">
<br />
 Aims to challenge <br />how we all think <br />and feel about health.
</div>
<label class="read-more-wellcome-label postcode hover:text-white" for="read-more-wellcome-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2OZhpce"
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
.read-more-wellcome {
  display: none;
}
.read-more-wellcome-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-wellcome-label:after {
  content: "More";
  display: inline-block;
}
.read-more-wellcome:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-wellcome:checked + .read-more-content + .read-more-wellcome-label:after {
  content: "Less";
}
</style>
