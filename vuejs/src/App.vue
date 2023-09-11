<template>
  <main>
    <NativeSwapWidget apiKey="8Y0ZN9X6VF7VW0KMF3P4" />
  </main>
</template>

<script>
import { applyPureReactInVue } from "veaury";
import NativeSwapWidget from "@native_org/widgets";

export default {
  components: { NativeSwapWidget: applyPureReactInVue(NativeSwapWidget) },
};
</script>

<style scoped></style>
