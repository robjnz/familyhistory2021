<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Jack The Ripper Museum </h1>
      <g-link href="http://bit.ly/2vxQka1" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/jack.jpg"
          alt = "Jack The Ripper Museum"
      /></g-link>
      <p class="text-blue-200">
       12 Cable Street<br />Whitechapel London


        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/38trqp8"
          target = "_blank"
        >
           E1 8JG
        </g-link>
      </p>

           <h2 class=" mb-4 text-2xl text-pink-300"></h2>
  <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £10.00 <br />Children: £8.00 
<br /><br />
   
      Opening Times: <br />Mon To Sun<br />
      9.30am To 6.30pm  

      

      </h2>

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2vxQka1"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>



