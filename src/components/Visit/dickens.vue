<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">

      <!--pick 
       <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of <br />places to visit in London is:
          
          </h1>
  end-->
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Charles Dickens Museum </h1>
      <g-link href="https://bit.ly/3g0baAG" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/dickens.jpg"
          alt   = "Charles Dickens Museum"
      /></g-link>
      <p class="text-blue-200">
        48-49 Doughty Street<br />London 



        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3jL8Yzt"
          target = "_blank"
        >
          WC1N 2LX
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
        <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £9.50 <br />Concession £7.50 <br />Children: £4.50 
<br /><br />
   
      Opening Times: <br />Fri To Sun<br />
      10.00am To 5.00pm  <br />Required To Book Online<br />

      

      </h2>
      <h1 class="text-2xl text-teal-400"> Events:</h1>
      <h2 class="text-2xl text-teal-400"> The Living Image <br />of Charles Dickens</h2>

      <p class="text-teal-400">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       <br />Sat 25th July 2020 to <br />Sun 25th April 2021<br /><br />
      
      The exhibition explores the <br />power of the writer’s image.<br /> Starting in his own lifetime,<br /> through artist interpretations,<br /> radical rethinking in popular culture.
      </p>
<br />
      <iframe class = "h-32 w-full object-fill" src="https://www.youtube.com/embed/914VgyAka3E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      
      <article class="text-blue-200">
   The Victorian family home<br /> of Charles Dickens.......

<input id="read-more-dickens-1" class="read-more-dickens" type="checkbox">

  <div class="read-more-content">
<br />

Uncover the private world behind<br />  the author where the he wrote <br />Oliver Twist, <br />Pickwick Papers<br /> and Nicholas Nickleby. 
</div>
<label class="read-more-dickens-label postcode hover:text-white" for="read-more-dickens-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/3g0baAG"
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
.read-more-dickens {
  display: none;
}
.read-more-dickens-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-dickens-label:after {
  content: "More";
  display: inline-block;
}
.read-more-dickens:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-dickens:checked + .read-more-content + .read-more-dickens-label:after {
  content: "Less";
}
</style>
