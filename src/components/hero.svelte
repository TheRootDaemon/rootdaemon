<section class="hero">
    <div><p id="whoami">Harshavardhan, aka The Root Daemon</p></div>
    <div id="man">
        <p>Developer, obsessed with clean workflows and cleaner code.</p>
    </div>
    <div id="daemon"><p>Oh, let’s talk about Root Daemons...</p></div>
    <div id="desc">
        <p>Root Daemons are Privileged processes running in the Shadows...</p>
        <p>
            Those Daemons has Absolute Powers of course with Responsibilities...
        </p>
    </div>
</section>

<style>
    p {
        margin: 0;
        font-weight: bold;
    }

    .hero {
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        align-items: left;
        font-family: Outfit;
        background-color: white;
        width: clamp(10vw, 90%, 1100px);
        margin-inline: auto;
        gap: clamp(0.5rem, 2vw, 1rem);
    }

    .hero {
        flex: 1 1 auto;
    }

    #whoami {
        font-size: clamp(1.5rem, 4vw, 2.5rem);
    }

    #man {
        font-size: clamp(1.2rem, 3.5vw, 2rem);
    }

    #daemon {
        font-family: Poppins;
        font-size: clamp(1rem, 3vw, 1.7rem);
    }

    #desc {
        font-family: Poppins;
        font-size: clamp(0.9rem, 2.5vw, 1.4rem);
    }
</style>
