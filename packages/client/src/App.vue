<template>
  <div>
    <h1>
      Hello Vue!
    </h1>
    <div>
      {{ hello }}
    </div>
  </div>
</template>

<script>
import { HELLO } from '@yarn-workspaces-ex/common';

export default {
  data() {
    return {
      hello: HELLO,
    };
  },
};
</script>

<style>

</style>
