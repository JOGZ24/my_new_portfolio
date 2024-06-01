<script>
    import { fade } from "svelte/transition";
    export let name;
    export let logo;
</script>

<div transition:fade={{ y: 50, duration: 100 }} class="skill">
    <p>{name}</p>
    <img
        src="https://imgs.search.brave.com/sDXS3IWHlItL53Dwu4oDtG8-5ydhvhQW28ByBeYMru8/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9hc3Nl/dHMuc3RpY2twbmcu/Y29tL2ltYWdlcy81/ODQ4MTUyZmNlZjEw/MTRjMGI1ZTQ5Njcu/cG5n"
        alt=""
        width="auto"
        height="20"
    />
</div>

<style>
    .skill {
        border: 1px solid #a8a29d;
        color: #a8a29d;
        width: min-content;
        height: min-content;
        padding: 5px 14px;
        border-radius: 7px;
        margin: 0 7px;
        display: flex;
    }

    .skill:hover {
        background-color: rgba(218, 165, 32, 0.4);
        border: 1px solid rgba(218, 165, 32, 0.8);
        color: white;
    }
    p {
        margin: 0;
    }

    img {
        margin: 0;
        margin-left: 8px;
    }
</style>
