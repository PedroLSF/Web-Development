# Espaço em Branco
O restante desta lição se concentrará em algumas ferramentas que os desenvolvedores usam para tornar o código mais fácil de interpretar.

À medida que o código em um arquivo HTML cresce, fica cada vez mais difícil acompanhar como os elementos estão relacionados. Os programadores usam duas ferramentas para visualizar a relação entre os elementos: espaço em branco e recuo.

Ambas as ferramentas tiram vantagem do fato de que a posição dos elementos em um navegador é independente da quantidade de espaço em branco ou recuo no arquivo index.html.

Por exemplo, se você quiser aumentar o espaço entre dois parágrafos em sua página da Web, não poderá fazer isso adicionando espaço entre os elementos de parágrafo no arquivo index.html. O navegador ignora espaços em branco em arquivos HTML quando renderiza uma página da Web, para que possa ser usado como uma ferramenta para tornar o código mais fácil de ler e seguir.

O que torna o exemplo abaixo difícil de ler?

    <body><p>Paragraph 1</p><p>Paragraph 2</p></body>

Você tem que ler a linha inteira para saber quais elementos estão presentes. Compare o exemplo acima com este:

    <body>
    <p>Paragraph 1</p>
    <p>Paragraph 2</p>
    </body>

Este exemplo é mais fácil de ler, pois cada elemento está em sua própria linha. Enquanto o primeiro exemplo exigia que você lesse toda a linha de código para identificar os elementos, este exemplo facilita a identificação da tag body e dois parágrafos.

Um navegador renderiza os dois exemplos da mesma maneira:

    Paragraph 1
    Paragraph 2

No próximo exercício, você aprenderá como usar o recuo para ajudar a visualizar elementos aninhados.