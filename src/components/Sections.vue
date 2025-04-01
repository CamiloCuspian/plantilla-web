<template>
    <div>
      <!-- Sección de macarons -->
      <section class="macarons">
        <h2>Наборы макарунов</h2>
        <p>Порадуйте себя и своих близких очень вкусными и изысканными макарунами.</p>
        <div class="macaron-set">
          <h3>Набор из четырех макарунов</h3>
          <p>220 арн</p>
        </div>
      </section>
  
      <!-- Sección de pasteles -->
      <section class="cakes">
        <h2>Набор из четырех кексов</h2>
        <p>220 арн</p>
      </section>
  
      <!-- Sección de oferta -->
      <section class="offer">
        <h2>Закажите на сумму 1 200 арн и получите набор макарун в подарок!</h2>
      </section>
  
      <!-- Sección de la tabla -->
      <section class="table">
        <h2>Комбинация</h2>
        <table>
          <thead>
            <tr>
              <th>Блок</th>
              <th>Выйти</th>
              <th>Успехи</th>
              <th>Стоимость</th>
              <th>Количество событий</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>5.00%</td>
              <td>2.00%</td>
              <td>День утра</td>
              <td>Один разный объект</td>
              <td>0,000,000,000</td>
            </tr>
            <tr>
              <td>5.00%</td>
              <td>3.00%</td>
              <td>День утра</td>
              <td>500,000,000,000</td>
              <td></td>
            </tr>
            <tr>
              <td>5.00%</td>
              <td>4.00%</td>
              <td>День утра</td>
              <td>100,000,000,000</td>
              <td></td>
            </tr>
          </tbody>
        </table>
      </section>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Sections'
  }
  </script>
  
  <style scoped>
  /* Estilos para las secciones */
  .macarons {
    padding: 2rem;
    background-color: #fff;
    text-align: center;
  }
  
  .macarons h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
  }
  
  .macarons p {
    font-size: 1.1rem;
    color: #666;
  }
  
  .macaron-set {
    margin-top: 1.5rem;
  }
  
  .macaron-set h3 {
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
  }
  
  .macaron-set p {
    font-size: 1.2rem;
    color: #333;
  }
  
  .cakes {
    padding: 2rem;
    background-color: #f8f8f8;
    text-align: center;
  }
  
  .cakes h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
  }
  
  .cakes p {
    font-size: 1.2rem;
    color: #333;
  }
  
  .offer {
    padding: 2rem;
    background-color: #fff3e0;
    text-align: center;
  }
  
  .offer h2 {
    font-size: 1.8rem;
    color: #333;
  }
  
  .table {
    padding: 2rem;
    background-color: #fff;
    text-align: center;
  }
  
  table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 1rem;
  }
  
  th, td {
    padding: 0.75rem;
    border: 1px solid #ddd;
  }
  
  th {
    background-color: #f8f8f8;
  }
  </style>