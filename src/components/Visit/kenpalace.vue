<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <!--pick --
       <h1 class="text-orange-400 text-2xl">
        <span class="text-blue-100" style="font-size: 1em;">
      <i class="fas fa-thumbs-up"></i>
      </span>
       
          Today's top pick of <br />places to visit in London is:
          
          </h1>
  ---end-->
      <h1 class="text-2xl text-blue-200"><span class="text-pink-300">
           <i class="fas fa-landmark"></i>
        </span>  Kensington Palace</h1>
      <g-link href="https://bit.ly/2S3ZPW7" target="_blank" aria-label="open new window"
        >
        <g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/kenpalace.jpg"
          alt   = "Kensington Palace"
      /></g-link>
      <p class="text-blue-200">
     
      Kensington Gardens<br />Kensington London


  <g-link
          class  = "postcode hover:text-white"
          to     = "https://bit.ly/3eNxtcx"
          target = "_blank" aria-label="open new window"
        >
          W8 4PX
        </g-link>
      
       <h2 class=" mb-4 text-base text-orange-300">
        
      Adults: £17.00 <br />Concession £13.60 <br />Children: £8.50 
<br />Family: £42.50<br /><br />
   
      Opening Times: <br />Wednesday To Sunday<br />
      10.30am To 5.00pm  <br />Required To Book Online<br />

      

      </h2>
      
     <h2 class="text-2xl event"> Events:</h2>
      <g-link href="https://bit.ly/30a5Rso" target="_blank" aria-label="open new window"
        >
        <g-image
          class = "h-32 w-full object-fill"
          src   = "@/images/visit/queen.jpg"
          alt   = "Life Through a Royal Lens image"
      /></g-link>
      <h2 class="text-2xl event"> Life Through a Royal Lens</h2>

      <p class="event">
        <span>
          <i class="far fa-calendar-alt"></i>
        </span>
       Opening March 2021<br /><br />
      
      Iconic photographs taken of the <br />royal family from Queen Victoria <br />to the present Day.

      </p>
      <br />
      
      <article class="text-blue-200">

 Royal palace and gardens, with exhibits<br /> on former residents.......
<input id="read-more-kenpalace-1" class="read-more-kenpalace" type="checkbox">

  <div class="read-more-content">
<br />
like Queen Victoria and Princess Diana.
</div>
<label class="read-more-kenpalace-label postcode hover:text-white" for="read-more-kenpalace-1">Read </label>
</article>

<br />
  <iframe class="h-32 w-full object-fill" aria-label="youtube-video" title="video trailer of kensington palace 0.30 seconds" src="https://www.youtube.com/embed/BKkE2Wj3xC0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allow64screen></iframe>

<br />
      <g-link
        class  = "postcode hover:text-white"
        to     = "https://bit.ly/2S3ZPW7"
        target = "_blank" aria-label="open new window"
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
.read-more-kenpalace {
  display: none;
}
.read-more-kenpalace-label {
  display    : inline-block;
  user-select: none;
  cursor     : pointer;
  border     : none;
  padding    : 5px;
  margin     : .5em;
  font-size  : 16px;
}
.read-more-kenpalace-label:after {
  content: "More";
  display: inline-block;
}
.read-more-kenpalace:checked + .read-more-content {
  display: block;
  /* css animation won't work with "auto"; set to some height larger
    than the content */
  max-height: 1000px;
}
.read-more-kenpalace:checked + .read-more-content + .read-more-kenpalace-label:after {
  content: "Less";
}
</style>
