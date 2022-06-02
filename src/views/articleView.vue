<template>
    <div>
        <v-btn class="ml-2 mb-10" small @click="backToSearchACB">
            Go Back to Search
        </v-btn>
        <iframe src='https://docs.google.com/document/d/1ecIvuirMiP36c72bKzAv_9zk6-ahfHonwPpCvcDwBXg/view?usp=drivesdk '
                frameborder='1'>
        </iframe>
        <iframe width="709" height="399" src="https://www.youtube.com/embed/Cid6ie1pTjY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


    </div>
</template>


<script>
export default {
  data() {
    return {

    };
  },
  components: {
  },

  methods: {
    backToSearchACB: function () {
      //this.$emit("returnToSearch");
    },
  },
};
</script>

