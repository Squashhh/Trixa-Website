<script>
  import TrixaBanner from '/TrixaBanner.png';
  import '$lib/styles/font.css'

  import Connected from '$lib/components/button/connected.svelte';
  import Register from '$lib/components/button/register.svelte';
</script>

<style>
  .button-container {
    position: absolute;
    bottom: 0;
    display: flex;
    justify-content: space-between;
    width: 100%;
  }

  img {
    padding: 0%;
    margin: 0%;
    width: 100%;
  }
</style>

<div class="banner-container">
  <img src={TrixaBanner} alt="TrixaBanner" width="1280" height="720">

  <div class="button-container">
    <div class="register-button">
      <Register />
    </div>
    <div class="connected-button">
      <Connected />
    </div>
  </div>
</div>