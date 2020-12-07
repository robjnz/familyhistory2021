<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 sub-title">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/netherlands-flag.jpg"
          alt="netherlands flag"
        />
        Netherlands Jewish Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <akevoth />
        <amstadam />
        <cemeteries />
      </div>

      <div class="grid sm:flex">
        <joods />
        <sephardic />
      </div>
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
    </section>
  </Layout>
</template>

<script>
import amstadam from "@/components/Netherlands/Jewish/amstadam";
import cemeteries from "@/components/Netherlands/Jewish/cemeteries";
import akevoth from "@/components/Netherlands/Jewish/akevoth";
import joods from "@/components/Netherlands/Jewish/joods";
import sephardic from "@/components/Netherlands/Jewish/sephardic";
import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Nevelands Jewish",
    meta: [
      {
        name: "description",
        content:
          "Neverlands family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    amstadam,
    cemeteries,
    akevoth,
    joods,
    sephardic,
    dropdown,
  },
};
</script>
