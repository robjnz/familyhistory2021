<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Epping Forest</h1>
      <g-link href="https://bit.ly/2N0SOTq" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/epping.jpg"
          fluid-grow
          alt = "Epping Forest"
      /></g-link>
      <p class="text-blue-200">
        Paul's Nursery Road<br />
        High Beach Essex

        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/2MZX4Cu"
          target = "_blank"
        >
          IG10 4AF
        </g-link>
      </p>

       <h2 class=" mb-4 text-2xl text-pink-300"></h2>
      <article class="text-blue-200">
  Epping Forest is a 2,400-hectare area<br /> of ancient woodland....... 
  <input id="read-more-epping-1" class="read-more-epping" type="checkbox">
  <div class="read-more-content">
      <br />
 between Epping in Essex to the north,<br /> and Forest Gate in Greater <br />London to the south,<br /> straddling the border <br />between London and Essex. 
  </div>
  <label class="read-more-epping-label postcode hover:text-white" for="read-more-epping-1">Read </label>
</article>
        
     
    
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2N0SOTq"
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
.read-more-epping {
  display: none;
}
.read-more-epping-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-epping-label:after {
  content: "More";
  display: inline-block;
}
.read-more-epping:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-epping:checked + .read-more-content + .read-more-epping-label:after {
  content: "Less";
}
</style>

