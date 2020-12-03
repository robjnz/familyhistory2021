<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Olympic Park</h1>
      <g-link href="http://bit.ly/33bvDwV" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/olympic.jpg"
          alt = "Olympic Park"
      /></g-link>
      <p class="text-blue-200">
        Olympic Park<br /> Stratford London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/3aN2Lxt"
          target = "_blank"
        >
         E20 2ST
        </g-link>
      </p>
      <br /><br />
        <!--
         <h2 class="text-2xl text-pink-300">Driverless Pod Trial</h2>
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
        Mon 9 – Fri 20 March
      </p>
      -->
      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/33bvDwV"
        target = "_blank"
      >
        More Info
      </g-link>
 

    </div>
  </div>
</template>

