<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  The Cartoon Museum </h1>
      <g-link href="https://bit.ly/3fdpmFa" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/cartoon.jpg"
          alt   = "The cartoon Museum"
      /></g-link>
      <p class="text-blue-200">
        63 Wells Street<br />Fitzrovia London  



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/310q5Vf"
          target = "_blank"
        >
          W1T 3PT
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300">Reopens 17 September</h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £8.50 <br />Concession £5.00 <br />Student: £3<br /> Children: Free 
<br /><br />
   
      Opening Times: <br />
      Mon Closed<br />
      Tues To Sat 10.30am To 8.00pm<br />
      Sun 12.00pm To 4.00pm

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
          Holds Over 6000 Cartoons <br />and Comic Artworks.....
<input id="read-more-cartoon-1" class="read-more-cartoon" type="checkbox">

  <div class="read-more-content">
<br />
  .....

</div>
<label class="read-more-cartoon-label postcode hover:text-white" for="read-more-cartoon-1">Read </label>
</article>

<br />
     <iframe class="h-32 w-full object-fill" title="video virtual tour of " src="" frameborder="0" allow="accelerometer; fullplay; encrypted-media; gyroscope; picture-in-picture" allowfullfull></iframe>

<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3fdpmFa"
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
.read-more-cartoon {
  display: none;
}
.read-more-cartoon-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-cartoon-label:after {
  content: "More";
  display: inline-block;
}
.read-more-cartoon:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-cartoon:checked + .read-more-content + .read-more-cartoon-label:after {
  content: "Less";
}
</style>
