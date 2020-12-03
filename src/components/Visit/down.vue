<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Down House</h1>
      <g-link href="https://bit.ly/2RaujVY" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/down.jpg"
          alt = "Down House"
      /></g-link>
      <p class="text-blue-200">
        Luxted Road Downe Orpington<br /> Bromley Kent

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2xKagam"
          target = "_blank"
        >
          BR6 7JT
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
       <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £14.50 <br />Concession £13.10 <br />Children: £8.70 
<br />Family: £37.70<br /><br />
   
      Opening Times: <br />Mon To Sun<br />
      10.00am To 5.00pm  <br />Required To Book Online<br />

      

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
    Charles Darwin home..... 
  <input id="read-more-down-1" class="read-more-down" type="checkbox">
  <div class="read-more-content">
         See the study where<br /> Darwin wrote 'On the Origin of Species'<br  /> and stroll through the gardens<br /> that inspired him.

  </div>
  <label class="read-more-down-label postcode hover:text-white" for="read-more-down-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2RaujVY"
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
.read-more-down {
  display: none;
}
.read-more-down-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-down-label:after {
  content: "More";
  display: inline-block;
}
.read-more-down:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-down:checked + .read-more-content + .read-more-down-label:after {
  content: "Less";
}
</style>
