<template>
  <Layout>
    <section class="px-32 py-14">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/australia-flag.jpg"
          alt="image of australian flag"
        />
        Australia Family History Resourses
      </h1>

      <div class="grid sm:flex">
          <genealogysa />
        <south />
        <statearchives />
      </div>

      <br />
      <p>
       
        <dropdown />
      
      </p>
      <br />
      <p>
        Add
        <g-link
          class="text-red-600 hover:text-yellow-600"
          to="http://bit.ly/2SxWdgt"
          target="_blank"
        >
          google translate
        </g-link>
        to your browser extensions, to view foreign language web sites.
      </p>

      <br />
    </div>
    </section>
  </Layout>
</template>

<script>
import south from "@/components/Australasia/General/south";
import statearchives from "@/components/Australasia/General/statearchives";
import genealogysa from "@/components/Australasia/General/genealogysa";

import dropdown from "@/components/Dropdown/dropdown";
import jewish from "@/components/Dropdown/jewish";
import australasia from "@/components/Dropdown/australasia";
import europe from "@/components/Dropdown/europe";


export default {
  metaInfo: {
    title: "Australasia",
    meta: [
      {
        name: "description",
        content:
          "Australasia Family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    south,
    statearchives,
    genealogysa,

    dropdown,
    jewish,
    australasia,
    europe,
    
  },
};
</script>
