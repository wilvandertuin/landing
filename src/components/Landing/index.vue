<template>
  <landing-bg>
    <landing-dialog/>
  </landing-bg>
</template>

<script>
import LandingBg from './BG'
import LandingDialog from './Dialog'

export default {
  name: 'Landing',
  components: { LandingBg, LandingDialog }
}
</script>
