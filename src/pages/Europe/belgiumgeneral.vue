<template>
  <Layout>
    <section class="px-32 py-14">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/belgium-flag.jpg"
          alt="austria flag"
        />
        Belgium Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <statearchives />
        <ancestry />
        <genealogy />

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
import statearchives from "@/components/Belgium/General/statearchives";
import genealogy from "@/components/Belgium/General/genealogy";
import ancestry from "@/components/Belgium/General/ancestry";
import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Belgium",
    meta: [
      {
        name: "description",
        content: "Belgium family history records of birth death and marriages",
      },
    ],
  },
  components: {
    statearchives,
    genealogy,
    ancestry,
    dropdown,
    
  },
};
</script>
