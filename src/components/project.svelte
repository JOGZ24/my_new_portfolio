<script>
    import { fly } from "svelte/transition";

    export let image;
</script>

<div in:fly={{ y: 50, duration: 500 }} class="project">
    <img class="project__image" src={image} alt="" width="250" height="auto" />
</div>

<style>
    .project {
        margin: 20px 0;
    }
    .project:hover {
        transform: scale(1.1) translateZ(50px);
    }
    .project__image {
        border-radius: 10px;
        border: 1px solid black;
    }

    .project__image:hover {
        filter: drop-shadow(0 0 0.8mm white);
        transition: 0.3s;
    }
</style>
