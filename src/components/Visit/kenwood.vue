<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> kenwood House</h1>
      <g-link href="https://bit.ly/2yrob5n" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,/v1587464118/kenwood_ow0mh6.jpg"
          alt   = "kenwood House"
      /></g-link>
      <p class="text-blue-200">
     Hampstead Lane<br />Hampstead London


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3abNWnh"
          target = "_blank"
        >
          NW3 7JR
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300">Gardens Open</h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
     
      Gardens Are Free To Visit<br /><br />
      Opening Times: Mon To Sun <br />8.00am To 7:30pm

      

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
 Kenwood is one of London's hidden <br />gems, with breathtaking interiors.......
<input id="read-more-kenwood-1" class="read-more-kenwood" type="checkbox">

  <div class="read-more-content">
<br />
  stunning art collection, including <br />Rembrandt's 'Portrait with Two Circles'.
 </div>
<label class="read-more-kenwood-label postcode hover:text-white" for="read-more-kenwood-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2yrob5n"
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
.read-more-kenwood {
  display: none;
}
.read-more-kenwood-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-kenwood-label:after {
  content: "More";
  display: inline-block;
}
.read-more-kenwood:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-kenwood:checked + .read-more-content + .read-more-kenwood-label:after {
  content: "Less";
}
</style>
