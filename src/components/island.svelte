<script lang="ts">
    type Handle = {
        name: string;
        icon: string;
        link: string;
    };

    const handles: Handle[] = [
        {
            name: "Mail",
            icon: "./mail.svg",
            link: "mailto:harshath3018@gmail.com",
        },
        {
            name: "GitHub",
            icon: "./github.svg",
            link: "https://github.com/TheRootDaemon",
        },
        {
            name: "LinkedIn",
            icon: "./linkedin.svg",
            link: "https://www.linkedin.com/in/therootdaemon",
        },
        {
            name: "X",
            icon: "./x.svg",
            link: "https://www.x.com/therootdaemon",
        },
        {
            name: "Instagram",
            icon: "./instagram.svg",
            link: "https://www.instagram.com/therootdaemon",
        },
    ];
</script>

<section class="social-handles">
    {#each handles as handle}
        <a
            href={handle.link}
            target="_blank"
            rel="noopener noreferrer"
            class="handle-link"
            title={handle.name}
            ><img src={handle.icon} alt={handle.name} class="icon" /></a
        >
    {/each}
</section>

<style>
    .social-handles {
        background-color: white;

        position: fixed;
        bottom: 0px;
        left: 50%;
        transform: translateX(-50%);

        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .social-handles .icon {
        width: 24px;
        height: 24px;
    }
</style>
