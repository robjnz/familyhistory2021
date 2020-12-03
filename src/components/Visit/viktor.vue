<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Viktor Wyne Museum</h1>
      <g-link href="http://bit.ly/2CHwY42" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/viktor.jpg"
          fluid-grow
          alt = "Viktor Wyne Museum"
      /></g-link>
      <p class="text-blue-200">
        11 Mare Street<br />Hackney London 

        <g-link
          class  = "postcode hover:text-white"
          to     = "http://bit.ly/3aWJKJ9"
          target = "_blank"
        >
          E8 4RP 
        </g-link>
      </p>
             <h2 class=" mb-4 text-2xl text-pink-300"></h2>
              <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £8.00 <br />
<br />
      Opening Times: <br />Wed To Sun<br />12.00pm To 10.00pm
      <br />Book Online
      <br />
      </h2>

       <article class="text-blue-200">
The Country's only <br />Curiosity Museum.....
<input id="read-more-viktor-1" class="read-more-viktor" type="checkbox">
  <div class="read-more-content">
    <br />
Is dedicated to subverting life,<br /> the universe and everything bored<br /> of the life and world it sees around it<br /> seeks to create a new world<br /> filled with beauty,<br /> wonder and the imagination.

  </div>
 <label class="read-more-viktor-label postcode hover:text-white" for="read-more-viktor-1">Read </label>
</article>

      <g-link
        class  = "postcode hover:text-white"
        to     = "http://bit.ly/2CHwY42"
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
.read-more-viktor {
  display: none;
}
.read-more-viktor-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-viktor-label:after {
  content: "More";
  display: inline-block;
}
.read-more-viktor:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-viktor:checked + .read-more-content + .read-more-viktor-label:after {
  content: "Less";
}
</style>



