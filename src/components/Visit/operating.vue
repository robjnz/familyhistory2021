<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  The Old Operating Theatre </h1>
      <g-link href="https://bit.ly/3gj1G3V" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1590225123/operating_w3iaif.jpg"
          alt   = "The Old Operating Theatre"
      /></g-link>
      <p class="text-blue-200">
        9a St Thomas Street<br />Southwark London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3e98wr1"
          target = "_blank"
        >
          SE1 9RY
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
   Housed in the attic of the <br />early eighteenth-century church.......
<input id="read-more-operating-1" class="read-more-operating" type="checkbox">

  <div class="read-more-content">
<br />
   This atmospheric museum <br />offers a unique insight into<br /> the history of medicine and surgery.

</div>
<label class="read-more-operating-label postcode hover:text-white" for="read-more-operating-1">Read </label>
</article>

<br />
     <iframe class="h-32 w-full object-fill" title="video virtual tour of " src="" frameborder="0" allow="accelerometer; fullplay; encrypted-media; gyroscope; picture-in-picture" allowfullfull></iframe>

<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3gj1G3V"
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
.read-more-operating {
  display: none;
}
.read-more-operating-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-operating-label:after {
  content: "More";
  display: inline-block;
}
.read-more-operating:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-operating:checked + .read-more-content + .read-more-operating-label:after {
  content: "Less";
}
</style>
