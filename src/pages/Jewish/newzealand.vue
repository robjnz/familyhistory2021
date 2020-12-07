<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 sub-title">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/newzealand-flag.jpg"
          alt="image of new zealand flag"
        />
        New zealand Jewish Family History Resourses
      </h1>

      <div class="grid sm:flex">
          <jewishgen />
        
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

import dropdown from "@/components/Dropdown/dropdown";



export default {
  metaInfo: {
    title: "New Zealand Jewish",
    meta: [
      {
        name: "description",
        content:
          "new zealand Jewish Family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    jewishgen,

    dropdown,
   
  },
};
</script>
