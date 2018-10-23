<template>
  <div :class="style.test">
    test
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style module>
.test {
  background: red;
}
</style>
