<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 sub-title">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/austria-flag.jpg"
          alt="austria flag"
        />
        Austrian Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <statearchives />
        <genteam />
        <vienna />

        <br />
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
import statearchives from "@/components/Austrian/General/statearchives";
import genteam from "@/components/Austrian/General/genteam";
import vienna from "@/components/Austrian/General/vienna";
import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Austrian",
    meta: [
      {
        name: "description",
        content: "Austrian Vienna records of birth death and marriages",
      },
    ],
  },
  components: {
    statearchives,
    genteam,
    vienna,
    dropdown,
  },
};
</script>
