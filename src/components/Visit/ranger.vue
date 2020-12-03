<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Ranger’s House</h1>
      <g-link href="http://bit.ly/2OgMGcC" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/ranger.jpg"
          alt = "Ranger’s House"
      /></g-link>
      <p class="text-blue-200">
        Chesterfield Walk<br />
        Blackheath London

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/2TJQa8w"
          target = "_blank"
        >
          SE10 8QX
        </g-link>
      </p>
            <h2 class=" mb-4 text-2xl text-pink-300"></h2>
             <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £10.00 <br />Concession £9.00 <br />Children: £6.00 
<br />Family: £26.00<br /><br />
   
      Opening Times: <br />Sun To Thurs<br />
      11.00am To 3.00pm  <br />Required To Book Online<br />

      

      </h2>


      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2OgMGcC"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
