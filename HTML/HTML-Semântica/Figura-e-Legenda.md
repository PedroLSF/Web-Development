# Figura e legenda da figura
Com "aside", aprendemos que podemos colocar informações adicionais ao lado de um conteúdo principal, mas e se quisermos adicionar uma imagem ou ilustração? É aí que entram "figure" e "figcaption".

"figure" é um elemento usado para encapsular mídia como imagem, ilustração, diagrama, trecho de código, etc, que é referenciado no fluxo principal do documento.

    <figure>
        <img src="overwatch.jpg">
    </figure>

Neste código, criamos um elemento "figure" para que possamos encapsular nossa tag "img". Em "figure" usamos a tag "img" para inserir uma imagem na página da web. Usamos o atributo src dentro da tag "img" para que possamos vincular a fonte da imagem.

É possível adicionar uma legenda à imagem usando "figcaption".

"figcaption" é um elemento usado para descrever a mídia na tag "figure". Normalmente, "figcaption" irá para dentro de "figure". Isso é diferente de usar um elemento "p" para descrever o conteúdo; se decidirmos mudar a localização de "figure", a tag de parágrafo pode ser deslocada da figura enquanto uma "figcaption" se moverá com a figura. Isso é útil para agrupar uma imagem com uma legenda.

    <figure>
        <img src="overwatch.jpg">
        <figcaption>This picture shows characters from Overwatch.</figcaption>
    </figure>

No exemplo acima, adicionamos um "figcaption" no elemento "figure" para descrever a imagem do exemplo anterior. Isso ajuda a agrupar o conteúdo "figure" com o conteúdo "figcaption".

Enquanto o conteúdo em "figure" está relacionado ao fluxo principal do documento, sua posição é independente. Isso significa que você pode removê-lo ou movê-lo para outro lugar sem afetar o fluxo do documento.