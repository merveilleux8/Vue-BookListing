<template>
  <div class="unordered-list">
    <h1>{{ title }}</h1>
    <li v-for="book in books">{{book.title}}:{{book.author}}</li>
  </div>
</template
>

<script>
export default {
  name: "Booklist",
  data() {
    return {
      title: "All Books",
      books: [
        { title: "Self-Reliance", author: "Ralph Waldo Emerson" },
        { title: "American Gods", author: "Neil Gaiman" },
        { title: "Amusing Ourselves to Death", author: "Neil Postman" }
      ]
    };
  }
};
</script>

<style scoped>
h1,
h2 {
  font-weight: normal;
}
.unordered-list {
  list-style-type: none;
  padding: 0;
}
li {
  display: block;
  margin: 0 10px;
}
</style>
