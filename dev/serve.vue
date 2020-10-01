<script>
import Vue from "vue";
import { AppButton } from "@/entry";

export default Vue.extend({
  name: "ServeDev",
  components: {
    AppButton,
  },
});
</script>

<template>
  <div id="app">
    <AppButton />
  </div>
</template>
