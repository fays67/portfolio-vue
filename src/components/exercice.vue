<template>
  <div>
    <h1>{{ message }}</h1>
    <button type="button" @click="afficherMessage">Afficher dans console</button>
  </div>
</template>

<script>
export default {
  name: 'MonComposant',
  data() {
    return {
      message: 'Hello depuis Vue SFC !'
    };
  },
  methods: {
    afficherMessage() {
      console.log('afficherMessage() appelé — message =', this.message);
    }
  }
};
</script>
Puis assure-toi de monter/afficher ce composant dans App.vue ou de l’utiliser dans le router.

4) Version Composition API (si tu utilises setup)
vue
Copier le code
<template>
  <div>
    <h1>{{ message }}</h1>
    <button type="button" @click="afficherMessage">Afficher dans console</button>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const message = ref('Hello depuis Composition API !');

function afficherMessage() {
  console.log('afficherMessage() appelé — message =', message.value);
}
</script>

