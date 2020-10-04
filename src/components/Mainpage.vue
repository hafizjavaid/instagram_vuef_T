<template>
  <v-container class="pa-10">
    <stories-section />
    <feed-section />
  </v-container>
</template>

<script>
import StoriesSection from "./Stories";
import FeedSection from "./Feeds";
export default {
  components: {
    StoriesSection,
    FeedSection,
  },
};
</script>

<style>
</style>