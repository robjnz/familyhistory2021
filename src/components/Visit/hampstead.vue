<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span> Hampstead Heath</h1>
      <g-link href="https://bit.ly/2VfzR49" target="_blank"
        ><g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/hampstead.jpg"
          alt   = "hampstead Heath"
      /></g-link>
      <p class="text-blue-200">
     Hampstead Lane<br />
Highgate London 


        <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3abNWnh"
          target = "_blank"
        >
          NW3 7JR
        </g-link>
      </p>
      
      <h2 class=" mb-4 text-2xl text-pink-300"></h2>
      
      <!--
      <p class="text-pink-300">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Thurs 19 March
      
      </p>
      -->
      <article class="text-blue-200">
 From Parliament Hill is the<br /> best view of London........
<input id="read-more-hampstead-1" class="read-more-hampstead" type="checkbox">

  <div class="read-more-content">
<br />
 ......
 </div>
<label class="read-more-hampstead-label postcode hover:text-white" for="read-more-hampstead-1">Read </label>
</article>
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2VfzR49"
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
.read-more-hampstead {
  display: none;
}
.read-more-hampstead-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-hampstead-label:after {
  content: "More";
  display: inline-block;
}
.read-more-hampstead:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-hampstead:checked + .read-more-content + .read-more-hampstead-label:after {
  content: "Less";
}
</style>
