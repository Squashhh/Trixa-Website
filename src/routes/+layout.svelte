<script>
    import NavBar from '$lib/components/navbar.svelte';
    import Banner from '$lib/components/banner.svelte';
    import Faq from '$lib/components/faq.svelte';
    import Trust from '$lib/components/trust.svelte';
    import Footer from '$lib/components/footer.svelte';
</script>

<NavBar/>
<div class="bar"></div>
<Banner/>
<div class="bar"></div>
<Faq/>
<div class="bar"></div>    
<Trust/>
<div class="bar"></div>    
<Footer/>

<svelte:head>
	<title>Trixa - Accueil</title>
	<meta name="description" content="Créé en 2021, Trixa est un serveur PvP-Faction sur le thème magique. Farm2Win, il est exclusivement disponible sur la version Minecraft Bedrock !" />
	<meta content="#332573" data-react-helmet="true" name="theme-color"/>
	<meta property="og:image" content="https://media.discordapp.net/attachments/947125715713802251/1114937754736935085/Trixa.png?width=468&height=468" />
</svelte:head>

<style>
    .bar {
        height: 3px;
        padding: 0px;
        margin: 0px;
        background-color: #2b2b2b;
    }
</style>