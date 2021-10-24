<template>
  <div class="v-m-mini-footer">
    <VButton>
      <span>About us</span>
    </VButton>
    <VButton>
      <span>Support</span>
    </VButton>
    <VButton>
      <span>Press</span>
    </VButton>
    <VButton>
      <span>API</span>
    </VButton>
    <VButton>
      <span>Jobs</span>
    </VButton>
    <VButton>
      <span>Privacy</span>
    </VButton>
    <VButton>
      <span>Terms</span>
    </VButton>
    <VButton>
      <span>Locations</span>
    </VButton>
    <VButton>
      <span>Top Accounts</span>
    </VButton>
    <VButton>
      <span>Hashtags</span>
    </VButton>
    <VButton>
      <span>Language</span>
    </VButton>
    <p>© 2019 INSTAGRAM</p>
  </div>
</template>

<script>

import VButton from '@/components/atoms/VButton'

export default {
  name: "VMiniFooter",
  components: {
    VButton
  }
}
</script>


<style lang="sass">
  .v-m-mini-footer
    line-height: 13px
    span, p
      font-size: 11px
      font-weight: 400
      color: $light-text-color
      &:after
        content: "\00B7"
        margin: 5px
    button:last-child
      span:after
        content: ""
</style>
