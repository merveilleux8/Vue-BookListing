<template>
  <div>
    <h1>{{ title }}</h1>
  </div></template
>

<script>
export default {
  name: "Booklist",
  data() {
    return {
      title: "All Books"
    };
  }
};
</script>

<style scoped>
h1,
h2 {
  font-weight: normal;
}
</style>
