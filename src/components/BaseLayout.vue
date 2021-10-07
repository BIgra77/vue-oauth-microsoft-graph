<template>
  <div>
    <slot>
      <base-header>
        <h2>Welcome into our <strong>TP3</strong></h2>
      </base-header>
      <home-page />
      <base-footer>
        Site design / logo © 2021 Vallmajo Inc; user contributions licensed under cc by-sa. rev 2021.10.1.999999999
      </base-footer>
    </slot>
  </div>

</template>
<script>
export default {
  name: "BaseLayout"
}
</script>
<style scoped>
</style>