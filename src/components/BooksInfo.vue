<script>
export default {
  data() {
    return {
      detailsAreVisible: false,
      book: {
        id: 1,
        title: "El resplandor",
        author: "Stephen King",
        releaseDate: "1997-28-01"
      },
    };
  },
  methods: {
    toggleDetails() {
      this.detailsAreVisible = !this.detailsAreVisible;
    },
  },
 };
</script>

<template>
  <li>
    <h2>{{ book.title }}</h2>

    <button type="button" @click="toggleDetails">
      {{ detailsAreVisible ? "Hide" : "Show" }}
    </button>

    <ul v-if="detailsAreVisible">
      <li><strong>Author: </strong> {{ book.author }}</li>
      <li><strong>Release Date: </strong> {{ book.releaseDate }}</li>
    </ul>
  </li>

</template>