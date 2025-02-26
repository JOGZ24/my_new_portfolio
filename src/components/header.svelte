<script>
  export let showProfile;
</script>

<div class="header">
  {#if showProfile == "true"}
    <img
      src="/face.png"
      alt=""
      width="40"
      height="auto"
      class="header__profile-img"
    />
  {/if}
  <nav class="nav">
    <a href="/" alt="">Home</a>
    <a href="/projects" alt="">Projets</a>
    <a href="/competences" alt="">Compétences</a>
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
