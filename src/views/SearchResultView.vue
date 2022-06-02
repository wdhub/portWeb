<template>
    <div>
        <v-btn class="ml-2 mb-10" small @click="searchACB">
            Search
        </v-btn>
        <div class="col-sm-12 col-md-4 col card-layout"
             v-for="(fileID, idx) in fileIDs"
             :key="idx">
            {{fileID}}
        </div>
    </div>
</template>

<script>
export default {
  components: {},
  name: "SearchResultView",
  props: {
    fileIDs: Array,
  },
  methods: {
   searchACB() {
          this.$emit("searchFile");
          console.log("view search function done");
    },
  },
};
</script>