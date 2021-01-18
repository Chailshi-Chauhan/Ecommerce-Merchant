<template>
  <div class="home">
    <MerchantLogin></MerchantLogin>
  </div>
</template>

<script>
// @ is an alias to /src
import MerchantLogin from '@/components/MerchantLogin.vue'

export default {
  name: 'Home',
  components: {
    MerchantLogin
  }
}
</script>
<style scoped>

</style>
