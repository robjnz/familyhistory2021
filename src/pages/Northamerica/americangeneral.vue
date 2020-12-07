<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
      <div id="background" class="container m-auto">
        <h1 class="ml-8 mt-3 sub-title">
          <g-image
            class="h-10 w-12 inline-block"
            src="@/images/europe/american-flag.jpg"
            alt="image of usa flag"
          />
          USA Family History Resourses
        </h1>

        <div class="grid sm:flex">
          <state />
          <war />
        </div>

        <br />
        <div class="border-b-4 border-gray-200"></div>
        <br />
        <h2 class="ml-8 mt-3 sub-title">
          <g-image
            class="h-10 w-12 inline-block"
            src="@/images/europe/newyork.jpg"
            alt="image of usa flag"
          />
          New York
        </h2>
        <br />
        <div class="grid sm:flex">
          <brooklyn />
          <nyarchives />
          <ellis />
        </div>

        <div class="grid sm:flex">
          <passenger />
          <york />
          <marriage />
        </div>

        <br />
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
      </div>
    </section>
  </Layout>
</template>

<script>
import state from "@/components/America/General/state";
import war from "@/components/America/General/war";
import nyarchives from "@/components/America/General/nyarchives";
import brooklyn from "@/components/America/General/brooklyn";
import passenger from "@/components/America/General/passenger";
import ellis from "@/components/America/General/ellis";
import york from "@/components/America/General/york";
import marriage from "@/components/America/General/marriage";

import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "USA",
    meta: [
      {
        name: "description",
        content:
          "USA Family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    state,
    war,
    nyarchives,
    brooklyn,
    passenger,
    ellis,
    york,
    marriage,

    dropdown,
  },
};
</script>
