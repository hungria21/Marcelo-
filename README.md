<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Apresentação</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header>
      <h1>Bem-vindo à Minha Apresentação</h1>
    </header>
    <nav>
      <ul>
        <li><a href="#about">Sobre</a></li>
        <li><a href="#services">Serviços</a></li>
        <li><a href="#contact">Contato</a></li>
      </ul>
    </nav>
    <main>
      <section id="about">
        <h2>Sobre</h2>
        <p>Eu sou um desenvolvedor web altamente capacitado e apaixonado por tecnologia. Possuo vasta experiência em várias tecnologias, incluindo HTML, CSS, JavaScript e PHP. Além disso, estou sempre procurando aprender e desenvolver minhas habilidades para fornecer soluções de alta qualidade para meus clientes.</p>
      </section>
      <section id="services">
        <h2>Serviços</h2>
        <ul>
          <li>Desenvolvimento de Sites</li>
          <li>Manutenção de Sites</li>
          <li>Desenvolvimento de Aplicativos Web</li>
          <li>Otimização de SEO</li>
        </ul>
      </section>
      <section id="contact">
        <h2>Contato</h2>
        <form>
          <label for="name">Nome:</label>
          <input type="text" id="name" name="name" required>
          <label for="email">E-mail:</label>
          <input type="email" id="email" name="email" required>
          <label for="message">Mensagem:</label>
          <textarea id="message" name="message" required></textarea>
          <input type="submit" value="Enviar">
        </form>
      </section>
    </main>
    <footer>
      <p>Todos os direitos reservados &copy; 2023</p>
    </footer>
  </body>
</html>

body {
  background-color: #333;
  color: #fff;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;

