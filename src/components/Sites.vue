<template>
  <div>Client!</div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {
    callClients() {
      fetch("https://tracktik-frontend-challenge-jwidtarfww.now.sh/sites", {
        method: "GET"
      })
        .then(response => response.json())
        .then(json => console.log(json));
    }
  },
  created() {
    // console.log("created! ");
    // this.callClients();
    // console.log("called");
  }
};
</script>


