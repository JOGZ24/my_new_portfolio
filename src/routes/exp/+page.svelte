<script>
    import Experience from "../../components/experience.svelte";
</script>

<div class="introduction">
    <h1>Experiences</h1>
    <p>
        I have been working as a full-time software developer since 2020, and a
        freelancer since 2018. As I have already indexed by projects, I have
        worked on a variety of projects, ranging from web development, desktop
        application development, and bot development. Here are some of the
        works, I have been involved in.
    </p>
</div>
<div class="experiences">
    <Experience></Experience>
</div>

<style>
    .introduction {
        width: 60vw;
        font-weight: 300;
        font-size: 1.1em;
    }

    .introduction > h1 {
        font-size: 3em;
        font-weight: 600;
    }

    .experiences {
        margin-top: 7%;
        width: 60vw;
    }
</style>
