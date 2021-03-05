<template>
  <v-app>
    <v-app-bar app color="primary" dark> </v-app-bar>

    <v-main>
      <v-container>
        <main-header />
        <search-results />
        <movie-details />
        <movie-reviews />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import MainHeader from "./components/MainHeader.vue";
import MovieDetails from "./components/MovieDetails.vue";
import MovieReviews from "./components/MovieReviews.vue";
import SearchResults from "./components/SearchResults.vue";

export default {
  components: { MainHeader, SearchResults, MovieDetails, MovieReviews }
};
</script>
