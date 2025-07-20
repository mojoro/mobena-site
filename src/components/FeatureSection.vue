<script setup lang="ts">
import FeatureCard from './FeatureCard.vue'
</script>
<template>
  <div class="feature-section w-full px-4 py-16">
    <div class="mx-auto max-w-7xl text-center">
      <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
        Changing Tax and Accounting Forever
      </h2>
      <p class="mx-auto mt-4 max-w-2xl text-lg text-white/80">
        Mobena is the first income and estate tax planning platform that provides accurate planning
        over a multigenerational timeframe
      </p>
      <div class="mt-12 grid gap-8 md:grid-cols-3">
        <FeatureCard
          title="Accurate Income Tax"
          description="Mobena was created by family office tax advisors to model tax the way that CPAs model tax for wealthy families"
          imgSrc="https://cdn.prod.website-files.com/643010cf972169b0d887edac/6706394cb9459aaa57b8ddc4_Teisis6.jpg"
          imgAlt="Accurate Income Tax"
        />
        <FeatureCard
          title="Real Life Structures"
          description="Like real life, Mobena reflects tiered-entity structures for the entire family and their trusts."
          imgSrc="https://apptad.com/wp-content/uploads/2025/04/AdobeStock_473276539-2.jpeg"
          imgAlt="Real Life Structures"
        />
        <FeatureCard
          title="Trust and Estate Models"
          description="Mobena was built to handle accurate trust income tax and estate tax treatment."
          imgSrc="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcSbNO5kx_SPn76j6XQD3GlZjUf4XySpqE5LSlAj6OniEWvuG94w"
          imgAlt="Trust and Estate Models"
        />
      </div>
    </div>
  </div>
</template>
