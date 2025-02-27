<script setup lang="ts">
import Header from "./components/Header.vue";
import WhoAmI from "./components/WhoAmI.vue";
import WhatIDo from "./components/WhatIDo.vue";
import FeaturesProjects from "./components/FeaturesProjects.vue";
import WorkExperience from "./components/WorkExperience.vue";
import ContactHere from "./components/ContactHere.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="flex h-screen flex-col overflow-x-hidden">
    <div class="flex flex-1">
      <div class="w-1/12 border-r-3 max-sm:hidden"></div>
      <div class="w-full bg-dots">
        <div class="container mx-auto px-4 py-6">
          <Header />
          <WhoAmI />
          <WhatIDo />
          <FeaturesProjects />
          <WorkExperience />
          <ContactHere />
          
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<style>
.bg-dots {
  background-image: radial-gradient(#cbd5e1 1px, transparent 1px);
  background-size: 20px 20px;
  background-color: white;
}

@media (max-width: 768px) {
  .bg-dots {
    background-size: 15px 15px;
  }
}

@media (max-width: 640px) {
  .bg-dots {
    background-size: 10px 10px;
  }
}
</style>
