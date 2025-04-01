<template>
  <div>
    <!-- Barra de navegación -->
    <NavBar />

    <!-- Encabezado -->
    <Header />

    <!-- Secciones agrupadas -->
    <Sections />

    <!-- Pie de página -->
    <Footer />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Header from './components/Header.vue';
import Sections from './components/Sections.vue'; // Importa el nuevo componente
import Footer from './components/Footer.vue';

export default {
  components: {
    NavBar,
    Header,
    Sections, // Registra el componente
    Footer
  }
}
</script>

<style>
/* Estilos globales */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

#app {
  width: 100%;
  max-width: 100%;
  overflow-x: hidden; /* Evita el desbordamiento horizontal */
  padding: 0;
}
</style>