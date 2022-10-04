# Inline Display
Cada elemento HTML tem um valor de exibição padrão que determina se ele pode compartilhar espaço horizontal com outros elementos. Alguns elementos preenchem todo o navegador da esquerda para a direita, independentemente do tamanho de seu conteúdo. Outros elementos ocupam apenas o espaço horizontal que seu conteúdo exige e podem estar diretamente ao lado de outros elementos.

Nesta lição, abordaremos três valores para a propriedade display: inline, block e inline-block.

A exibição padrão de alguns elementos, como "em", "strong" e "a", é chamada de inline. Os elementos inline têm uma caixa que envolve seu conteúdo firmemente, ocupando apenas a quantidade de espaço necessária para exibir seu conteúdo e não exigindo uma nova linha após cada elemento. A altura e a largura desses elementos não podem ser especificadas no documento CSS. Por exemplo, o texto de uma marca âncora ("a") será, por padrão, exibido na mesma linha que o texto ao redor e terá a largura necessária para conter seu conteúdo. elementos inline não podem ser alterados em tamanho com as propriedades CSS height ou width.

```html
To learn more about <em>inline</em> elements, read <a href="#">MDN documentation</a>.   
```

No exemplo acima, o elemento "em" é embutido, pois exibe seu conteúdo na mesma linha do conteúdo ao seu redor, incluindo a marca âncora. Este exemplo exibirá:

Para saber mais sobre elementos embutidos, leia a documentação do MDN.

A propriedade de exibição CSS fornece a capacidade de tornar qualquer elemento um elemento embutido. Isso inclui elementos que não são embutidos por padrão, como parágrafos, divs e títulos.

```css
h1 {
  display: inline;
}
```

O CSS no exemplo acima mudará a exibição de todos os elementos "h1" para inline. O navegador renderizará elementos "h1" na mesma linha que outros elementos embutidos imediatamente antes ou depois deles (se houver).