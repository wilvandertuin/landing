<template>
  <landing-bg>
    <landing-dialog/>
  </landing-bg>
</template>

<script>
import LandingBg from './bg'
import LandingDialog from './dialog'

export default {
  name: 'Landing',
  components: { LandingBg, LandingDialog }
}
</script>
