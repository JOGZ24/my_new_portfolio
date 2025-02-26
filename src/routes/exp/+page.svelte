<script>
  import Experience from "../../components/experience.svelte";

  let TPWorks = [
    "Conception d'un système de gestion des stocks pour une usine de plasturgie",
    "Création d'une API REST en NestJS pour gérer des ressources dynamiques",
    "Développement et optimisation d'une application mobile multiplateforme en Flutter",
    "Mise en place d'un CI/CD avec GitLab pour automatiser les déploiements",
    "Maintenance et ajout de nouvelles fonctionnalités sur des applications web et mobiles",
  ];

  let isecWorks = [
    "Développement Front End avec les templates Django",
    "Développement d'API avec Django REST Framework",
    "Collaboration avec un système de GMAO (Gestion de la Maintenance Assistée par Ordinateur)",
    "Développement d'une application mobile avec React Native",
    "Collaboration autour de la réalité augmentée",
  ];

  let bdeWorks = [
    "Responsable événementiel au BDE Info",
    "Coordination des événements du BDE",
    "Organisation et planification d'activités",
    "Animation et gestion d'événements étudiants",
  ];

  let fnaelWorks = [
    "Développement WordPress",
    "Maintenance de site internet",
    "Gestion de projet",
    "Collaboration interdisciplinaire",
  ];

  let butWorks = [
    "Développement web",
    "Programmation",
    "Manipulation de bases de données",
    "Algorithmique et logique informatique",
  ];
</script>

<div class="introduction">
  <h1>Experiences</h1>
  <p>Voici un aperçu de mes expériences jusqu'à présent :</p>
</div>
<div class="experiences">
  <Experience
    place="Arras"
    job="En cours - Talent Pluriel - Alternant développeur fullstack"
    presentation="
      Actuellement, je suis en alternance chez Talent Pluriel en tant que développeur fullstack. J'ai l'opportunité de travailler sur des projets diversifiés, incluant la création d'une API REST en NestJS pour gérer des ressources dynamiques, le développement d'applications mobiles multiplateformes avec Flutter, ainsi que la mise en place de solutions CI/CD pour automatiser les déploiements avec GitLab. Mon rôle inclut également la maintenance et l'ajout de nouvelles fonctionnalités sur des applications web et mobiles existantes.
    "
    works={TPWorks}
    logoColor="#ba2aa0"
  ></Experience>
  <Experience
    place="IUT A de Lille"
    job="En cours - BUT Informatique - Troisième Année"
    presentation=" En troisième année de BUT Informatique à l'IUT de Lille, je me plonge dans le monde captivant du développement web et de la programmation. Au cours de cette formation enrichissante, j'explore une variété de langages de programmation, perfectionne mes compétences en manipulation de bases de données et affine ma maîtrise de l'algorithmique et de la logique informatique. Animé par la passion de la technologie, je m'efforce de repousser mes limites et de développer des solutions innovantes pour les défis informatiques contemporains."
    works={butWorks}
    logoColor="#4a28e0"
  ></Experience>
  <Experience
    place="Instituto Superior de Engenharia de Coimbra"
    job="Avril 2024 - Juillet 2024 (Full Stack Developper)"
    presentation="Stage de développement web à l'Instituto Superior de Engenharia à Coimbra, Portugal, je participe activement au développement full-stack d'un site web. En collaboration avec une équipe, nous intégrons un système de gestion de la maintenance assistée par ordinateur (CMMS) et explorons les possibilités de réalité augmentée pour enrichir l'expérience utilisateur."
    works={isecWorks}
    logoColor="#b42a21"
  ></Experience>
  <Experience
    place="IUT A de Lille"
    job="2023 - Responsable du pôle évènementiel du Bureau Informatique des Etudiants "
    presentation=" En tant que Responsable du pôle événementiel au Bureau Informatique des Étudiants (BDE Info), j'ai le privilège de coordonner et d'animer les événements qui rythment la vie étudiante. De la planification à l'exécution, mon rôle consiste à orchestrer avec soin une variété d'activités visant à enrichir le quotidien de nos membres. Avec passion et détermination, je m'engage à créer des expériences mémorables et à favoriser un environnement dynamique et convivial au sein de notre communauté étudiante."
    works={bdeWorks}
    logoColor="#b328e0"
  ></Experience>
  <Experience
    place="Fédération Nationale des Associations Etudiantes Linguistes"
    job="Juin 2021 - Septembre 2021 (WordPress Developpeur)"
    presentation=" De juin à septembre 2021 à Lille, j'ai eu l'opportunité de contribuer au maintien et au développement du site internet de la FNAEL. Pendant cette période, j'ai apporté des améliorations fonctionnelles et esthétiques au site, contribuant ainsi à son évolution. "
    works={fnaelWorks}
    logoColor="#45a742"
  ></Experience>
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
