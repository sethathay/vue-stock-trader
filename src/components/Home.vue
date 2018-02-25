<template>
  <div>
    <h1>Trad or View Your Portfolio</h1>
    <h6>You may save & load your data</h6>
    <h6>Click on 'End Day' to begin a New Day!!!!</h6>
    <hr/>
    <h3>Your Founds : {{ funds | currency }}</h3>
  </div>
</template>
<script>
export default {
  computed: {
    funds () { 
      return this.$store.getters.funds
    }
  }
}
</script>
