<template>
  <Layout>
    <section class="px-32 py-14 overflow-auto">
    <div id="background" class="container m-auto">
      <h1 class="ml-8 mt-3 text-4xl text-teal-900">
        <g-image
          class="h-10 w-12 inline-block"
          src="@/images/europe/uk-flag.jpg"
          alt="british flag"
        />

        British Family History Resourses
      </h1>

      <br />

      <div class="grid sm:flex">
        <birth />
        <children />
        <companies />
      </div>

      <div class="grid sm:flex">
        <roll />
        <trade />
        <industral />
      </div>

      <div class="grid sm:flex">
        <gazette />
        <newspaper />
        <raf />
      </div>

      <div class="grid sm:flex">
        <state />
        <war />
        <wills />
      </div>
      <div class="grid sm:flex">
        <workhouse />
        <thirtynine />
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
    </div>
    </section>
  </Layout>
</template>

<script>
import birth from "@/components/UK/General/birth";
import newspaper from "@/components/UK/General/newspaper";
import companies from "@/components/UK/General/companies";
import state from "@/components/UK/General/state";
import raf from "@/components/UK/General/raf";
import gazette from "@/components/UK/General/gazette";
import wills from "@/components/UK/General/wills";
import war from "@/components/UK/General/war";
import thirtynine from "@/components/UK/General/thirtynine";
import roll from "@/components/UK/General/roll";
import trade from "@/components/UK/General/trade";
import workhouse from "@/components/UK/General/workhouse";
import children from "@/components/UK/General/children";
import industral from "@/components/UK/General/industral";

import dropdown from "@/components/Dropdown/dropdown";

export default {
  metaInfo: {
    title: "British",
    meta: [
      {
        name: "description",
        content:
          "British family history where to find records of birth death and marriages",
      },
    ],
  },
  components: {
    birth,
    newspaper,
    companies,
    raf,
    state,
    gazette,
    wills,
    war,
    thirtynine,
    roll,
    trade,
    workhouse,
    children,
    industral,
    dropdown,
  },
};
</script>
