# Link mesma página
Neste ponto, temos todo o conteúdo que queremos em nossa página. Como temos muito conteúdo, nem tudo cabe na tela. Como tornamos mais fácil para um usuário pular para diferentes partes da nossa página?

Quando os usuários visitam nosso site, queremos que eles possam clicar em um link e fazer com que a página role automaticamente para uma seção específica.

Para vincular a um destino na mesma página, devemos fornecer ao destino um id, como este:

    <p id="top">This is the top of the page!</p>
    <h1 id="bottom">This is the bottom! </h1>

Neste exemplo, a tag "p" recebe um id “top” e a tag "h1" é atribuído “bottom”. Um id pode ser adicionado à maioria das tags em uma página da web.

Um id deve ser descritivo para facilitar a memorização da finalidade de um link. O link de destino é uma string contendo o caractere # e o id da tag de destino.

    <ol>
    <li><a href="#top">Top</a></li>
    <li><a href="#bottom">Bottom</a></li>
    </ol>

No exemplo acima, os links para "p id="top"" e "h1 id="bottom"" são incorporados em uma lista ordenada. Esses links aparecem no navegador como uma lista numerada de links. Um id é especialmente útil para organizar o conteúdo pertencente a uma div!

