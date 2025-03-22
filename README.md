<!-- 
    Irei falar para o navegador
    qual o documento que irar
    carregar 
-->
<!DOCTYPE html>
<!-- 
    Iniciando o meu projeto com HTML
-->
<html>
<!-- Cabeçalho -->

<head>
    <!-- Titulo da pagina -->
    <title>Dia 1</title>

    <!-- Tag's de configurações -->
    <meta charset="UTF-8">

</head>
<!-- O corpo da pagina -->

<body>
    <!-- Tag's de titulos -->
    <h1>Olá mundo!</h1>

    <h2> Sub informação </h2>

    <h3> Sub informação </h3>

    <h4> Sub informação </h4>

    <h5> Sub informação </h5>

    <h6> Sub informação </h6>

    <!-- Hiper link -->
    <a href="https:\\google.com"> google </a>
    <!-- quebra de linha -->
    </br>

    <!-- Botões para click's -->
    <button> Botão 1 </button>
    <button> Botão 2 </button>


    <!-- Tabela -->
    <table>
        <!-- Cabeçalho -->
        <thead>
            <!-- tabela linha -->
            <tr>
                <th>id</th>
                <th>nome</th>
                <th>telefone</th>
                <th>e-mail</th>
            </tr>
        </thead>
        <!-- Conteudo da tabela -->
        <tbody>
            <!-- Aqui fica o loop -->
            <tr>
                <td>0</td>
                <td>Francisco Wallison</td>
                <td>85 9 5000000</td>
                <td>franciscowallison@gmail.com</td>
            </tr>
            <tr>
                <td>1</td>
                <td>Levi Ribeiro</td>
                <td>85 9 96833118</td>
                <td>levirs999@gmail.com</td>
            </tr>
        </tbody>
    </table>
    <!-- Paragrafo -->
    <p>Lorem, ipsum dolor <a href="https:\\google.com">sit</a> amet consectetur adipisicing elit. Placeat officia
        distinctio et? Eligendi, quam. Quam soluta sit omnis? Nostrum harum mollitia, laudantium vero rem soluta odit
        tempore provident dolores fuga.</p>
    <!-- Imagem -->
    <a href="https:\\google.com">
        <img src="img/undraw_car-repair_wski.png" alt="">
    </a>

    <!-- Formulario -->

    <form>
        <!-- Titulo do Input-->
        <label for="Primeiro-nome">Nome: </label>
        <input type="text" placeholder="Primeiro nome" id="Primeiro-nome"/>
    </br>
        <label for="Segundo-nome">Segundo Nome: </label>
        <input type="text" placeholder="Segundo nome" id="Segundo-nome"/>
    </br>
        <label for="email">E-mail: </label>
        <input type="email" name="email" placeholder="Exemplo@texte.com" id="email">
    </br>
        <input type="submit" name="" id="">
    </form>

</body>



</html>
