<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/ukraine-flag.jpg"
          alt="ukraine flag"
        />
        Ukraine Jewish Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <dnipropetrovsk />
        <memorial />
        <dnipro />
      </div>

      <div class="grid sm:flex">
        <moved />
        <mogilev />
        <mohyliv />
      </div>

      <div class="grid sm:flex">
        <skala />
        <gen />
        <kehilalinks />
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
import dnipropetrovsk from "@/components/Ukraine/Jewish/dnipropetrovsk";
import memorial from "@/components/Ukraine/Jewish/memorial";
import dnipro from "@/components/Ukraine/Jewish/dnipro";
import moved from "@/components/Ukraine/Jewish/moved";
import mogilev from "@/components/Ukraine/Jewish/mogilev";
import mohyliv from "@/components/Ukraine/Jewish/mohyliv";
import skala from "@/components/Ukraine/Jewish/skala";
import gen from "@/components/Ukraine/Jewish/gen";
import kehilalinks from "@/components/Ukraine/Jewish/kehilalinks";
import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Ukraine",
    meta: [
      {
        name: "description",
        content:
          "Ukraine jewish family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    dnipropetrovsk,
    memorial,
    dnipro,
    moved,
    mogilev,
    mohyliv,
    skala,
    gen,
    kehilalinks,
    dropdown,
  },
};
</script>
