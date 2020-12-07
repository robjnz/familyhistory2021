<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 sub-title">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/uk-flag.jpg"
          alt="british flag"
        />
        British Jewish Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <jc />
        <jcr />
        <jfs />
      </div>

      <div class="grid sm:flex">
        <first />
        <marriage />
        <army />
      </div>

      <div class="grid sm:flex">
        <fifty />
        <fiftyone />
      </div>

      <br />
      <div class="border-b-4 border-gray-200"></div>
      <br />

      <h1 class="ml-8 mt-3 sub-title">
        Jewish Cemeteries
      </h1>

      <adath />
      <fed />
      <liberal />
      <united />
      <western />

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
import jcr from "@/components/UK/Jewish/jcr";
import jc from "@/components/UK/Jewish/jc";
import jfs from "@/components/UK/Jewish/jfs";
import first from "@/components/UK/Jewish/first";
import marriage from "@/components/UK/Jewish/marriage";
import army from "@/components/UK/Jewish/army";
import fifty from "@/components/UK/Jewish/fifty";
import fiftyone from "@/components/UK/Jewish/fiftyone";

import adath from "@/components/UK/Jewish/Cemeteries/adath";
import fed from "@/components/UK/Jewish/Cemeteries/fed";
import liberal from "@/components/UK/Jewish/Cemeteries/liberal";
import united from "@/components/UK/Jewish/Cemeteries/united";
import western from "@/components/UK/Jewish/Cemeteries/western";
import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "British Jewish",
    meta: [
      {
        name: "description",
        content:
          "British jewish family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    jcr,
    jc,
    jfs,
    adath,
    fed,
    liberal,
    united,
    western,
    first,
    army,
    marriage,
    fifty,
    fiftyone,
    dropdown,
    
  },
};
</script>
<style></style>
