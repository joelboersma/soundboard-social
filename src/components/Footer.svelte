<script lang="ts">
    const footerLinks = [
        {
            href: '/',
            text: 'SoundBoard Social',
        },
        {
            href: 'https://github.com/joelboersma/',
            text: 'Made by Joel Boersma',
        },
        {
            href: 'https://github.com/joelboersma/soundboard-social',
            text: 'Source',
        },
    ];
</script>

<footer class="bg-orange-600 flex justify-evenly p-4 text-white">
    {#each footerLinks as link}
        <a href={link.href} class="hover:underline">{link.text}</a>
    {/each}
</footer>