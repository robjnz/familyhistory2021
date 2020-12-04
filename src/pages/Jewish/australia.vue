<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/australia-flag.jpg"
          alt="image of australian flag"
        />
        Australia Jewish Family History Resourses
      </h1>

      <div class="grid sm:flex">
          <jewishgen />
          <historical />
        
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
import jewishgen from "@/components/Australasia/Jewish/jewishgen";
import historical from "@/components/Australasia/Jewish/historical";

import dropdown from "@/components/Dropdown/dropdown";



export default {
  metaInfo: {
    title: "Australasia Jewish",
    meta: [
      {
        name: "description",
        content:
          "Australasia Jewish Family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    jewishgen,
    historical,

    dropdown,
   
  },
};
</script>
