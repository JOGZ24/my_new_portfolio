<script>
    import Skill from "../components/skill.svelte";

    let moreSkill = false;

    function changeMoreSkill() {
        moreSkill = !moreSkill;
    }
</script>

<div class="presentation">
    <div class="presentation__img">
        <img
            src="https://scontent.fopo6-2.fna.fbcdn.net/v/t1.15752-9/426660886_642754561310087_3166163148633590885_n.png?_nc_cat=111&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeE-EoRe96EnqZsAK_UsS_uWin2qQ8fg3DqKfapDx-DcOvj3IphvmACRxqVwVj04SxQoWS6_iCkXgdmprAqQM4En&_nc_ohc=2LZldypesocQ7kNvgF7fCwj&_nc_ht=scontent.fopo6-2.fna&oh=03_Q7cD1QFTY6_grxsMYU6Lk_6ls2bzmcDJWVke1rYusvb3bAHxBQ&oe=66804EE7"
            alt=""
            width="200"
            height="auto"
        />
    </div>
    <div class="presentation__container">
        <h1 class="presentation__hey">Hey !</h1>
        <h2 class="presentation__name">I'm Bouin Julien</h2>
        <p class="presentation__text">
            A Full-Stack Web developer doing Django Python, Svelte/Kit, Ruby on
            Rails, React.js & Next JS. I love to develop things, I'd rather say
            I am addicted to development and coding.
        </p>
        <div class="skills">
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <!-- svelte-ignore a11y-no-noninteractive-element-interactions -->
            <p class="skills__show-more" on:click={changeMoreSkill}>
                {#if moreSkill}
                    Show less
                {:else}
                    Show more
                {/if}
            </p>
            <Skill name="Python"></Skill>
            <Skill name="Django"></Skill>
            <Skill name="Java"></Skill>
            {#if moreSkill}
                <Skill name="Javascript"></Skill>
                <Skill name="C"></Skill>
                <Skill name="SQL"></Skill>
            {/if}
        </div>
    </div>
</div>
<div class="main-content">
    <div class="main-content__intro">
        <h2>Intro</h2>
        <p>
            I'm a software engineer with 5 years of experience. I design and
            developI'm a software engineer with 5 years of experience. I design
            and developI'm a software engineer with 5 years of experience. I
            design and develop I'm a software engineer with 5 years of
            experience. I design and developI'm a software engineer with 5 years
            of experience. I design and developI'm a software engineer with 5
            years of experience. I design and develop
        </p>
    </div>
    <div class="main-content__exist">
        <h2>Why I Exist?</h2>
        <p>
            I'm a software engineer with 5 years of experience. I design and
            developI'm a software engineer with 5 years of experience. I design
            and developI'm a software engineer with 5 years of experience. I
            design and develop I'm a software engineer with 5 years of
            experience. Ip
        </p>
    </div>
    <div class="main-content__education">
        <h2>Am I really educated?</h2>
        <p>
            I'm a software engineer with 5 years of experience. I design and
            developI'm a software engineer with 5 years of experience. I design
            and developI'm a software engineer with 5 years of experience. I
            design and develop I'm a software engineer with 5 years of
            experience. I design angineer with 5 years of experience. I design
            and develop
        </p>
    </div>
</div>

<style>
    .presentation__text {
        font-size: 1.4em;
    }
    .presentation__container {
        width: 50vw;
        margin-left: 10px;
        font-weight: 300;
    }

    .main-content {
        font-weight: 250;
        width: 70vw;
        font-size: 1.2em;
    }

    .main-content h2 {
        font-weight: 350;
    }

    .presentation__hey {
        font-size: 4.7em;
        margin: 0;
    }

    .presentation__name {
        font-size: 2.8em;
        margin: 0;
        font-weight: 400;
    }

    .presentation {
        display: flex;
    }

    .presentation__img {
        margin-right: 20px;
        margin-top: 18px;
    }

    .presentation__img > img {
        border: 1px solid white;
        border-radius: 10px;
    }

    .skills {
        display: flex;
        align-items: center;
    }

    .skills > p {
        font-weight: 400;
        margin-left: 10px;
    }
    .skills {
        display: flex;
        align-items: center;
        flex-wrap: wrap;
        gap: 5px;
    }
</style>
