<template>
  <div class="portfolio">

    <!-- Code HTML du portfolio -->
    

<main> <!-- "Contenu principal du portfolio" -->

    <!-- ===== SECTION ACCUEIL ===== -->
    <section class="hero"> <!-- "Section d'accueil avec texte et image" -->
      <div class="hero-text"> <!-- "Bloc de texte de présentation" -->
        <h2>Salut, je suis <span>Malagouene Faical</span></h2> <!-- "Titre de bienvenue avec mise en valeur du nom" -->
        <p>Étudiant en BTS SIO passionné par l’informatique, le code et la créativité. J’aime transformer des idées en
          projets concrets.</p> <!-- "Paragraphe d'introduction" -->
        <a href="#contact" class="btn">Me contacter</a> <!-- "Bouton pour accéder à la section contact" -->
      </div>
      <div class="hero-img"> <!-- "Bloc contenant l'image de présentation" -->
        <img :src="informatique" alt="Illustration informatique">
        <!-- "Image d'illustration de la section accueil" -->
      </div>
    </section>

    <!-- ===== À PROPOS ===== -->
    <section id="a-propos" class="section two-cols"> <!-- "Section À propos avec deux colonnes" -->
      <div class="col"> <!-- "Colonne gauche avec image" -->
        <img :src="violet" alt="Illustration profil développeur"> <!-- "Image du profil développeur" -->
      </div>
      <div class="col"> <!-- "Colonne droite avec texte" -->
        <h2>À propos de moi</h2> <!-- "Titre de la section" -->
        <p>Je m'appelle <strong>Malagouene Faical</strong>, étudiant en <strong>BTS SIO</strong>. Passionné par
          l’informatique et le développement, j’aime apprendre de nouvelles technologies et créer des projets
          personnels. Mon objectif : devenir un développeur complet et polyvalent.</p>
        <!-- "Paragraphe de présentation" -->
      </div>
    </section>

    <!-- ===== SOFT SKILLS ===== -->
    <section id="softskills" class="section bg-gradient"> <!-- "Section Soft Skills avec fond dégradé" -->
      <h2>Soft Skills</h2> <!-- "Titre de la section" -->
      <div class="skills-grid"> <!-- "Grille des compétences humaines" -->
        <div class="skill">Travail en équipe</div> <!-- "Compétence 1" -->
        <div class="skill">Communication claire</div> <!-- "Compétence 2" -->
        <div class="skill">Curiosité et apprentissage</div> <!-- "Compétence 3" -->
        <div class="skill">Gestion du temps</div> <!-- "Compétence 4" -->
      </div>
      <div class="social-links"> <!-- "Liens vers réseaux sociaux" -->
        <a href="https://www.linkedin.com/in/faical-malagouene-2ab42738a/" target="_blank"> <!-- "Lien LinkedIn" -->
          <img :src="linkedinImg" alt="Image dynamique" />

        </a>
        <a href="#" target="_blank"> <!-- "Lien GitHub (à compléter)" -->
          <img :src="github" alt="GitHub" class="social-icon"> <!-- "Icône GitHub" -->
        </a>
      </div>
    </section>

    <!-- ===== COMPÉTENCES ===== -->
    <section id="competences" class="section"> <!-- "Section Compétences techniques" -->
      <h2>Compétences techniques</h2> <!-- "Titre de la section" -->
      <p class="competence-intro">Voici les technologies et langages que j’utilise le plus souvent :</p>
      <!-- "Introduction des compétences" -->

      <div class="competence-logos"> <!-- "Grille des logos des technologies" -->
        <div class="logo-item"> <!-- "Bloc d'une technologie" -->
          <img :src="html" alt="Logo HTML"> <!-- "Logo HTML" -->
          <span>HTML</span> <!-- "Nom de la technologie" -->
        </div>
        <div class="logo-item">
          <img :src="css" alt="Logo CSS">
          <span>CSS</span>
        </div>
        <div class="logo-item">
          <img :src="python" alt="Logo Python">
          <span>Python</span>
        </div>
        <div class="logo-item">
          <img :src="SQl" alt="Logo SQL">
          <span>SQL</span>
        </div>
      </div>
    </section>

    <!-- ===== TECHNOLOGIES ===== -->
    <section id="technologies" class="section bg-dark"> <!-- "Section Technologies avec fond sombre" -->
      <h2>Technologies</h2>
      <p>HTML • CSS • Python • SQL • GitHub • VS Code</p> <!-- "Liste des technologies" -->
    </section>

    <!-- ===== CONTACT ===== -->
    <section id="contact" class="section two-cols"> <!-- "Section contact avec deux colonnes" -->
      <div class="col"> <!-- "Colonne texte" -->
        <h2>Contact</h2>
        <p>Tu veux collaborer ou en savoir plus ?</p>
        <p class="email">
          <a href="mailto:faicalmalagouene@gmail.com">faicalmalagouene@gmail.com</a> <!-- "Lien mail direct" -->
        </p>
        <p>
          <a href="https://mail.google.com/mail/?view=cm&to=faicalmalagouene@gmail.com" class="btn-secondary"
            target="_blank">
            M’écrire via Gmail
          </a> <!-- "Lien pour ouvrir Gmail" -->
        </p>
      </div>
      <div class="col"> <!-- "Colonne image" -->
          <img :src="bleu" alt="Image informaitque bleu" />
      </div>
    </section>

  </main>

  
  </div>
</template>

<script>
import bleu from '@/Asset/bleu.jpeg';
import linkedinImg from '@/Asset/linkedin.jpeg';
import githubImg from '@/Asset/github.jpeg';
import cssImg from '@/Asset/css.jpeg';
import python from '@/Asset/python.jpeg';
import violet from '@/Asset/violet.jpeg';
import informatique from '@/Asset/informatique.jpeg';
import violett from '@/Asset/violett.jpeg';



export default {
  name: "Portfolio",
};
</script>

<style scoped>
/* ===== RESET & BASE ===== */

/* Code CSS du portfolio */
</style>