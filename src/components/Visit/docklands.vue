<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Docklands Museum</h1>
      <g-link href="http://bit.ly/2EyBcwJ" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/docklands.jpg"
          fluid-grow
          alt = "Docklands Museum"
      /></g-link>
      <p class="text-blue-200">
        No1 Warehouse<br />
        West India Quay London

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2vX30Y2"
          target = "_blank"
        >
          E14 4AL
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
       <h2 class=" mb-4 text-base text-orange-300">
        
     Admission free<br /><br />
   
      Opening Times: <br />Mon To Fri<br />
      11.30am To 3.30pm  <br /><br />
      
       Sat To Sun <br />
       10.00am To 6.00pm<br /><br />
      Required To Book Online<br />

      

      </h2>
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2EyBcwJ"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
