<script>
    export let showProfile;
</script>

<div class="header">
    {#if showProfile == "true"}
        <img
            src="https://scontent.fopo6-2.fna.fbcdn.net/v/t1.15752-9/426660886_642754561310087_3166163148633590885_n.png?_nc_cat=111&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeE-EoRe96EnqZsAK_UsS_uWin2qQ8fg3DqKfapDx-DcOvj3IphvmACRxqVwVj04SxQoWS6_iCkXgdmprAqQM4En&_nc_ohc=2LZldypesocQ7kNvgF7fCwj&_nc_ht=scontent.fopo6-2.fna&oh=03_Q7cD1QFTY6_grxsMYU6Lk_6ls2bzmcDJWVke1rYusvb3bAHxBQ&oe=66804EE7"
            alt=""
            width="40"
            height="auto"
            class="header__profile-img"
        />
    {/if}
    <nav class="nav">
        <a href="/" alt="">Home</a>
        <a href="/projects" alt="">Projects</a>
        <a href="/exp" alt="">Experiences</a>
    </nav>
</div>

<style>
    .header {
        position: relative;
        padding-top: 30px;
        margin-bottom: 7%;
        font-size: 1.1em;
        text-align: center;
        align-items: center;
    }

    .header__profile-img {
        position: absolute;
        left: -24%;
        top: 82%;
        transform: translateY(-50%);
        border: 1px solid white;
        border-radius: 10px;
    }

    .nav {
        display: inline-block;
    }

    nav a {
        margin: 0 10px;
        color: white;
        text-decoration: none;
    }

    nav a:hover {
        filter: drop-shadow(0 0 6mm white);
        color: #c5d4de;
        transition: 0.2s;
    }
</style>
