<script>

export default {
  name: 'testingSlots',
  components: {
  },
  props: {
  },
  data () {
    return {
    }
  },
  created () {
  },
  computed: {
  },
  methods: {
  }
}

</script>

<template lang="pug">

.root
    slot(name='iconfirst')
    main
    footer
        div 12113
        slot(name='footer')



</template>

<style scoped lang="sass">

</style>
