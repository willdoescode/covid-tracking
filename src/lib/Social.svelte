<script lang="ts">
  export let logo: string
  export let url: string
</script>

<a target="_blank" href={url}>
  <img src={logo} alt={logo}>
</a>

<style lang="sass">
  a
    margin: 1em
  img
    width: 5em
</style>
