<!-- Questo codice importa due componenti Vue: AppTitle e AppHero. -->
<!-- Esporta un oggetto con una proprietà `components` che contiene i due componenti importati. -->
<!-- L'oggetto `components` può essere utilizzato per registrare i componenti globalmente in Vue. -->
<!-- In questo modo, i componenti possono essere utilizzati in qualsiasi punto dell'app. -->
<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default{
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<!-- qui scrivo il codice html generale tramite i componenti creati separatamente -->
<template>

  <div>
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
  
</template>

<style></style>