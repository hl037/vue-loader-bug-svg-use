<template>
  <div>
    <div id="d1">
      <svg>
        <use href="@/assets/logo.svg#logo"></use>
      </svg>
    </div>
    <div id="d2">
      <svg>
        <use href="@/assets/logo.svg#logo"></use>
      </svg>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
});
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

svg {
  height: 100px;
}
</style>
