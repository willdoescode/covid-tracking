<script lang="ts">
  let email = '<williamlane923@gmail.com>'
  import github_logo from '../../static/images/logos/github-logo.png'
  import devto_logo from '../../static/images/logos/devto-logo.svg'
  import devpost_log from '../../static/images/logos/devpost-logo.png'
  import Social from '$lib/Social.svelte'
</script>

<div class="about">
  <h1>Written and maintained by William Lane
    <a class="email" target="_blank" href="mailto:williamlane923@gmail.com">{email}</a>
  </h1>
  <div class="socials">
    <Social logo={github_logo} url="https://github.com/willdoescode" />
    <Social logo={devto_logo} url="https://dev.to/willdoescode" />
    <Social logo={devpost_log} url="https://devpost.com/willdoescode" />
  </div>
</div>

<style lang="sass">
  .about
    height: 100vh
    width: 100vw

    display: flex
    justify-content: center
    align-items: center

    flex-direction: column

  .socials
    display: flex

  .email
    text-decoration: none
    color: #64A1A5

    &:hover
      text-underline-color: #64A1A6
      text-decoration: underline
</style>
