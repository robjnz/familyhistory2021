<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">

       <!--pick --
       <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of <br />places to visit in London is:
          
          </h1>
  --end-->
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Tower Of London</h1>
      <g-link href="http://bit.ly/2OKnQ4U" target="_blank" aria-label="open new window"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/tower.jpg"
          fluid-grow
          alt = "Tower Of London"
      /></g-link>
      <p class="text-blue-200">
        Tower of London<br />Wapping London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/38OAXr8"
          target = "_blank" aria-label="open new window"
        >
         EC3N 4AB
        </g-link>
      </p>
               <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £25.00 <br />Concession £20.00 <br />Children: 12.50 
      <br />Family Saver 1: £37.50 1 Adult & 3 Children<br />Family Saver 2: £62.50 2 Adults & 3 Children 


<br /><br />
   
      Opening Times: <br />Wednesday To Sunday<br />
       10.pm To 6.00pm <br /> Required To Book Online<br />

      

      </h2>

      <iframe  class = "h-32 w-full object-fill" title="video virtual tour of the The Tower of London 0.32 minute long" src="https://www.youtube.com/embed/p-JACPCa3rA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2OKnQ4U"
        target = "_blank" aria-label="open new window"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>

