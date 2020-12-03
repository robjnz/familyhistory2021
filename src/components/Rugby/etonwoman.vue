<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h2 class="flex flex-row text-2xl text-blue-200">
        <span class="text-pink-300 mr-2">
          <i class="fas fa-football-ball"></i>
        </span>
        Eton<span class="ml-2 text-pink-200">Women's Team</span>
      </h2>
      <g-link href="https://bit.ly/3a947CN" target="_blank"
        ><g-image
          class = "w-auto h-auto"
          src   = "~/images/rugby/eton.jpg"
          alt   = "Eton Manor"
      /></g-link>
      <p class="text-blue-200 text-center">
          <br />
        Nutter Lane<br />Wanstead London



        <g-link
          class  = "text-red-700 hover:text-white"
          to     = "https://bit.ly/2UdPo48"
          target = "_blank"
        >
          E11 2JA
        </g-link>
        <br /><br /><br />
      </p>

      <p class="text-pink-200 text-center">
        <span class="text-pink-300">
          <i class="far fa-calendar-alt"></i>
        </span>
        <!--
        Sat 18 April - 3pm <br /><span class="text-red-700">V</span>
        <br />Upminster
-->
        <br />
      </p>

      <g-link
        class  = "text-red-700 hover:text-white"
        to     = "https://bit.ly/3a947CN"
        target = "_blank"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
