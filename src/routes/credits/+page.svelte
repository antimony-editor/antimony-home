<script>
    import Navbar from '$lib/navbar.svelte';
    import Button from '$lib/button.svelte';
</script>

<Navbar />

<main class="credits-container">
        <h1>Credits</h1>
        <p>Antimony is made possible by the work of many volunteers. We want to thank everyone who has contributed to the project.</p>

    <section class="all-sections">
        <h2>Active Contributors</h2>
        <ul class="all-lists">
            <li>
                <img src="https://github.com/Gen1xLol.png" alt="Gen1xLol's avatar">
                <span><a href="https://github.com/Gen1xLol" style="color: white;"><p>Gen1xLol</p></a></span>
            </li>
            <li>
                <img src="https://github.com/thedotun.png" alt="thedotun's avatar">
                <span><a href="https://github.com/thedotun" style="color: white;"><p>thedotun</p></a></span>
            </li>
            <li>
                <img src="https://github.com/UnbraveChimp.png" alt="UnbraveChimp's avatar">
                <span><a href="https://github.com/UnbraveChimp" style="color: white;"><p>UnbraveChimp</p></a></span>
            </li>
            <li>
                <img src="https://github.com/LordCat0.png" alt="LordCat0's avatar">
                <span><a href="https://github.com/LordCat0" style="color: white;"><p>LordCat0</p></a></span>
            </li>
            <li>
                <img src="https://github.com/ddededodediamante.png" alt="ddededodediamante's avatar">
                <span><a href="https://github.com/ddededodediamante" style="color: white;"><p>ddededodediamante</p></a></span>
            </li>
            <li>
                <img src="https://github.com/vedal789.png" alt="vedal789's avatar">
                <span><a href="https://github.com/vedal789" style="color: white;"><p>vedal789</p></a></span>
            </li>
            <li>
                <img src="https://github.com/PuzzlingGGG.png" alt="PuzzlingGGG's avatar">
                <span><a href="https://github.com/PuzzlingGGG" style="color: white;"><p>PuzzlingGGG</p></a></span>
            </li>
        </ul>

        <h2>Server Host</h2>
        <div class="host-text">
            Antimony's Backend API is currently being developed and hosted by <a href="https://github.com/lordcat0" style="color: #86C5DB;">lordcat.</a>
            <n></n>
            <img class="host-pfp" src="https://github.com/lordcat0.png" alt="lordcat0's avatar">
        </div>    
    </section>
</main>

<style>

    .credits-container {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
    }

    .all-sections {
        margin-top: 40px;
        width: 100%;
    }

    .all-lists {
        list-style: none;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
        align-items: center;
    }

    .all-lists li {
        display: flex;
        align-items: center;
        border: 3px solid rgba(59, 56, 202, 0.1);
        padding: 10px 20px;
        border-radius: 12px;
        width: 100%;
        max-width: 350px;
    }

    .all-lists li:hover {
        background: rgba(46, 49, 247, 0.1);
    }

    .all-lists img{
        width: 50px;
        height: 50px;
        border-radius: 50%;
        margin-right: 15px;
        object-fit: cover;
    }

    .all-lists span {
        font-size: 1.1rem;
        font-weight: 500;
    }

    .host-text {
        width: 100%;
        max-width: 800px;
        margin: 0 auto 15px auto;
    }

    .host-pfp {
        display: block;
        margin: 0 auto;
        width: 100px;
        height: 100px;
        object-fit: cover;
    }
</style>