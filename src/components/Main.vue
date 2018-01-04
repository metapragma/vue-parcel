<template>
  <h1 class="blah">{{ header }}</h1>
</template>

<script>
export default {
  data () {
    return {
      header: 'The build time is ridiculous. HMR is fast.'
    }
  }
}
</script>

<style lang="scss">
@import './index';
</style>