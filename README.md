<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Diagnóstico BIM</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f7f7f7;
    }
    h1 {
      text-align: center;
    }
    form {
      background-color: white;
      padding: 20px;
      border-radius: 8px;
      max-width: 1200px;
      margin: auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 20px;
    }
    th, td {
      padding: 8px;
      border: 1px solid #ccc;
    }
    th {
      background-color: #005ca9;
      color: white;
    }
    .header-inputs input {
      width: 100%;
      padding: 5px;
    }
    .submit-button {
      background-color: #005ca9;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
    }
    .submit-button:hover {
      background-color: #004080;
    }
  </style>
</head>
<body>
  <h1>Diagnóstico Preliminar BIM</h1>
  <form action="https://formsubmit.co/leone.augusto@hotmail.com" method="POST">
    <div class="header-inputs">
      <label>Instituição:</label>
      <input type="text" name="instituicao"><br><br>
      <label>Principais áreas de atuação:</label>
      <input type="text" name="areas"><br><br>
      <label>Composição da equipe técnica:</label>
      <input type="text" name="equipe"><br><br>
    </div>

    <table>
      <tr>
        <th>Pilar</th>
        <th>Avaliação</th>
        <th>Sim</th>
        <th>Não</th>
        <th>Na</th>
        <th>Síntese Positiva</th>
        <th>Síntese Negativa</th>
        <th>Complementação</th>
      </tr>

      <!-- Questões geradas dinamicamente -->
      <!-- Exemplo de uma questão -->
      <tr>
        <td>Política</td>
        <td>1) Existe iniciativa formalizada da Prefeitura para promover/fomentar a Transformação Digital?</td>
        <td><input type="radio" name="q1" value="Sim"></td>
        <td><input type="radio" name="q1" value="Não"></td>
        <td><input type="radio" name="q1" value="Na"></td>
        <td><input type="text" name="q1_positiva"></td>
        <td><input type="text" name="q1_negativa"></td>
        <td><input type="text" name="q1_complemento"></td>
      </tr>

      <!-- Repita conforme o padrão acima para as questões de 2 a 16 -->

    </table>

    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_next" value="https://example.com/agradecimento.html">
    <button type="submit" class="submit-button">Enviar Diagnóstico</button>
  </form>
</body>
</html>
