<template>
  <v-app>

      <div id="appBar">

        <div id="logo"></div>

        <div class="rightSide">

          <!-- <div class="userBox" id="myBids" >Your Bids</div> -->

          <!-- <v-btn class="userBox" id="signUp">Sign Up</v-btn> -->

          <v-btn  tile color="indigo" dark>Your Bids</v-btn>

          <v-btn class="mx-2" fab dark color="red">
            <span id="userButton">MD</span>
          </v-btn>

        </div>

      </div>

</v-app>
</template>

<style>
  @import './assets/appbar.css';
</style>

<script>

export default {
  name: "App",

  components: {
  },

  data: () => ({
    //
  })
};
</script>
