<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 sub-title">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/ukraine-flag.jpg"
          alt="ukraine flag"
        />
        Ukraine Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <dnipropetrovsk />
        <residents />
        <family />
      </div>

      <div class="grid sm:flex">
        <statearchives />
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
import statearchives from "@/components/Ukraine/General/statearchives";
import family from "@/components/Ukraine/General/family";
import residents from "@/components/Ukraine/General/residents";
import dnipropetrovsk from "@/components/Ukraine/General/dnipropetrovsk";

import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Ukraine",
    meta: [
      {
        name: "description",
        content:
          "Ukraine family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    statearchives,
    family,
    residents,
    dnipropetrovsk,
    dropdown,
  },
};
</script>
