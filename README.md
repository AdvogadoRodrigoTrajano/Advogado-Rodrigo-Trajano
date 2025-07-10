![mapa-interativo](https://github.com/user-attachments/assets/312eaf28-03e7-40a2-8a29-734d29199155)[Uploading 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rodrigo Trajano | Advogado</title>
  <meta name="description" content="Rodrigo Trajano - Advogado. Atuação nacional. Direito internacional, trabalhista, civil, família.">
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background-color: #111; color: #fff; }
    header, footer { background-color: #000; padding: 20px; text-align: center; }
    h1, h2 { color: #d4af37; }
    section { padding: 20px; max-width: 960px; margin: auto; }
    .mapa { text-align: center; margin: 2rem 0; }
    .mapa img, .mapa svg { max-width: 100%; height: auto; }
    .whatsapp-button {
      position: fixed; bottom: 20px; right: 20px;
      background: #25d366; color: white; padding: 15px 20px;
      border-radius: 50px; font-weight: bold;
      text-decoration: none; box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }
    .form-container {
      background: #222; padding: 20px; border-radius: 10px; margin-top: 40px;
    }
    input, textarea {
      width: 100%; padding: 10px; margin: 10px 0;
      border: none; border-radius: 5px;
    }
    button {
      background: #d4af37; border: none;
      padding: 10px 20px; color: black; font-weight: bold;
      border-radius: 5px; cursor: pointer;
    }
  </style>
  <script>
    function enviarWhatsApp() {
      var nome = document.getElementById('nome').value;
      var numero = document.getElementById('numero').value.replace(/\D/g, '');
      var pergunta = document.getElementById('pergunta').value;
      var texto = `Olá, meu nome é ${nome}, meu número é +55${numero}. Minha pergunta é: ${pergunta}`;
      var url = `https://wa.me/5513981036116?text=${encodeURIComponent(texto)}`;
      window.open(url, '_blank');
    }
  </script>
</head>
<body>
<header>
  <h1>Trajano</h1>
  <p>Rodrigo Trajano – Advogado | OAB/SP 477765</p>
  <p>Fluente em português e espanhol</p>
</header>

<section>
  <h2>Áreas de Atuação</h2>
  <ul>
    <li>Direito Trabalhista</li>
    <li>Direito Civil</li>
    <li>Direito de Família</li>
    <li>Direito do Consumidor, Bancário, Imobiliário, Tributário</li>
    <li>Direito Internacional – Sequestro de Menores (Convenção de Haia)</li>
  </ul>
</section>

<section class="mapa">
  <h2>Atuação Nacional</h2>
  <p>Estados com municípios onde já atuei:</p>
  <img src="mapa-interativo.svg" alt="Mapa interativo">
</section>

<section>
  <h2>Contato</h2>
  <p>Email: <a href="mailto:adv.rodrigotrajano@gmail.com">adv.rodrigotrajano@gmail.com</a></p>
</section>

<section class="form-container">
  <h2>❓ Tem dúvidas?</h2>
  <p>Digite seu nome, número de WhatsApp e pergunta abaixo. Você será redirecionado automaticamente.</p>
  <input id="nome" type="text" placeholder="Seu nome" required />
  <input id="numero" type="text" placeholder="WhatsApp com DDD (ex: 13981036116)" required />
  <textarea id="pergunta" rows="4" placeholder="Digite sua pergunta aqui..." required></textarea>
  <button onclick="enviarWhatsApp()">Enviar pelo WhatsApp</button>
</section>

<section>
  <h2>About (English)</h2>
  <p>Brazilian attorney fluent in Portuguese and Spanish. Specialized in Labor, Civil, Family and International Law (Hague Convention). Nationwide practice.</p>
</section>

<section>
  <h2>Sobre mí (Español)</h2>
  <p>Abogado brasileño, fluente en portugués y español. Especializado en Derecho Laboral, Civil, de Familia e Internacional (Convenio de La Haya). Actuación nacional.</p>
</section>

<a class="whatsapp-button" href="https://wa.me/5513981036116" target="_blank">WhatsApp</a>

<footer>
  &copy; 2025 Rodrigo Trajano. Todos os direitos reservados.
</footer>
</body>
</html>
index.html…]()
![Up<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 600">
<rect width="800" height="600" fill="#d4af37"/>
<text x="50%" y="50%" font-size="30" text-anchor="middle" fill="#111" dy=".3em">Mapa Interativo do Brasil</text>
</svg>loading mapa-interativo.svg…]()
