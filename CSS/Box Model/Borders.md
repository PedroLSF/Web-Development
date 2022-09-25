# Borders
Uma borda é uma linha que envolve um elemento, como uma moldura em torno de uma pintura. As bordas podem ser definidas com largura, estilo e cor específicos:

* width — A espessura da borda. A espessura de uma borda pode ser definida em pixels ou com uma das seguintes palavras-chave: fina, média ou grossa.
* style — O design da borda. Os navegadores da Web podem renderizar qualquer um dos 10 estilos diferentes. Alguns desses estilos incluem: nenhum, pontilhado e sólido.
* color — A cor da borda. Os navegadores da Web podem renderizar cores usando alguns formatos diferentes, incluindo 140 palavras-chave de cores incorporadas.

```css
p {
  border: 3px solid coral;
}
```

No exemplo acima, a borda tem uma largura de 3 pixels, um estilo de sólido e uma cor de coral. Todas as três propriedades são definidas em uma linha de código.

A borda padrão é média sem cor, onde cor é a cor atual do elemento. Se a largura, o estilo ou a cor não estiverem definidos no arquivo CSS, o navegador da Web designará o valor padrão para essa propriedade.

```css
p.content-header {
  height: 80px;
  width: 240px;
  border: solid coral;
}
```

Neste exemplo, o estilo da borda é definido como sólido e a cor é definida como coral. A largura não está definida, portanto, o padrão é médio.