<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 sub-title">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/ireland-flag.jpg"
          alt="ireland flag"
        />
        Ireland Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <census />
        <genealogy />
        <toolkit />
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
import census from "@/components/Ireland/General/census";
import genealogy from "@/components/Ireland/General/genealogy";
import toolkit from "@/components/Ireland/General/toolkit";
import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Ireland",
    meta: [
      {
        name: "description",
        content:
          "Ireland family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    census,
    genealogy,
    toolkit,
    dropdown,
  },
};
</script>
