<script>
    import { fade } from "svelte/transition";
    export let name;
</script>

<div transition:fade={{ y: 50, duration: 100 }} class="badge">{name}</div>

<style>
    .badge {
        border: 1px solid #a8a29d;
        color: #a8a29d;
        width: min-content;
        height: min-content;
        padding: 5px 14px;
        border-radius: 7px;
        margin: 0 7px;
    }

    .badge:hover {
        background-color: rgba(218, 165, 32, 0.4);
        border: 1px solid rgba(218, 165, 32, 0.8);
        color: white;
    }
</style>
