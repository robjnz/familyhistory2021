<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-white text-center">
         United Kingdom</h1>

     
        <g-image 
          class = "h-32 w-full object-fill"
          src   = "@/images/europe/uk-flag.jpg"
          alt = "uk flag"
      />
       <br />
      <ul class=""> 
      
      <li>Capital: London</li>
      <li>Language: <br />English</li>
      <li>Currency:  Pound Sterling</li>
      <li>Population: 66.65 million <br />in 2019</li><br />
      <li>Religion:<br />Christianity 60%<br /> Islam 4%<br />Hinduism 1.3%  <br /> 
      Sikhism 0.7%<br /> Buddhism 0.4% <br />Jewish 0.4% </li>
      <br />

      <li>Genealogy Resourses:<br />
      <g-link
          class  = "text-white hover:text-yellow-500"
          to     = "/Europe/britishgeneral">
          General
        </g-link>

        <br />

        <g-link
          class  = "text-white hover:text-yellow-500"
          to     = "/Jewish/british">
          Jewish
        </g-link>
      
      </li>
      </ul>

    </div>
  </div>
</template>


