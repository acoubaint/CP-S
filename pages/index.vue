<template>
  <div>
    <navbar/>
    <intro/>
    <location/>
    <features/>
    <promo/>
    <event/>
    <testimony/>
    <faq/>
    <contact/>
    <footers/>
  </div>
</template>

<script>
import Location from '../components/Location.vue'
import Testimony from '../components/Testimony.vue'

export default {
  components: { Location, Testimony },

}
</script>

<style>

</style>
