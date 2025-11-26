 <template>
 <header class="menu-fixe"> <!-- "Header fixe avec logo et navigation" -->
    <h1 class="logo">Faica<span>Malagouene</span></h1> <!-- "Logo textuel" -->

    <!-- Checkbox cachée pour contrôler le burger -->
    <input type="checkbox" id="burger-toggle" class="burger-toggle" /> <!-- "Case à cocher cachée" -->

    <!-- Bouton burger -->
    <label for="burger-toggle" class="burger"> <!-- "Bouton burger cliquable" -->
      <span class="bar"></span> <!-- "Première barre du burger" -->
      <span class="bar"></span> <!-- "Deuxième barre du burger" -->
      <span class="bar"></span> <!-- "Troisième barre du burger" -->
    </label>

    <ul class="nav-links"> <!-- "Menu de navigation" -->
      <li><a href="#a-propos">À propos</a></li>
      <li><a href="#softskills">Soft Skills</a></li>
      <li><a href="#competences">Compétences</a></li>
      <li><a href="#technologies">Technologies</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </header>
  </template>