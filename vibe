<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Bel Vibes</title>

  <!-- Fonte desenhada -->
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet" />

  <style>
    /* Estilo Geral */
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #0e0a0e; /* Fundo bem escuro */
      color: #d8cfd8; /* Texto em tom claro, não branco */
    }

    /* Cabeçalho */
    header {
      background-color: #1a0f1a; /* Roxo quase preto */
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-family: 'Pacifico', cursive;
      color: #8b1e3f; /* Vermelho escuro fechado */
      font-size: 3em;
      font-weight: normal; /* Tirando o negrito */
    }

    /* Grade do Feed */
    .feed {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    /* Card do Post */
    .post {
      background-color: #1a0f1a; /* Fundo do card bem escuro */
      border-radius: 15px;
      padding: 10px;
      box-shadow: 0 5px 15px rgba(139, 30, 63, 0.3); /* Sombra em tom vermelho fechado */
      opacity: 0;
      transform: translateY(20px);
      transition: all 0.6s ease;
    }

    .post img {
      width: 100%;
      height: 300px;
      object-fit: cover;
      border-radius: 10px;
    }

    .post p {
      margin-top: 10px;
      color: #d69ca5; /* Tom de rosa queimado suave */
    }

    /* Efeito de aparecer na rolagem */
    .post.show {
      opacity: 1;
      transform: translateY(0);
    }

    /* Responsividade */
    @media (max-width: 768px) {
      header h1 {
        font-size: 2.5em;
      }
      .post img {
        height: 250px;
      }
    }

    @media (max-width: 480px) {
      header h1 {
        font-size: 2em;
      }
      .post img {
        height: 200px;
      }
    }
  </style>
</head>

<body>
  <!-- Cabeçalho -->
  <header>
    <h1>Bel Vibes</h1>
  </header>

  <!-- Feed Estilo Instagram -->
  <section class="feed">
    <div class="post">
      <img src="https://s11.aconvert.com/convert/p3r68-cdx67/2wh5l-lq0ze.jpg" alt="Foto 1" />
      <p>Um olhar que é filhadaputamente perfeito, um olhar marcante que ja deixou sua mancha na minha alma..</p>
    </div>
    <div class="post">
      <img src="https://s11.aconvert.com/convert/p3r68-cdx67/75sj2-qoha8.jpg" alt="Foto 2" />
      <p>As vezes a própria bebida fala pore ela, mas são momentos no mínimo cômicos kkkk</p>
    </div>
    <div class="post">
      <img src="https://s11.aconvert.com/convert/p3r68-cdx67/nlq01-994ug.jpg" alt="Foto 3" />
      <p>Como ela diz "Deftones é um sentimento", e eu te digo que o meu sentimento por ela é simplesmente Cherry Waves.</p>
    </div>
    <div class="post">
      <img src="	https://s11.aconvert.com/convert/p3r68-cdx67/6a9rk-6q1nw.jpg" alt="Foto 4" />
      <p>Um dos únicos lados ainda misterioso pelo lado dela que eu espero conhecer.</p>
    </div>
    <div class="post">
      <img src="https://s11.aconvert.com/convert/p3r68-cdx67/g221k-wz1wq.jpg" alt="Foto 5" />
      <p>É O FLUZÃO CARALHO.</p>
    </div>
    <div class="post">
      <img src="https://s11.aconvert.com/convert/p3r68-cdx67/85r6q-zdbn9.jpg" alt="Foto 6" />
      <p>Além de gostosa e tatuada toca guitarra🤤🤤🤤</p>
    </div>
    <div class="post">
      <img src="https://s11.aconvert.com/convert/p3r68-cdx67/0lm14-31ati.jpg" alt="Foto 7" />
      <p>A muié é malucona fi, impressionante o quanto isso me apaixona cada vez mais.</p>
    </div>
    <div class="post">
      <img src="https://s11.aconvert.com/convert/p3r68-cdx67/0a50x-0maed.jpg" alt="Foto 8" />
      <p>Você não é guia, mas balançou meu terreiro...
Acho que jogaram pemba no meu coração,
porque desde que te vi, só gira você na minha cabeça. <div/>
desculpa se foi desrespeitosa</p>
    </div>
  </section>

  <!-- Script de animação -->
  <script>
    const posts = document.querySelectorAll('.post');

    window.addEventListener('scroll', checkPosts);

    function checkPosts() {
      const triggerBottom = window.innerHeight * 0.9;

      posts.forEach(post => {
        const postTop = post.getBoundingClientRect().top;

        if (postTop < triggerBottom) {
          post.classList.add('show');
        } else {
          post.classList.remove('show');
        }
      });
    }

    // Verificar ao carregar
    checkPosts();
  </script>
</body>
</html>
