<template>
  <main>
    <NativeSwapWidget apiKey="JWL73SF2K899AMPFRHZV" />
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
