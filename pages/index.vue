<template>
  <Flicking >
    <div class="panel">1</div>
    <div class="panel">2</div>
    <div class="panel">3</div>
  </Flicking>
</template>

<script>
import { Flicking } from "@egjs/vue-flicking";

export default {
  name: 'IndexPage',
  components: {
    Flicking
  }
}
</script>
<style>
.panel {
  width: 200px;
  height: 200px;
}
</style>
