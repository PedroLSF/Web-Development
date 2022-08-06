# Cabeçalho
Os dados da tabela não fazem muito sentido sem títulos para descrever o que os dados representam.

Para adicionar títulos a linhas e colunas, você pode usar o elemento de cabeçalho da tabela: 

    <th>.

O elemento de cabeçalho da tabela é usado exatamente como um elemento de dados da tabela, exceto com um título relevante. Assim como os dados da tabela, um cabeçalho de tabela deve ser colocado em uma linha da tabela.

    <table>
    <tr>
        <th></th>
        <th scope="col">Saturday</th>
        <th scope="col">Sunday</th>
    </tr>
    <tr>
        <th scope="row">Temperature</th>
        <td>73</td>
        <td>81</td>
    </tr>
    </table>

O que aconteceu no código acima?

Primeiro, uma nova linha foi adicionada para conter os três títulos: um título em branco, um título de Saturday e um título de Sunday. O cabeçalho em branco cria a célula de tabela extra necessária para alinhar os cabeçalhos de tabela corretamente sobre os dados aos quais correspondem.

Na segunda linha, um cabeçalho de tabela foi adicionado como título de linha: Temperature.

Quando renderizado, este código aparecerá semelhante à imagem abaixo:

Imagem

Observe também o uso do atributo scope, que pode assumir um de dois valores:

row - este valor deixa claro que o título é para uma linha.
col - este valor deixa claro que o cabeçalho é para uma coluna.
O código HTML para tabelas pode parecer um pouco estranho no começo, mas analisá-lo peça por peça ajuda a tornar o código mais compreensível.