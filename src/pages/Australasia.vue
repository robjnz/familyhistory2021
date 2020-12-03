<template>
  <Layout>
    <section class="px-32 py-14">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <span class="text-teal-900">
          <i class="fas fa-theater-masks"></i>
        </span>
        Family History Resourses For Australasia
      </h1>

      <br />

      <div class="grid sm:flex">
        <australia />
        <newzealand />
       
      </div>
    </div>
    <br />
    </section>
  </Layout>
</template>

<script>
import australia from "@/components/Australasia/australia";
import newzealand from "@/components/Newzealand/newzealand";

export default {
  metaInfo: {
    title: "New Zealand",
    meta: [
      {
        name: "description",
        content:
          "New Zealand where to find family history Resourses of birth, death and mariages",
      },
    ],
  },
  components: {
    australia,
    newzealand,
    
  },
};
</script>

<style></style>
