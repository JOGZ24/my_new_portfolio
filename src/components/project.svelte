<script>
    import { fly } from "svelte/transition";

    export let image;
    export let name;
    export let link;
</script>

<div in:fly={{ y: 50, duration: 500 }} class="project">
    <p>{name}</p>
    <a href={link} target="_blank">
        <img
            class="project__image"
            src={image}
            alt=""
            width="250"
            height="auto"
        />
    </a>
</div>

<style>
    .project {
        margin: 20px 8px;
        height: 170px;
    }
    .project:hover {
        transform: scale(1.1) translateZ(50px);
    }
    .project__image {
        border-radius: 10px;
        border: 1px solid black;
        height: 100%;
    }

    .project__image:hover {
        filter: drop-shadow(0 0 0.8mm white);
        transition: 0.3s;
    }

    p {
        opacity: 0.7;
        margin: 0;
        margin-left: 5px;
    }
</style>
