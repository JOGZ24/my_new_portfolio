<script>
  import Experience from "../../components/experience.svelte";
</script>

<div class="introduction">
  <h1>Compétences</h1>
  <p>Voici un aperçu détaillé de mes compétences :</p>
</div>

<div class="competences">
  <div class="competence">
    <h2>Java</h2>
    <p>
      Java est un langage orienté objet que j'utilise pour développer des
      applications robustes, grâce à sa portabilité et sa structure solide.
    </p>
  </div>

  <div class="competence">
    <h2>SQL</h2>
    <p>
      SQL est essentiel dans mon travail pour manipuler et interroger des bases
      de données relationnelles, assurant une gestion efficace des données.
    </p>
  </div>

  <div class="competence">
    <h2>JavaScript</h2>
    <p>
      JavaScript est au cœur de mes projets de développement web dynamique,
      permettant des interfaces utilisateur interactives et réactives.
    </p>
  </div>

  <div class="competence">
    <h2>React</h2>
    <p>
      React est ma bibliothèque de prédilection pour créer des interfaces
      utilisateur modernes et performantes, facilitant le développement
      d'applications frontales complexes.
    </p>
  </div>

  <div class="competence">
    <h2>Vue.js</h2>
    <p>
      Vue.js est un framework progressif que j'utilise pour sa simplicité et sa
      flexibilité, idéal pour construire des applications web modernes et
      réactives.
    </p>
  </div>

  <div class="competence">
    <h2>Flutter</h2>
    <p>
      Flutter me permet de développer des applications mobiles multiplateformes
      avec une seule base de code, offrant une expérience utilisateur fluide et
      uniforme sur iOS et Android.
    </p>
  </div>

  <div class="competence">
    <h2>C</h2>
    <p>
      C est un langage que je maîtrise pour son efficacité et sa performance
      dans le développement de logiciels bas niveau, idéal pour les systèmes
      embarqués et les applications nécessitant des performances optimales.
    </p>
  </div>

  <div class="competence">
    <h2>Python</h2>
    <p>
      Python est polyvalent et puissant, utilisé pour des applications diverses
      telles que le développement web, l'analyse de données, et l'automatisation
      de tâches grâce à sa syntaxe claire et concise.
    </p>
  </div>

  <div class="competence">
    <h2>Spring</h2>
    <p>
      Spring Framework est essentiel pour le développement d'applications web
      Java robustes et évolutives, offrant des fonctionnalités avancées pour la
      gestion de la sécurité, la gestion des transactions, et bien plus encore.
    </p>
  </div>

  <div class="competence">
    <h2>GitLab CI/CD</h2>
    <p>
      GitLab CI/CD est un outil puissant que j'utilise pour automatiser les
      workflows d'intégration et de déploiement continus, assurant une livraison
      logicielle rapide et fiable.
    </p>
  </div>
</div>

<style>
  .competences {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
  }
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
    margin-right: 30px;
  }

  .competence > h2 {
    font-size: 1.5em;
    font-weight: 500;
  }

  .competence > p {
    font-weight: 300;
    opacity: 0.7;
  }
</style>
