<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Keats House</h1>
      <g-link href="https://bit.ly/2Pjs2Xw" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/keats.jpg"
          alt   = "keats house"
      /></g-link>
      <p class="text-blue-200">
     10 Keats Grove<br />Hampstead London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2x4cOzV"
          target = "_blank"
        >
          NW3 2RR
        </g-link>
      </p>
      
      
       <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £7.50 <br />Concession £4.50 <br />Children: Free 
<br /><br />
   
      Opening Times: <br />Mon To Sun<br />
      11.00am To 4.30pm  <br />Required To Book Online<br />

      

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
 Home of John Keats the poet <br />1818 to 1820...... 
<input id="read-more-keats-1" class="read-more-keats" type="checkbox">

  <div class="read-more-content">
<br />
Built in 1815 and originally<br /> named Wentworth Place.

 </div>
<label class="read-more-keats-label postcode hover:text-white" for="read-more-keats-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2Pjs2Xw"
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
.read-more-keats {
  display: none;
}
.read-more-keats-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-keats-label:after {
  content: "More";
  display: inline-block;
}
.read-more-keats:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-keats:checked + .read-more-content + .read-more-keats-label:after {
  content: "Less";
}
</style>
