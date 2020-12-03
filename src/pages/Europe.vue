<template>
  <Layout>
    <section class="px-32 py-14">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <span class="text-teal-900">
          <i class="fas fa-theater-masks"></i>
        </span>
        Family History Resourses For Europe
      </h1>

      <br />

      <div class="grid sm:flex">
        <austria /><!--Austria-->
        <belarus /><!--Belarus-->
        <belgium /><!--Belgium-->
      </div>

      <div class="grid sm:flex">
        <french />
        <ireland />
        <netherlands />
      </div>

      <div class="grid sm:flex">
        <russia />
        <ukraine />
        <british />
      </div>
    </div>
    <br />
    </section>
  </Layout>
</template>

<script>
import austria from "@/components/Austrian/austria";
import belarus from "@/components/Belarus/belarus";
import belgium from "@/components/Belgium/belgium";
import ireland from "@/components/Ireland/ireland";
import netherlands from "@/components/Netherlands/netherlands";
import russia from "@/components/Russia/russia";
import ukraine from "@/components/Ukraine/ukraine";
import british from "@/components/UK/british";
import french from "@/components/French/french";

export default {
  metaInfo: {
    title: "Europe",
    meta: [
      {
        name: "description",
        content:
          "Australasia where to find family history Resourses of birth, death and mariages",
      },
    ],
  },
  components: {
    austria,
    belarus,
    belgium,
    ireland,
    netherlands,
    russia,
    ukraine,
    british,
    french,
  },
};
</script>

<style></style>
