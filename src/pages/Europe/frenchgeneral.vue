<template>
  <Layout>
    <section class="px-32 py-14">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/french-flag.jpg"
          alt="french flag"
        />

        French Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <naturalisation />
        <state />
      </div>

     
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
import state from "@/components/French/General/state";
import naturalisation from "@/components/French/General/naturalisation";

import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "British",
    meta: [
      {
        name: "description",
        content:
          "French family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    naturalisation,
    state,
    
    dropdown,
  },
};
</script>
