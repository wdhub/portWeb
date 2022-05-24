<template>
    <div>
        <v-btn class="ml-2 mb-10" small @click="backToSearchACB">
            Go Back to Search
        </v-btn>
        <v-card>
           <v-card-text v-if="trailInfo.longText">
               <h2>The Route Details</h2>
               <br />
               <LazyYoutube src="https://youtu.be/OLPuiWl9d8g" />
           </v-card-text>
        </v-card>


                
    </div>
</template>


<script>
import LazyYoutube from 'vue-lazytube'
export default {
  data() {
    return {

    };
  },
  components: {
      LazyYoutube,
  },

  methods: {
    backToSearchACB: function () {
      //this.$emit("returnToSearch");
    },
  },
};
</script>

