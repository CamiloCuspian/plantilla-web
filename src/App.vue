<template>
  <div class="landing-page">
    <header>
      <h1>Bienvenido a Mi Landing Page</h1>
      <p>Esta es una página de aterrizaje simple creada con Vue y Vite.</p>
    </header>

    <section class="features">
      <h2>Características</h2>
      <ul>
        <li>Rápida y ligera</li>
        <li>Fácil de personalizar</li>
        <li>Diseño responsivo</li>
      </ul>
    </section>

    <section class="cta">
      <h2>¿Listo para empezar?</h2>
      <button @click="showAlert">¡Regístrate Ahora!</button>
    </section>
  </div>
</template>

<script>
export default {
  methods: {
    showAlert() {
      alert('¡Gracias por registrarte!');
    }
  }
}
</script>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

.landing-page {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  text-align: center;
}

header {
  margin-bottom: 40px;
}

header h1 {
  font-size: 2.5em;
  color: #333;
}

header p {
  font-size: 1.2em;
  color: #666;
}

.features {
  margin-bottom: 40px;
}

.features h2 {
  font-size: 2em;
  color: #333;
}

.features ul {
  list-style-type: none;
  padding: 0;
}

.features li {
  font-size: 1.1em;
  color: #555;
  margin: 10px 0;
}

.cta {
  margin-bottom: 40px;
}

.cta h2 {
  font-size: 2em;
  color: #333;
}

.cta button {
  padding: 10px 20px;
  font-size: 1.2em;
  color: #fff;
  background-color: #007BFF;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.cta button:hover {
  background-color: #0056b3;
}
</style>