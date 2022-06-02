<template>
    <search-result-view :fileIDs="this.$store.getFileIDs" @searchFile="onSearch"/>
</template>

<script>
    import SearchResultView from "../views/SearchResultView.vue";

export default {
  components: { SearchResultView },
  data() {
      return {
          fileIDs: Array,
      };
        },


  methods: {
    onSearch: function () {
      //console.log("onAddToFav " + trail);
      this.$store.commit("setFileIDs");
    },
  },
};
</script>
