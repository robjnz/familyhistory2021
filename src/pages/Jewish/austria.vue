<template>
  <Layout>
    <section class="px-32 py-14">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/austria-flag.jpg"
          alt="austria flag"
        />
        Austrian Jewish Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <viennabirth />
        <viennaweddings />
        <viennacemetery />

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
import viennabirth from "@/components/Austrian/Jewish/viennabirth";
import viennaweddings from "@/components/Austrian/Jewish/viennaweddings";
import viennacemetery from "@/components/Austrian/Jewish/viennacemetery";
import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "Austria Jewish",
    meta: [
      {
        name: "description",
        content: "Austrian Vienna jewish records of birth death and marriages",
      },
    ],
  },
  components: {
    viennacemetery,
    viennabirth,
    viennaweddings,
    dropdown,
   
  },
};
</script>
<style></style>
