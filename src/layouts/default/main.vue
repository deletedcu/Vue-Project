<template lang="pug">
  v-app.my-default-layout
    //- app-sidebar
    //- app-bar
    v-content(style="padding-top: 48px;")
      transition(name="slide" mode="out-in")
        router-view
    //- app-footer
    //- app-dialog
    //- app-snackbar
</template>

<script>
export default {
  name: 'DefaultLayout',

  components: {  },

  methods: {

  }
}
</script>

<style lang="stylus">

</style>
