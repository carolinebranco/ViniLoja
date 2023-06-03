<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Loja de Artigos para Carro</title>
  <link rel="stylesheet" type="text/css" href="style.css">
  <link rel="stylesheet" type="text/css" href="slick.css">
  <script src="script.js" defer></script>
  <script src="slick.min.js"></script>
</head>
<body>
  <header>
    <h1>Loja de Artigos para Carro</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Contato</a></li>
        <li><a href="#" id="cart-link">Meu Carrinho (0)</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <!-- Seu conteúdo principal da loja aqui --> 
    <div class="product">
      <h2>Produto 1</h2>
      <div class="product-photos">
        <div class="carousel">
          <img src="foto1_1.jpg" alt="Foto 1">
          <img src="foto1_2.jpg" alt="Foto 2">
          <img src="foto1_3.jpg" alt="Foto 3">
        </div>
      </div>
      <p>Descrição do produto 1</p>
      <button class="add-to-cart-button" data-product="1">Adicionar ao carrinho</button>
    </div>
    <div class="product">
      <h2>Produto 2</h2>
      <div class="product-photos">
        <div class="carousel">
          <img src="foto2_1.jpg" alt="Foto 1">
          <img src="foto2_2.jpg" alt="Foto 2">
          <img src="foto2_3.jpg" alt="Foto 3">
        </div>
      </div>
      <button class="add-to-cart-button" data-product="2">Adicionar ao carrinho</button>
    </div>
    <div class="product">
      <h2>Produto 3</h2>
      <div class="product-photos">
        <div class="carousel">
          <img src="foto3_1.jpg" alt="Foto 1">
          <img src="foto3_2.jpg" alt="Foto 2">
          <img src="foto3_3.jpg" alt="Foto 3">
        </div>
      </div>
      <p>Descrição do produto 3</p>
      <button class="add-to-cart-button" data-product="3">Adicionar ao carrinho</button>
    </div>
    <!-- Repita o código acima para os outros produtos -->
  </main>

  <footer>
    <!-- Seu conteúdo do rodapé aqui -->
    <p>&copy; 2023 Loja de Artigos para Carro. Todos os direitos reservados.</p>
  </footer>

  <script>
    // Inicializar o carrossel usando a biblioteca Slick
    document.addEventListener("DOMContentLoaded", function() {
      var carousels = document.querySelectorAll(".carousel");
      Array.prototype.forEach.call(carous
