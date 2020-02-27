<template>
  <v-app class="grey lighten-4">
    <Navbar />
    <div class="Dashboard">
      <h1>Dashboard</h1>
    </div>
  </v-app>
</template>

<script>
import Navbar from "@/components/Navbar";

export default {
  name: "Home",
  components: { Navbar }
};
</script>
