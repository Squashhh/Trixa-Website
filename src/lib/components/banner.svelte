<script>
  import Connected from '$lib/components/elements/connected.svelte';
  import Register from '$lib/components/elements/register.svelte';
</script>

<style>
  .banner-container {
    position: relative;
    width: 100%; /* Définissez la largeur du conteneur sur 100% */
    overflow: hidden; /* Ajoutez un overflow: hidden; pour cacher le débordement des éléments positionnés absolument */
  }

  img {
    padding: 0;
    margin: 0;
    width: 100%;
    display: block;
  }

  .button-container {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    padding: 0 20px;
    box-sizing: border-box;
  }
</style>

<div class="banner-container">
  <img src='/TrixaBanner.png' alt="TrixaBanner">

  <div class="button-container">
    <Register />
    <Connected />
  </div>
</div>