<template>
  <div id="work-card" class="m-4 p-4 w-auto rounded-lg shadow-2xl">
    <div class="p-6">
      <h1 class="text-2xl text-white">
        Historical Records
      </h1>

      <g-image
        class="h-32 w-full object-fill"
        src="@/images/europe/nz-birth-cert.jpg"
        alt="image of newzealand birth cerificates"
      />
      <br />
      <ul>
        <li>Births over 100 year's</li>
        <li>Marriages over 80 year's</li>
        <li>Deaths over 50 year's</li>
      </ul>

      <br />
      <g-link
        class="text-white hover:text-yellow-500"
        to="http://bit.ly/2I57AYi"
      >
        More Info
      </g-link>
    </div>
  </div>
</template>
