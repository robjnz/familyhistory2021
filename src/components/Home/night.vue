<template>
  <div class="m-4 p-4 w-auto rounded-lg">
    <div class="p-6">
      <h2 class="text-3xl text-blue-500">
        <span>
          <i class="fas fa-glass-cheers"></i>
        </span>
        Nightclubs
      </h2>
      
    
       
      

      <g-link class="text-blue-500 text-2xl hover:text-white" to="/nightclubs"
        >More Nightclubs</g-link
      >
    </div>
  </div>
</template>

<script>
import atik from "@/components/Nightclubs/atik";
import faces from "@/components/Nightclubs/faces";
import xoyo from "@/components/Nightclubs/xoyo";




export default {
  components: {
    atik,
    faces,
    xoyo,
   
    
  }
};
</script>
