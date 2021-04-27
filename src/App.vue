<template>
  <div>
    <h1>{{ title }}</h1>
    <button @click="add">add{{ cnt }}</button>
  </div>
</template>

<script>
export default {
  data: () => ({
    title: "Sssss",
    cnt: 0,
  }),
  methods: {
    add() {
      ++this.cnt;
      console.log(this.cnt);
    },
  },
};
</script>

<style>
</style>