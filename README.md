<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site formularios</title>
</head>
<!-- Conteudo Apresentado ao visitante -->
<body>
<!-- criação de menus-->
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    <!-- Lista ordenada -->
    <ol>
        <li> Categoria </li>
            <ul>
                <li>Carros</li>
                <li>Moto</li>

            </ul>
        <li>Item 2</li>
        <li>Item 3</li>
    </ol>

<!-- Criando Tabelas  -->
<table>

<!-- Cabeçalho da tabela  -->
    <thead>
      <tr>
        <!-- alinha do cabeçalho -->
        <th>#</th>
        <th>Nome</th>
        <th>EMail</th>
      </tr>
    </thead>

    <tbody>

        <!--iniciando linha do corpo-->
        <tr>
        <!-- Iniciando as informações-->
            <td>0</td>
            <td>Guilherme</td>
            <td>Guimas@hotmail.com</td>
        </tr>

        <!--iniciando linha do corpo-->
        <tr>
            <!-- Iniciando as informações-->
                <td>1</td>
                <td>ana</td>
                <td>ana@hotmail.com</td>
            </tr>

    <!--iniciando linha do corpo-->
    <tr>
        <!-- Iniciando as informações-->
        <td>3</td>
        <td>joao</td>
        <td>joao@hotmail.com</td>
    </tr>



    </tbody>

</table>


<!-- Formulario -->
<form target="/pesquisar">
    <!-- Paragrafo -->
    <p> Formulario de cadastro </p>
    <!-- tag utilizada para dar nome ao input -->
    <label for="nome" > Nome </label>
    <!-- Tag para adicionar informções -->
    <!-- type: tipo de input que pode ser texto, email -->
    <!-- id: indentificador -->
    <!-- nome: nos ajudara a capturar a informação que foi passada -->
    <!-- required: valor booleano -->
    <!-- placeholder: informação dentro do input -->

    <input id="nome" type="text" name="nome" required placeholder="Digite o seu nome"/>
    <br>


    <label for="email"> E-mail</label>
    <input id="email" type="email" name="email" required placeholder="Digite seu e-mail">
    <br>

    <label for="senha">senha</label>
    <input id="senha" type="password" name="senha" required placeholder="digite sua senha">
    <br>
    <!-- usando tag botão -->
    <button type="submit">Enviar</button>





</form>

<a href="https://www.google.com.br/"> Vai para o google</a>
<br>
<!-- Target para abrir uma nova aba -->
<a href="https://www.google.com.br/" target="_blank">vai para o google</a>
<!-- hr:adiciona uma linha -->
<hr>
<!-- action: redireciona o usuario com as informações passadas -->
<form action="https://wa.me/55859">
   <label for="text">mensagem</label>
<br>
   <textarea id="text" name="text"></textarea>
<br>
<!-- usando tag input para enviar -->
<input type="submit">

</form>

<!-- form -->
<form>
   
   
    <p>Pedido de Pizza</p>
    <br>
    <label for="localidade"> Localidade </label>
    <input type="text" id="localidade" name="localidade" required placeholder="adicionar rua, bairro, número">
<br>
    <!-- type="radio": é para selecionar apenas uma opção -->
    <!-- o atributo "name" dele repete para que possa escolher somente 1 -->
    <p>borda</p>
    <input type="radio" id="chedder" name="borda" value="chedder"/>
    <label for="chedder">chedder</label>
<br>
    <input type="radio" id="catupiry" name="borda" value="catupiry"/>
    <label for="catupiry">catupiry</label>
<br>
    <input type="radio" id="chocolate" name="borda" value="chocolate"/>
    <label for="chocolate">chocolate</label>
<br>    
    <!-- select -->
    <P>adicionais</P>
    <label for="mais">adicionais</label>
    <select name="adicionais" id="adicionais">
        <option value="queijo">Queijo</option>
        <option value="tomate"> Tomate </option>
    </select>
    <br>
    <!-- pizza -->
    <p>Pizzas</p>
    <input type="checkbox" name="pizza" value="marquerita">
    <label for="marquerita">marquerita</label>
<br>
    <input type="checkbox" name="pizza" value="4Queijos">
    <label for="4Queijos">4Queijos</label>
<br>
<button type="submit">enviar pedido</button>

    
    
</form>
</body>
</html>
