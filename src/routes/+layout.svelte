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

<style>
    .bar {
        height: 3px;
        padding: 0px;
        margin: 0px;
        background-color: #2b2b2b;
    }
</style>