<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> St. Paul's Cathedral</h1>
      <g-link href="https://bit.ly/3abjhqv" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/pauls.jpg"
          alt   = "St. Pauls Cathedral"
      /></g-link>
      <p class="text-blue-200">
      St. Paul's Churchyard<br /> London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2RFn8p5"
          target = "_blank"
        >
          EC4M 8AD
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
       <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £17.00 <br />Concession £15.00 <br />Children: £7.20 
<br />Family: £41.20<br /><br />
   
      Opening Times: <br />Mon To Sun<br />
      8.30am To 3.30pm  <br />Required To Book Online<br />

      

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
The cathedral is one of the most <br />recognisable sights of London......
<input id="read-more-pauls-1" class="read-more-pauls" type="checkbox">

  <div class="read-more-content">
<br />
 It sits on Ludgate Hill <br /> at the highest point of the City of London<br /> and is a Grade I listed building. 
 </div>
<label class="read-more-pauls-label postcode hover:text-white" for="read-more-pauls-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3abjhqv"
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
.read-more-pauls {
  display: none;
}
.read-more-pauls-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-pauls-label:after {
  content: "More";
  display: inline-block;
}
.read-more-pauls:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-pauls:checked + .read-more-content + .read-more-pauls-label:after {
  content: "Less";
}
</style>
