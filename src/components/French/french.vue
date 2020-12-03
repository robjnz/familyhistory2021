<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-white text-center">
         France</h1>

     
        <g-image 
          class = "h-32 w-full object-fill"
          src   = "@/images/europe/french-flag.jpg"
          alt = "french flag"
      />
       <br />
      <ul class=""> 
      
      <li>Capital: Paris</li>
      <li>Language: <br />French</li>
      <li>Currency: Euro</li>
      <li>Population: 66.99 million <br />in 2019</li><br />
      <li>Religion:<br />Roman Catholic 41%<br />Islam 5%<br /> Eastern Orthodoxy 2%<br /> Protestantism 2%<br /> 
        Buddhism 1% <br />Jewish 1% </li>
      <br />

      <li>Genealogy Resourses:<br />
      <g-link
          class  = "text-white hover:text-yellow-500"
          to     = "/Europe/frenchgeneral">
          General
        </g-link>

        <br />
<!--
        <g-link
          class  = "text-white hover:text-yellow-500"
          to     = "/Jewish/british">
          Jewish
        </g-link>
      -->
      </li>
      </ul>

    </div>
  </div>
</template>


