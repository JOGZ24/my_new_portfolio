<script>
    import Skill from "../components/skill.svelte";
    import { slide } from "svelte/transition";

    let moreSkill = false;

    function changeMoreSkill() {
        moreSkill = !moreSkill;
    }
</script>

<div class="presentation">
    <div in:slide class="presentation__img">
        <img
            src="https://scontent.fopo6-2.fna.fbcdn.net/v/t1.15752-9/426660886_642754561310087_3166163148633590885_n.png?_nc_cat=111&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeE-EoRe96EnqZsAK_UsS_uWin2qQ8fg3DqKfapDx-DcOvj3IphvmACRxqVwVj04SxQoWS6_iCkXgdmprAqQM4En&_nc_ohc=2LZldypesocQ7kNvgF7fCwj&_nc_ht=scontent.fopo6-2.fna&oh=03_Q7cD1QFTY6_grxsMYU6Lk_6ls2bzmcDJWVke1rYusvb3bAHxBQ&oe=66804EE7"
            alt=""
            width="200"
            height="auto"
        />
    </div>
    <div in:slide class="presentation__container">
        <h1 class="presentation__hey">Hey !</h1>
        <h2 class="presentation__name">Je suis Bouin Julien</h2>
        <p class="presentation__text">
            À 19 ans et en 2ème année de BUT Informatique à l'IUT de Lille, je
            mets en œuvre mes compétences dans la création d'applications.
            Actuellement à la recherche d'une alternance pour approfondir mon
            expérience. Explorez mes réalisations et contactez-moi pour discuter
            de collaborations potentielles.
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
            <Skill
                image="https://imgs.search.brave.com/sDXS3IWHlItL53Dwu4oDtG8-5ydhvhQW28ByBeYMru8/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9hc3Nl/dHMuc3RpY2twbmcu/Y29tL2ltYWdlcy81/ODQ4MTUyZmNlZjEw/MTRjMGI1ZTQ5Njcu/cG5n"
                name="Python"
            ></Skill>
            <Skill
                name="Django"
                image="https://imgs.search.brave.com/mpNV_eSe_OP6CPb0QLLDrVn9E4_pFrUAYobiJn9dxgg/rs:fit:860:0:0/g:ce/aHR0cHM6Ly9zdGF0/aWMtMDAuaWNvbmR1/Y2suY29tL2Fzc2V0/cy4wMC9kamFuZ28t/aWNvbi04MDN4MTAy/NC1yemkwM3ZhMC5w/bmc"
            ></Skill>
            <Skill
                name="Java"
                image="https://imgs.search.brave.com/LVuj-1Oe_4XricNqMXDIj9zFJk3_rnWlppC5OqcZlYE/rs:fit:860:0:0/g:ce/aHR0cHM6Ly91eHdp/bmcuY29tL3dwLWNv/bnRlbnQvdGhlbWVz/L3V4d2luZy9kb3du/bG9hZC9icmFuZHMt/YW5kLXNvY2lhbC1t/ZWRpYS9qYXZhLXBy/b2dyYW1taW5nLWxh/bmd1YWdlLWljb24u/cG5n"
            ></Skill>
            {#if moreSkill}
                <Skill
                    name="Javascript"
                    image="https://imgs.search.brave.com/S3poLhf_uSzqM0qqanNsHpMXBMTmBZwN1kto06jaKvE/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9hc3Nl/dHMuc3RpY2twbmcu/Y29tL2ltYWdlcy82/MTNiNjRmZTMwZTg1/MzAwMDRiYTNhMDMu/cG5n"
                ></Skill>
                <Skill
                    name="C"
                    image="https://imgs.search.brave.com/kbIST97wBjybu79oHpie4VbNH6CrI5nfzrMoOAS5OvQ/rs:fit:860:0:0/g:ce/aHR0cHM6Ly91cGxv/YWQud2lraW1lZGlh/Lm9yZy93aWtpcGVk/aWEvY29tbW9ucy8x/LzE4L0NfUHJvZ3Jh/bW1pbmdfTGFuZ3Vh/Z2Uuc3Zn.svg"
                ></Skill>
                <Skill
                    name="SQL"
                    image="https://imgs.search.brave.com/YVyfwwIlAHUZfc-0o8QR8jYSShZW4lCBBZRvfguR9MM/rs:fit:500:0:0/g:ce/aHR0cHM6Ly93d3cu/cG9zdGdyZXNxbC5v/cmcvbWVkaWEvaW1n/L2Fib3V0L3ByZXNz/L2VsZXBoYW50LnBu/Zw"
                ></Skill>
            {/if}
        </div>
    </div>
</div>
<div class="main-content">
    <div class="main-content__intro">
        <h2>Introduction</h2>
        <p>
            Je suis un étudiant en informatique passionné avec une forte
            capacité d'adaptation et un penchant pour les technologies
            innovantes. Fort de plusieurs expériences en développement
            full-stack et d'une implication active dans des projets
            collaboratifs, je cherche à enrichir mon parcours par une alternance
            stimulante dans le domaine du développement logiciel.
        </p>
    </div>
    <div class="main-content__exist">
        <h2>Pourquoi je suis fait pour ce métier</h2>
        <p>
            Je suis profondément passionné par le développement logiciel et
            motivé par la recherche constante de solutions innovantes. Doté d'un
            solide bagage en informatique, je m'efforce continuellement de créer
            des solutions efficaces et élégantes pour répondre aux défis
            complexes du monde numérique. Mon parcours diversifié m'a permis de
            développer des compétences polyvalentes et approfondies, allant de
            la conception de sites web à la gestion de projets.
        </p>
    </div>
    <div class="main-content__education">
        <h2>Mon parcours académique</h2>
        <p>
            Actuellement en deuxième année de BUT Informatique à l'IUT A de
            Lille, j'ai acquis une base solide en programmation et en
            développement de logiciels. Mon stage à l'Instituto Superior de
            Engenharia de Coimbra a renforcé mes compétences en développement
            full-stack et en intégration de nouvelles technologies, ce qui a
            renforcé ma conviction et mon intérêt pour le domaine du
            développement logiciel.
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
