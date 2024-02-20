<template>
  <div class="main">
    <CardElementVue></CardElementVue>
    <CardElementVue></CardElementVue>
    <CardElementVue></CardElementVue>
    <CardElementVue></CardElementVue>
  </div>
</template>

<script>
// import { ref } from 'vue'

import CardElementVue from '@/components/elements/CardElement.vue'

export default {
  name: 'MainPage',
  components: {
    CardElementVue
  },
  props: {
  },
  setup () {
  }
}
</script>

<style lang="scss" scoped>
.main {
  display: flex;
  justify-content: space-between;
}

</style>
