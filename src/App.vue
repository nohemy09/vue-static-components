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
          title: "Carrie",
          author: "Stephen King",
          releaseDate: "1974-05-04" 
        },
        {
          id: 3,
          title: "Cujo",
          author: "Stephen King",
          releaseDate: "1981-08-09"
        },
      ],
    };
  },
 };
</script>

<template>
  <h1>My books</h1>
  <ul>
    <book-info
    id ="1" 
    title ="El resplandor"
    author ="Stephen King"
    releaseDate ="1999-29-07"
    is-liked="1"
    ></book-info>
    <book-info
    id ="1" 
    title ="Carrie"
    author ="Stephen King"
    releaseDate ="1984-09-09"
    ></book-info>
    <book-info
    id ="1" 
    title ="Cujo"
    author ="Stephen King"
    releaseDate ="1991-09-09"
    is-liked="1"
    ></book-info>
  </ul>
</template>

<style>
  h1{
    color: crimson;
  }
</style>