<script>
    import NavBar from '$lib/components/navbar/navbar.svelte';
    import Banner from '$lib/components/navbar/banner.svelte';
    import Article from '$lib/components/article.svelte';
    import Creators from '$lib/components/creators.svelte';
    import Footers from '$lib/components/footers.svelte';
</script>

<NavBar/>
<div class="bar"></div>
<Banner/>
<div class="bar"></div>
<Article/>
<div class="bar"></div>
<Creators/>
<div class="bar"></div>
<Footers/>

<style>
    .bar {
        height: 3px;
        background-color: #D9D9D9;
    }
</style>