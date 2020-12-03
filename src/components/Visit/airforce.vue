<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"
        ><span class="text-pink-300">
          <i class="fas fa-landmark"></i>
        </span>
        Royal Air Force Museum
</h1
      >
      <g-link href="https://bit.ly/3broAmB" target="_blank"
        ><g-image 
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/airforce.jpg"
          alt = "Royal Air Force Museum"
      /></g-link>
      <p class="text-blue-200">
        Grahame Park Way<br /> Hendon London 
        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2WKtOpo"
          target = "_blank"
        >
           NW9 5LL
        </g-link>
      </p>
      
       <h2 class=" mb-4 text-base text-orange-300">
     Admission free<br />
     
     <br />
      Opening Times: Mon To Sun <br />10.00am To 5.00pm
<br />Required To Book Online
       

     </h2>
      <article class="text-blue-200">
  Celebrates and commemorates<br /> the Royal Air Force 
....... 
  <input id="read-more-airforce-1" class="read-more-airforce" type="checkbox">
  <div class="read-more-content">
      <br />
The new innovative galleries<br /> explore the first 100 years<br /> of the RAF & its role today.

  </div>
  <label class="read-more-airforce-label postcode hover:text-white" for="read-more-airforce-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3broAmB"
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
.read-more-airforce {
  display: none;
}
.read-more-airforce-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-airforce-label:after {
  content: "More";
  display: inline-block;
}
.read-more-airforce:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-airforce:checked + .read-more-content + .read-more-airforce-label:after {
  content: "Less";
}
</style>
