<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-white text-center">
         Ukraine</h1>

     
        <g-image 
          class = "h-32 w-full object-fill"
          src   = "@/images/europe/ukraine-flag.jpg"
          alt = "ukraine flag"
      />
       <br />
      <ul class=""> 
      
      <li>Capital: Kyiv</li>
      <li>Language: <br />Ukrainian</li>
      <li>Currency:  Ukrainian Hryvnia</li>
      <li>Population: 41.98 million <br />in 2019</li><br />
      <li>Religion:<br />Eastern Orthodoxy 67%<br /> Greek Orthodoxy 9%<br />Christian 7%  <br /> 
      Jewish 0.4%<br /> Buddhist 0.1%<br />Hindu 0.1% <br /> Pagan 0.1%</li>
      <br />

      <li>Genealogy Resourses:<br />
      <g-link
          class  = "text-white hover:text-yellow-500"
          to     = "/Europe/ukrainegeneral">
          General
        </g-link>

        <br />

        <g-link
          class  = "text-white hover:text-yellow-500"
          to     = "/Jewish/ukraine">
          Jewish
        </g-link>
      
      </li>
      </ul>

    </div>
  </div>
</template>


