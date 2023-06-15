# Portfolio_Ana_Beatriz

Objetivo: Por meio desta conta fazer o portfólio e atingir a nota máxima, cadastrando minhas dúvidas e as resposta delas.

<h1>
  <ul>
    <li> CSS </li>
    <li> Java Script </li>
    <li> Estrutura Básica do Html </li>
  </ul>
</h1>


<h2>
  <p> Na aula do dia 24/05/2023 entramos nesse site e criamos uma pasta para fazer o porfólio para cadastrar nossas atividades do dia a dia. </p>
</h2>

<h3>
  <p> Na aula do dia 01/06/2023 fizemos uma ativiade para calcular a média ponderada, tive um pouco de dificuldade porque o botão de mostrar o resultado não estava dando certo. </p>
</h3>

<h4>
  <p> Na aula do dia 01/06/2023 fizemos uma ativiade sobre o Envio de Dados no form. Foi bem fácil de fazer, tranquilo. 
   'ARQUIVO GS'
     function doGet() {
  return HtmlService.createTemplateFromFile('formulario').evaluate();
}
function doPost(e) {
  Logger.log(e.parameter.Nome)
  Logger.log(e.parameter.Sobrenome)
}

function getUrl() {
  var url = ScriptApp.getService().getUrl();
  return url
}
  'ARQUIVO HTML'
 <!DOCTYPE html>
<html>
  <head>
    <title> formulario </title>
    <base target="_top">
  </head>
  <body>
    <? var url = getUrl() ?>

    <form action="<?= url ?>" method="POST">
      <label for="Nome">Nome</label>
      <input type="text" id="text" name="Nome">

       <label for="Sobrenome">Sobrenome</label>
      <input type="text" id="text" name="Sobrenome">

      <button type="submit">Enviar</button>
    </form>

  </body>
</html>

  </p>
</h4>

<h5>
  <p> </p>
</h5>
