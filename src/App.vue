<script>
 export default {
  data() {
    return {
      book: [
        {
          id: 1,
          title: "El resplandor",
          author: "Stephen King",
          releaseDate: "1997-28-01"
        },
        {
          id: 2,
          title: "El resplandor 2",
          author: "Stephen King",
          releaseDate: "1997-28-01" 
        },
        {
          id: 3,
          title: "El resplandor 3",
          author: "Stephen King",
          releaseDate: "1997-28-01"
        },
      ],
    };
  },
 };
</script>

<template>
  <h1>My books</h1>
  <ul>
    <book-info></book-info>
    <book-info></book-info>
    <book-info></book-info>
  </ul>
</template>

<style>
  h1{
    color: crimson;
  }
</style>