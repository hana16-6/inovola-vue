<template>
  <div class="header">
    <nav>
      <Navbar />
      <HeroBox />
    </nav>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import HeroBox from "@/components/HeroBox.vue";
export default {
  name: "AppHeader",
  components: {
    Navbar,
    HeroBox,
  },
};
</script>