<script setup>
import Navbar from "@/components/Navbar.vue";
import Hero from "@/components/Hero.vue";
import HomeCards from "./components/HomeCards.vue";
import JobListings from "./components/JobListings.vue";
import JobListing from "./components/JobListing.vue";
</script>

<template>
  <Navbar />
  <Hero
    title="Become a Vue Dev"
    subtitle="Find the Vue job that fits your skills and needs"
  />
  <HomeCards />
  <JobListings />
  <JobListing />
</template>
