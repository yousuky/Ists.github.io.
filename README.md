# Ists.github.io.
prevencao-ists.hmtl
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Saúde: ISTs e Gravidez na Adolescência</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: linear-gradient(135deg, #f0f8ff, #ffffff);
    }

    header {
      background: #0077b6;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      padding: 20px;
      gap: 20px;
      align-items: center;
    }

    .texto {
      flex: 1;
      min-width: 250px;
    }

    .texto h2 {
      color: #0077b6;
    }

    .imagem {
      flex: 1;
      text-align: center;
      min-width: 250px;
    }

    .imagem img {
      width: 80%;
      max-width: 300px;
      border-radius: 15px;
    }

    .enquete {
      background: white;
      margin: 20px;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
    }

    button {
      margin-top: 10px;
      padding: 12px;
      background: #0077b6;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }

    button:hover {
      background: #023e8a;
    }

    footer {
      background: #0077b6;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>

<body>

<header>
  <h1>Saúde do Adolescente</h1>
  <p>Informações sobre ISTs e Gravidez na Adolescência</p>
</header>

<!-- ISTs -->
<div class="container">
  <div class="texto">
    <h2>O que são ISTs?</h2>
    <p>
      As Infecções Sexualmente Transmissíveis (ISTs) são doenças transmitidas
      principalmente por relações sexuais sem proteção. Entre as mais conhecidas
      estão HIV, sífilis e HPV.
    </p>

    <h2>Como prevenir?</h2>
    <p>
      O uso de preservativo é a principal forma de prevenção. Também é importante
      realizar exames e buscar orientação em postos de saúde.
    </p>
  </div>

  <div class="imagem">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Red_ribbon.svg" alt="Prevenção ISTs">
  </div>
</div>

<!-- Gravidez na adolescência -->
<div class="container">
  <div class="texto">
    <h2>Gravidez na adolescência</h2>
    <p>
      A gravidez na adolescência pode trazer desafios físicos, emocionais e sociais.
      Muitas vezes acontece por falta de informação ou ausência de métodos contraceptivos.
    </p>

    <h2>Prevenção</h2>
    <p>
      O uso de métodos contraceptivos, como preservativos e anticoncepcionais,
      além de educação sexual, ajudam a prevenir a gravidez precoce.
    </p>
  </div>

  <div class="imagem">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Pregnant_woman.svg/512px-Pregnant_woman.svg.png" alt="Gravidez">
  </div>
</div>

<!-- Enquete -->
<div class="enquete">
  <h2>Enquete</h2>
  <p>Qual é a melhor forma de prevenir ISTs e gravidez na adolescência?</p>

  <form>
    <input type="radio" name="opcao"> Uso de preservativo<br>
    <input type="radio" name="opcao"> Informação e educação sexual<br>
    <input type="radio" name="opcao"> Uso de métodos contraceptivos<br>
    <input type="radio" name="opcao"> Todas as alternativas acima<br><br>

    <button type="button" onclick="alert('Resposta enviada! Obrigado 😊')">
      Enviar
    </button>
  </form>
</div>

<footer>
  <p>Site educativo sobre saúde e prevenção</p>
</footer>

</body>
</html>
