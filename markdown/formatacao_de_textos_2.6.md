## Formatação de textos

### Links
Para fazer a formatação de links, primeiramente nos utilizamos a tag `<a>` de âncora, para ancorar os links de outras páginas <br>
Nos links é possível fazer uma personalização maior, conforme os exemplos abaixo:<br><br>
Cor do link:

    a:link{
    background-color: #b2ff99;
    color: blue;
    }

Cor do link quando for visitado

    a:visited{
        background-color: #ffff85;
        color: red;
    }

Cor do link quando o mouse passar por cima

    a:hover{
        background-color: #77704d;
        color: green;

Cor do link quando ativado  

    }
    a:active{
        background-color: #ff704d;

### Listas

Podemos personalizar as listas tradicionais, ao invés de ter bolinhas ou números, podemos ordenar do jeito que desejarmos. <br>
Exemplo de lista com imagem por tag: <br>

    ul{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 12pt;
    list-style-image: url('cubo.png');
    list-styyle-positions: inside;
    }

Exemplo lista com imagem por classe: <br>
Veja que a tag ul está sendo usada, pois ela ela delimita a lista, com tbm podemos usar ela para delimitar os parâmetros comum das classes

    ul{
        font-family: Arial, Helvetica, sans-serif;
        font-size: 12pt;
    }
    .item1{
        list-style-image: url('cubo.png');
        list-styyle-positions: inside;
    }
    .item2{
        list-style-image: url('cubomagico.png');
        list-styyle-positions: inside;
    }
    .item3{
        list-style-image: url('cubo.png');
        list-styyle-positions: inside;
    }

Podemos usar tbm outros tipos de padrões para listas desordenada ao invés de pontos, como por exemplo - list-style-type:vai ter vários tipos de estilo: <br>

    UL{
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        font-size: 12pt;
        list-style-type: disc;
    }

Para mais exemplos de menus que pode se comportar como menus, podemos acessar o site: https://css3menu.com/

