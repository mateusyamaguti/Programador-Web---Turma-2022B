## Media Query
O Media Query é uma propriedade do CSS que possibilita a personalização das páginas na internet <br>
Existem vários tipos de mídia para ser trabalhado, depende muito objtivo do seu site e em qual dispositivo o usuário vai utilizar. No nosso caso vamos focar no tipo Screen (computadores e dispositivos moveis)<br>
Podemos especificar as configurações da media query, direto no link do css. Exemplo

    <link rel="stylesheet" href="estilo.css" media="screen and (color)">

ou

    <link rel="stylesheet" href="estilo.css" media="screen and (max-width: 480px)">

Quais os tipos de especificações: <br>
<strong>Especificações</strong>
<ul>
<li>width</li>
<li>height</li>
<li>device-width</li>
<li>device-height</li>
<li>orientation</li>
<li>aspect-radio</li>
<li>device-aspect-radio</li>
<li>color</li>
<li>color-index</li>
<li>monochrome</li>
<li>resolution</li>
<li>scan</li>
<li>grid</li>
</ul>

Como especificar: <br>
Primeiramente se deve colocar o mais geral no início do arquivo css, e as opções abaixo conforme o comportamento do dispositivo. Exemplo: fundo branco padrão, quando o dispositivo for menor que 600px fundo rosa, quando o disitivo por menor que 900px fundo laranja

    body{
    background-color: #eee;
    }
    @media screen and (max-width: 600px) {
        body{
            background-color: #F9C;
        }
    }
    @media screen and (min-width: 900px){
        body{
            background-color: #f90;
        }
    }

PDF: Web design responsivo - https://moodle.ifrs.edu.br/mod/url/view.php?id=271491 <br>

