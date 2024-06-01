<!-- src/routes/+layout.svelte -->
<script>
    // Aucun script nécessaire pour cette tâche

    import Header from "../components/header.svelte";

    import { page } from "$app/stores";

    // Pour accéder aux informations de la page actuelle
    $: currentPage = $page.url.pathname;
</script>

<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
    href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap"
    rel="stylesheet"
/>

<body>
    <div class="container">
        {#if currentPage == "/"}
            <Header showProfile="false"></Header>
        {:else}
            <Header showProfile="true"></Header>
        {/if}
        <div class="content">
            <slot />
        </div>
    </div>
</body>

<style global>
    body {
        background-color: #0d101f;
        color: white;
        display: flex;
        justify-content: center;

        font-family: "Lato", sans-serif;
    }
</style>
