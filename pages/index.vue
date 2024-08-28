<template>
  <Tutorial />
</template>

<script lang="ts">
import Vue from "vue";
import { ofetch } from "ofetch";

export default defineComponent({
  name: "IndexPage",
  mounted() {
    ofetch("/")
  },
});
</script>
