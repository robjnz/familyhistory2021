<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 sub-title">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/russian-flag.jpg"
          alt="russian flag"
        />
        Russian Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <cyrillic />
        <print />
        <tree />
      </div>

      <div class="grid sm:flex">
        <forebears />
        <hero />
        <family />
      </div>

      <div class="grid sm:flex">
        <awards />
        <military />
        <soviet />
      </div>

      <div class="grid sm:flex">
        <temples />
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
import tree from "@/components/Russia/General/tree";
import cyrillic from "@/components/Russia/General/cyrillic";
import forebears from "@/components/Russia/General/forebears";
import family from "@/components/Russia/General/family";
import print from "@/components/Russia/General/print";
import awards from "@/components/Russia/General/awards";
import military from "@/components/Russia/General/military";
import temples from "@/components/Russia/General/temples";
import soviet from "@/components/Russia/General/soviet";
import hero from "@/components/Russia/Jewish/hero";
import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Russia",
    meta: [
      {
        name: "description",
        content:
          "russian family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    tree,
    cyrillic,
    forebears,
    family,
    print,
    awards,
    military,
    soviet,
    temples,
    hero,
    dropdown,
  },
};
</script>
