<template>
    <nav>
      <div class="logo">Subset Delivery</div>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Productos</a></li>
        <li><a href="#">Ofertas</a></li>
        <li><a href="#">Contacto</a></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'NavBar'
  }
  </script>
  
  <style scoped>
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    background-color: #6D2323; /* Fondo blanco */
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1); /* Sombra suave */
    position: sticky; /* Hace que el nav sea pegajoso */
    top: 0; /* Lo fija en la parte superior */
    z-index: 1000; /* Asegura que esté por encima de otros elementos */
  }
  
  .logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: #222; /* Color del texto del logo */
  }
  
  ul {
    list-style: none;
    display: flex;
    gap: 1.5rem; /* Espacio entre los elementos del menú */
    margin: 0;
    padding: 0;
  }
  
  ul li a {
    text-decoration: none;
    color: #555; /* Color del texto del menú */
    font-weight: 500;
    transition: color 0.3s ease; /* Transición suave para el hover */
  }
  
  ul li a:hover {
    color: #000; /* Color al pasar el mouse */
  }
  </style>