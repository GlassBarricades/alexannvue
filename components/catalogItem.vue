<template>
  <v-card max-width="450" class="mx-auto" elevation="1">
    <v-img
      class="white--text align-end"
      height="200px"
      src="pexels-moose-photos-1036641.jpg"
    >
    </v-img>
    <v-card-text
      class="title font-weight-bold mt-3 pb-0 text--primary"
      style="line-height: 1.8rem"
    >
      Check out the new mansion we got for our eSports team!
    </v-card-text>
    <v-card-text class="text--primary">
      An online streamer, also known as a live streamer, internet streamer, or
      streamer, is a person who broadcasts themself online through a live stream
      or pre-recorded video. The scope of online streamers has grown to
      includ...
      <v-btn href="#" small text color="primary">Read More</v-btn>
    </v-card-text>

    <v-card-actions>
      <v-btn icon color="yellow darken-1"><v-icon>mdi-comment</v-icon></v-btn>
      <span class="text--disabled">15</span>
      <v-spacer></v-spacer>
      <v-btn icon color="orange"> <v-icon>mdi-heart</v-icon> </v-btn
      ><span class="text--disabled mr-2">45K</span>
      <v-btn icon color="primary"> <v-icon>mdi-share-variant</v-icon> </v-btn
      ><span class="text--disabled">25K</span>
      <span class="mr-4"></span>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {
  data() {
    return {}
  },
}
</script>
