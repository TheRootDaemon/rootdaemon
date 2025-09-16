<script lang="ts">
    import Icon from "@iconify/svelte";

    type Handle = {
        name: string;
        icon: string;
        link: string;
    };

    const handles: Handle[] = [
        {
            name: "Mail",
            icon: "mdi:email",
            link: "mailto:harshath3018@gmail.com",
        },
        {
            name: "GitHub",
            icon: "mdi:github",
            link: "https://github.com/TheRootDaemon",
        },
        {
            name: "LinkedIn",
            icon: "mdi:linkedin",
            link: "https://www.linkedin.com/in/therootdaemon",
        },
        {
            name: "X",
            icon: "mdi:twitter",
            link: "https://x.com/therootdaemon",
        },
        {
            name: "Instagram",
            icon: "mdi:instagram",
            link: "https://www.instagram.com/therootdaemon",
        },
    ];
</script>

<section class="island">
    {#each handles as { name, icon, link }}
        <a href={link} target="_blank" rel="noopener noreferrer" class="handle"
            ><Icon {icon} width="24" height="24" /></a
        >
    {/each}
</section>
