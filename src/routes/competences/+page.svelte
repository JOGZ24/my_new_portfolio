<script>
  import Experience from "../../components/experience.svelte";
</script>

<div class="introduction">
  <h1>Compétences</h1>
  <p>Voici un aperçu de mes compétences jusqu'à présent :</p>
</div>
<div class="competences">
  <div class="competence">
    <h2>Java</h2>
    <p>
      Langage orienté objet utilisé pour le développement d'applications
      robustes.
    </p>
  </div>
  <div class="competence">
    <h2>SQL</h2>
    <p>Langage de requête pour manipuler et interroger des bases de données.</p>
  </div>
  <div class="competence">
    <h2>JavaScript</h2>
    <p>
      Langage de programmation essentiel pour le développement web dynamique.
    </p>
  </div>
  <div class="competence">
    <h2>React</h2>
    <p>
      Bibliothèque JavaScript pour créer des interfaces utilisateur
      interactives.
    </p>
  </div>
  <div class="competence">
    <h2>Vue.js</h2>
    <p>
      Framework JavaScript progressif pour construire des interfaces modernes.
    </p>
  </div>
  <div class="competence">
    <h2>Flutter</h2>
    <p>Framework de développement d'applications mobiles multiplateformes.</p>
  </div>
  <div class="competence">
    <h2>C</h2>
    <p>Langage de programmation bas niveau connu pour sa performance.</p>
  </div>
  <div class="competence">
    <h2>Python</h2>
    <p>Langage polyvalent apprécié pour sa simplicité et sa puissance.</p>
  </div>
  <div class="competence">
    <h2>Spring</h2>
    <p>
      Framework Java pour créer des applications web robustes et évolutives.
    </p>
  </div>
  <div class="competence">
    <h2>GitLab CI/CD</h2>
    <p>
      Outil d'intégration et de déploiement continus pour automatiser les
      workflows.
    </p>
  </div>
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

  .competences {
    margin-top: 7%;
    width: 60vw;
  }

  .competence {
    margin-bottom: 2%;
  }

  .competence > h2 {
    font-size: 1.5em;
    font-weight: 500;
  }
  p {
    font-weight: 300;
    opacity: 0.7;
  }
</style>
