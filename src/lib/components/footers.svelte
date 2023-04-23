<script>
  import '$lib/styles/font.css'
  import BlackAndWhiteTitle from '/TrixaTitleBlackAndWhite.png';

  import Instagram from '$lib/components/button/instagram.svelte';
  import Twitter from '$lib/components/button/twitter.svelte';
  import Discord from '$lib/components/button/discord.svelte';
  import Github from '$lib/components/button/github.svelte';
</script>

<body>
  <ul>
    <img src={BlackAndWhiteTitle} alt="BlackAndWhiteTitle" width="300" height= 118>
    <h1>2023 - Tous droits réservés</h1>
    <h2>Made with ❤ by Squashhh</h2>
    <h3>Nous rejoindres :</h3>

    <Github/>
    <Instagram/>
    <Twitter/>
    <Discord/>
  </ul>

  <style>

    img {
      margin: 75px;
    }

    h1 {
        font-family: "Inter";
        text-align: start;
        color: #ffffff;
    }

    h2 {
        font-family: "Inter";
        text-align: start;
        color: #ffffff;
    }

    h3 {
        font-family: "Inter";
        text-align: start;
        color: #ffffff;
    }

    ul {
        margin: 0px;
        padding: 0px;
        background: linear-gradient(70deg, #0B0B0B, #181818);
        height: 250px;
        display: flex;
        align-items: center;
    }
  </style>
</body>