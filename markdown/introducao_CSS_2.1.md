## Introdução a CSS

O CSS consiste em uma folha de estilo, porém nesse 1º momento iremos realizar o design dentro do próprio html. Primeiramente dentro do cabeçalho <b>head</b> incluimos a tag <b>style</b> e começamos dentro dela a configurar a tag <b>body</b>
Exemplo tudo ques estiver dentro da tag body será vermelho, fonte verdana e tamanho 50 pixels <br>
        
        <style> 
        body{color:red;
        }
        </style>

Outra dorma de referenciar o arquivo CSS

    <link rel="stylesheet" type="text/CSS" href="Local.path">

Podemos colocar tbm que dentro de uma tag que todas as letras serão em negrito <font-weight: bold;>

Outra forma de realizar o stylo é por meio dos id ou class, id e class <br>
principalmente na tag, pois a tag spam não faz nada, foi feita para ajudar com o CSS <b>spam</b> <br>
Referenciar estilo pr ID:<br>

    #id1{ 
        font-size: 24px;
    }

Referenciar estilo por class: <br>

    .class1{
        font-size: 10px;
    }

Como também podemos combinar formatações
