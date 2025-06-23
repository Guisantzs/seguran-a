<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Segurança Digital</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Projeto Segurança Digital</h1>
    <p>Dicas para proteger seus dados online</p>
  </header>

  <main>
    <section id="dicas">
      <h2>Dicas de Segurança</h2>
      <ul>
        <li>Use senhas fortes e diferentes para cada site</li>
        <li>Ative a autenticação em duas etapas (2FA)</li>
        <li>Não clique em links suspeitos de e-mails</li>
        <li>Mantenha seu antivírus atualizado</li>
        <li>Evite redes Wi-Fi públicas sem VPN</li>
      </ul>
    </section>

    <section id="verificador">
      <h2>Verifique sua senha</h2>
      <input type="password" id="senha" placeholder="Digite uma senha">
      <button onclick="verificarSenha()">Verificar</button>
      <p id="resultado"></p>
    </section>
  </main>

  <footer>
    <p>Desenvolvido com 💻 na trilha da Alura</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
