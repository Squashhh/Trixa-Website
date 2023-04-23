<script>
    import Offline from '/Offline.png';
    import '$lib/styles/font.css'
</script>

<ul style="display: flex; align-items: center;">
    <img src={Offline} alt="Online" width="30" height="30">
    <div style="display: flex; flex-direction: column; justify-content: center;">
        <h1>HORS LIGNE</h1>
        <h2>0 joueur connecté...</h2>
    </div>
</ul>
  
<style>
  
    img {
        margin: 25px;
    }

    h1 {
        margin: 0;
        font-size: 20px;
        font-family: "Inter";
        text-align: start;
        color: #ffffff;
    }

    h2 {
        margin: 0;
        font-size: 19px;
        font-family: "Inter";
        text-align: start;
        color: #8a8a8a;
    }
  
    ul {
        margin: 25px;
        height: 95px;
        width: 310px;
        background-color: #0B0B0B;
        border-radius: 25px;
        opacity: 90%;
    } 
</style>