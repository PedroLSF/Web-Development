# Padding
O espaço entre o conteúdo de uma caixa e as bordas de uma caixa é conhecido como preenchimento. O preenchimento é como o espaço entre uma imagem e o quadro que a cerca. Em CSS, você pode modificar este espaço com a propriedade padding.

```css
p.content-header {
  border: 3px solid coral;
  padding: 10px;
}
```

O código neste exemplo coloca 10 pixels de espaço entre o conteúdo do parágrafo (o texto) e as bordas, nos quatro lados.

A propriedade padding é frequentemente usada para expandir a cor do plano de fundo e fazer com que o conteúdo pareça menos apertado.

Se você quiser ser mais específico sobre a quantidade de preenchimento em cada lado do conteúdo de uma caixa, você pode usar as seguintes propriedades:

* padding-top
* padding-right
* padding-bottom
* padding-left

Cada propriedade afeta o preenchimento em apenas um lado do conteúdo da caixa, oferecendo mais flexibilidade na personalização.

```css
p.content-header {
  border: 3px solid fuchsia;
  padding-bottom: 10px;
}
```

No exemplo acima, apenas a parte inferior do conteúdo do parágrafo terá um preenchimento de 10 pixels.