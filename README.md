<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Loja</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {margin:0; padding:0; box-sizing:border-box; font-family: 'Roboto', sans-serif;}
    body {background-color: #f4f4f9; color:#333;}
    header {background: linear-gradient(90deg, #ff7e5f, #feb47b); color:white; text-align:center; padding:2rem 1rem;}
    header h1 {font-size:2.5rem;}
    header p {margin-top:0.5rem; font-size:1.2rem;}

    main {display:grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap:2rem; padding:2rem;}
    .produto {background:white; border-radius:10px; padding:1rem; box-shadow:0 4px 10px rgba(0,0,0,0.1); transition: transform 0.3s;}
    .produto:hover {transform: translateY(-5px);}
    .produto h2 {margin-bottom:0.5rem; color:#ff7e5f;}
    .produto p {margin:0.5rem 0 1rem 0;}
    .produto video {width:100%; border-radius:10px; margin-bottom:1rem;}
    .produto button {background:#ff7e5f; color:white; border:none; padding:0.7rem 1.5rem; border-radius:5px; cursor:pointer; font-weight:bold; transition: background 0.3s;}
    .produto button:hover {background:#feb47b;}

    footer {text-align:center; padding:1.5rem; background:#333; color:white; margin-top:2rem;}
    .support {position:fixed; bottom:20px; right:20px; background:#ff7e5f; color:white; padding:1rem 1.5rem; border-radius:50px; box-shadow:0 4px 10px rgba(0,0,0,0.2); cursor:pointer; font-weight:bold; transition: background 0.3s;}
    .support:hover {background:#feb47b;}
  </style>
</head>
<body>
  <header>
    <h1>Minha Loja</h1>
    <p>Produtos incríveis com vídeos!</p>
  </header>

  <main>
    <!-- Produtos (6 no máximo) -->
    <section class="produto">
      <h2>Produto 1</h2>
      <video autoplay muted loop controls>
        <source src="[https://drive.google.com/uc?export=download&id=ID_DO_VIDEO1" type="video/mp4](https://drive.google.com/uc?export=download&id=1eoQiFkGl4DH-Wn0oE4f_KRsOKKuf4_lc)">
        Seu navegador não suporta vídeo.
      </video>
      <p>Descrição completa do Produto 1. Conteúdo detalhado e chamativo.</p>
      <button onclick="adicionarCarrinho('Produto 1')">Comprar</button>
    </section>

    <section class="produto">
      <h2>Produto 2</h2>
      <video autoplay muted loop controls>
        <source src="https://drive.google.com/uc?export=download&id=ID_DO_VIDEO2" type="video/mp4">
        Seu navegador não suporta vídeo.
      </video>
      <p>Descrição completa do Produto 2. Conteúdo detalhado e chamativo.</p>
      <button onclick="adicionarCarrinho('Produto 2')">Comprar</button>
    </section>

    <section class="produto">
      <h2>Produto 3</h2>
      <video autoplay muted loop controls>
        <source src="https://drive.google.com/uc?export=download&id=ID_DO_VIDEO3" type="video/mp4">
        Seu navegador não suporta vídeo.
      </video>
      <p>Descrição completa do Produto 3. Conteúdo detalhado e chamativo.</p>
      <button onclick="adicionarCarrinho('Produto 3')">Comprar</button>
    </section>

    <section class="produto">
      <h2>Produto 4</h2>
      <video autoplay muted loop controls>
        <source src="https://drive.google.com/uc?export=download&id=ID_DO_VIDEO4" type="video/mp4">
        Seu navegador não suporta vídeo.
      </video>
      <p>Descrição completa do Produto 4. Conteúdo detalhado e chamativo.</p>
      <button onclick="adicionarCarrinho('Produto 4')">Comprar</button>
    </section>

    <section class="produto">
      <h2>Produto 5</h2>
      <video autoplay muted loop controls>
        <source src="https://drive.google.com/uc?export=download&id=ID_DO_VIDEO5" type="video/mp4">
        Seu navegador não suporta vídeo.
      </video>
      <p>Descrição completa do Produto 5. Conteúdo detalhado e chamativo.</p>
      <button onclick="adicionarCarrinho('Produto 5')">Comprar</button>
    </section>

    <section class="produto">
      <h2>Produto 6</h2>
      <video autoplay muted loop controls>
        <source src="https://drive.google.com/uc?export=download&id=ID_DO_VIDEO6" type="video/mp4">
        Seu navegador não suporta vídeo.
      </video>
      <p>Descrição completa do Produto 6. Conteúdo detalhado e chamativo.</p>
      <button onclick="adicionarCarrinho('Produto 6')">Comprar</button>
    </section>
  </main>

  <footer>
    <p>Minha Loja © 2026</p>
  </footer>

  <!-- Botão de suporte -->
  <div class="support" onclick="window.location.href='mailto:suporte@minhaloja.com'">
    Suporte
  </div>

  <script>
    function adicionarCarrinho(produto) {
      alert(produto + " foi adicionado ao carrinho!");
    }
  </script>
</body>
</html>

</html>
