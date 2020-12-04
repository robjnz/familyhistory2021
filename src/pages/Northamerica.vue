<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <span class="text-teal-900">
          <i class="fas fa-theater-masks"></i>
        </span>
        Family History Resourses For North America
      </h1>

      <br />

      <div class="grid sm:flex">
        <canada />
        <america />
        
       
      </div>
    </div>
    <br />
    </section>
  </Layout>
</template>

<script>
import canada from "@/components/Canada/canada";
import america from "@/components/America/america";


export default {
  metaInfo: {
    title: "North America",
    meta: [
      {
        name: "description",
        content:
          "North America where to find family history Resourses of birth, death and mariages",
      },
    ],
  },
  components: {
    canada,
    america,
    
  },
};
</script>

<style></style>
