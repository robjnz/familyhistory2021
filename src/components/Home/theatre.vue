<template>
  <div class="m-4 p-4 w-auto rounded-lg">
    <div class="p-6">
      <h2 class="text-3xl text-blue-500">
        <span>
          <i class="fas fa-theater-masks"></i>
        </span>
        Theatres
      </h2>

 

    
      
 
    
      
      
      
     
<!--en 1 april -->

<!--2 april-->
    
<!--end 2 april -->
      <g-link class="text-blue-500 text-2xl hover:text-white" to="/theatres"
        >More Theatres</g-link
      >
    </div>
  </div>
</template>

<script>
import barking from "@/components/Theatres/barking";
import greenwichT from "@/components/Theatres/greenwichT";
import hackneyT from "@/components/Theatres/hackneyT";
import hoxton from "@/components/Theatres/hoxton";
import ilford from "@/components/Theatres/ilford";
import hornchurch from "@/components/Theatres/hornchurch";
import stratford from "@/components/Theatres/stratford";
import two from "@/components/Theatres/two";
import wilton from "@/components/Theatres/wilton";
import yard from "@/components/Theatres/yard";

import Blank from "@/components/Home/Blank";



export default {
  components: {
    Blank,
    barking,
    greenwichT,
    hackneyT,
    hornchurch,
    hoxton,
    ilford,
    stratford,
    two,
    wilton,
    yard,
  }
};
</script>
