# Formulário

## Introdução

Para criar formulários usa-se a tag `<form>`, além disso, o atributo mais importante no formulário é o <b>action=""</b>, o qual será responsável por indicador para qual lugar aquela informação vai. Como também, o atributo que se refere ao envio do formulário <b>method=""</b>, que pode ser "post" (melhor método) ou "get" (historico do navegador - não recomendavel)

### Parâmetros dos fomulários:
<ul>
<li>action</li>
<li>autocomplete</li>
<li>enctype</li>
<li>method</li>
<li>name</li>
<li>novalidate</li>
<li>target</li>
</ul>

## Campo texto
Parâmetros de input

<ul>
<li>autocomplete</li>
<li>autofocus</li>
<li>disable</li>
<li>max</li>
<li>maxlength</li>
<li>min</li>
<li>name</li>
<li>pattern</li>
<li>placeholder</li>
<li>readonly</li>
<li>required</li>
<li>size</li>
<li>type</li>
<li>value</li>
<li></li>
</ul>

## Botões

Botão de clique simples: <br>
`<button type="button">Clique</button>`<br>

Botão de submissão: <br>
`<button type="submit">Enviar</button>`<br>

Parâmetros dos botões<br>

<ul>
<li>autofocus</li>
<li>disabled</li>
<li>name</li>
<li>type: button, reset, submit</li>
<li>value</li>
</ul>

Parâmetro dos botões de tipo submit<br>

<ul>
<li>formaction</li>
<li>formmethod</li>
<li>formnovalidate</li>
<li>formtarget</li>
<li></li>
</ul>

## Rótulos e Agrupamento de campos

Dentro dos formulários é possível inserir elementos que vão além dos próprios campos, como inserir rótulos e como delimitar o conjunto de campos que pertencem a um domínio comum, ou seja, que são do mesmo tipo/categoria. <br>

### Label
Faz com que ao clicar no campo label, seja redirecionado a algum campo do formulário
É necessário que o rótulo, ou o parâmetro label seja conectado a algum elemento ou tag, pelo parâmetro ID <br>
Exemplo: <br>

`<label for="endereco">Endereço</label>`<br>
`<textarea name="endereco" id="endereco" cols="30" rows="10"></textarea>`

### Fieldset
Conjunto de campos que pertencem a um domínio comum <br>
Para melhorar a orgnanização é bom colocar a tag <b>legend<b><br>
Exemplo:<br>
`<fieldset>`
`<legend>Dados Pessoais:</legend>`<br>
`Nome:<input type="text"><br>`<br>
`Email: <input type="text"><br>`<br>
`Nascimentos: <input type="text">`<br>
`</fieldset>`<br>

## Campos de seleção
Dentro do HTML é possível criar um conjunto de opções a serem selecionadas por meio de checkboxs, radios e selects

### Checkbox
Caixa de seleção, permite várias seleções <br>
Exemplo: <br>

        <form action="#" method="post">
            <p><h3>Checkbox</h3></p>
            <input type="checkbox" name="html" value="1">HTML<br>
            <input type="checkbox" name="css" value="1">CSS<br>
            <input type="checkbox" name="javascript" value="1">javascript<br>
        </form>

### Radio
Diferente do campo checkbox, type radio permite apenas uma seleção. Para isso, o valor (value) da tag input precisa ser diferente das demais

### Parâmetro

<b>checked:</b> Esse parâmetro deixa pré selecinado uma caixa de seleção

### SELECT
Permite escolher dentro de uma lista de seleção qual opção o usuário deseja. Como também o select possui parâmetros especificos.
<b>select:<b><br>
<ul>
<li>autofocus</li>
<li>disabled</li>
<li>multiple</li>
<li>name</li><br>
<li>required</li>
<li>size</li>
</ul>
<p></p>
<b>option</b>
<ul>
<li>disabled</li>
<li>label</li>
<li>selected</li>
<li>value</li>
</ul>
Exemplo:<br>

        <form action="#" method="post">
            <p><h3>SELECT</h3></p><br>
            Selecione o Estado <br>
            <select name="estado">
                <option value="sao_paulo">São Paulo</option>
                <option value="acre">Acre</option>
                <option value="tocantins">Tocantins</option>
            </select>
        </form>
<p></p>

## Novos Campos

input type e-mail <br>
input type date (calendário) <br>
input type range (barra de escala) <br>
input type color (escolher diversas colores) <br>

Novo campo datelist -> uma mescla do select <br>

