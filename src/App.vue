<template>
  <Header />
  <div class="container"> <!-- mx-autoȘmargin auto on the x axis  -->
    <router-view />
    </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  components: {
    Header,
  },
};
</script>
t
