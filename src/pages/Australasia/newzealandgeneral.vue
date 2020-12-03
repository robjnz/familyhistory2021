<template>
  <Layout>
    <section class="px-32 py-14">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/newzealand-flag.jpg"
          alt="image of australian flag"
        />
        New Zealand Family History Resourses
      </h1>

      <div class="grid sm:flex">
        <cemeteries />
        <companies />
        <gazette />
      </div>

      <div class="grid sm:flex">
        <birth />
        <archway />
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
import archway from "@/components/Newzealand/General/archway";
import cemeteries from "@/components/Newzealand/General/cemeteries";
import birth from "@/components/Newzealand/General/birth";
import companies from "@/components/Newzealand/General/companies";
import gazette from "@/components/Newzealand/General/gazette";

import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "New zealand",
    meta: [
      {
        name: "description",
        content:
          "New zealand Family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    archway,
    cemeteries,
    birth,
    companies,
    gazette,

    dropdown,
  },
};
</script>
