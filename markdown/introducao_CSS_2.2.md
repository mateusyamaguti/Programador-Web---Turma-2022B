## Fontes
Atualmente toda formatação de fontes é feita detro do arquivo CSS, sendo é muito importante enteder como fazer essa formatação

Podemos por exemplo configurar a tag `<p>` para formatação de parágrafos <br>

As unidades de tamanho dentro do CSS são divididas em dois tipo <br>

<table>
    <tr>
        <td><b>Relativo</b></td>
        <td><b>Absoluto</b></td>
    </tr>
        <tr>
        <td>%</td>
        <td>in</td>
    </tr>
    </tr>
        <tr>
        <td>em</td>
        <td>cm</td>
    </tr>
    </tr>
        <tr>
        <td>ex</td>
        <td>mm</td>
    </tr>
    </tr>
        <tr>
        <td>px</td>
        <td>pt</td>
    </tr>
    </tr>
        <tr>
        <td></td>
        <td>pc</td>
    </tr>
</table>

### Decoração do texto

Exemplo de linha sobre o texto, no meio do texto e embaixo do texto

    .inferior{
    text-decoration: underline;
    }
    .superior{
        text-decoration: overline;
    }
    .centro{
        text-decoration: line-through;
    }
    .pisca{
        text-decoration: blink;
    }

### Recúo de parágrafo

Usado para dar espaçamento de parágrafo
`text-indent: 30pt`

### Sombra e letra maiúscula

    text-shadow: blue 5px 6px 2px;
    text-transform: capitalize;