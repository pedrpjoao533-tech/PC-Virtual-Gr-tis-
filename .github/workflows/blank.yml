
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Meu PC Virtual</title>
  <style>
    body {
      margin: 0;
      background: #101827;
      color: white;
      font-family: Arial, sans-serif;
      display: grid;
      place-items: center;
      min-height: 100vh;
    }
    .card {
      width: 85%;
      max-width: 380px;
      background: #1e293b;
      padding: 24px;
      border-radius: 18px;
      text-align: center;
    }
    input, button {
      box-sizing: border-box;
      width: 100%;
      padding: 13px;
      margin-top: 12px;
      border-radius: 9px;
      font-size: 16px;
    }
    input {
      border: 1px solid #475569;
      background: #0f172a;
      color: white;
    }
    button {
      border: 0;
      background: #2878ff;
      color: white;
      font-weight: bold;
    }
    p { color: #cbd5e1; line-height: 1.5; }
  </style>
</head>
<body>
  <div class="card">
    <h1>💻 Meu PC Virtual</h1>
    <p>Conecte-se ao seu computador Windows na nuvem.</p>

    <input id="servidor"
      placeholder="Endereço do PC (servidor)"
      autocomplete="url">

    <button onclick="conectar()">
      CONECTAR AO PC
    </button>

    <p id="mensagem">
      Digite o endereço do seu servidor Windows.
    </p>
  </div>

  <script>
    function conectar() {
      const servidor =
        document.getElementById("servidor").value.trim();

      const mensagem =
        document.getElementById("mensagem");

      if (!servidor) {
        mensagem.textContent =
          "Digite o endereço do servidor primeiro.";
        return;
      }

      mensagem.textContent =
        "Para acessar o Windows, abra seu aplicativo de " +
        "Área de Trabalho Remota no celular e configure " +
        "o servidor: " + servidor +
        ". Esta página não estabelece a conexão sozinha.";
    }
  </script>
</body>
</html>
