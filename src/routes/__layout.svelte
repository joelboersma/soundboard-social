<script lang="ts">
    import "../app.css";
    import Header from "../components/Header.svelte";
    import Footer from "../components/Footer.svelte";

    document.title = "SoundBoard Social"
</script>

<Header />
<slot />
<Footer />