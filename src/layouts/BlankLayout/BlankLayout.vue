<template>
  <div class="blank-layout">
    <slot/>
  </div>
</template>

<script>
export default {
  name: 'blank-layout'
}
</script>

<style lang="scss" scoped>
.blank-layout {
  width: 100%;
  height: 100%;
}
</style>
