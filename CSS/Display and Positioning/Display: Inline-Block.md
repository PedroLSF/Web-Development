# Display: Inline-Block
O terceiro valor para a propriedade display é inline-block. A exibição de bloco em linha combina recursos de elementos de bloco e em linha. Os elementos do bloco embutido podem aparecer um ao lado do outro e podemos especificar suas dimensões usando as propriedades de largura e altura. As imagens são o melhor exemplo de elementos de bloco inline padrão.

Por exemplo, os "div"s abaixo serão exibidos na mesma linha e com as dimensões especificadas:

![image](/Images/PoBlock.png)

Vamos dar uma olhada no código:

```html
<div class="rectangle">
  <p>I’m a rectangle!</p>
</div>
<div class="rectangle">
  <p>So am I!</p>
</div>
<div class="rectangle">
  <p>Me three!</p>
</div>
```

```css
.rectangle {
  display: inline-block;
  width: 200px;
  height: 300px;
}
```

Existem três divs retangulares, cada uma contendo um parágrafo de texto. Os .retangle <div>s aparecerão todos alinhados (desde que haja espaço suficiente da esquerda para a direita) com largura de 200 pixels e altura de 300 pixels, mesmo que o texto dentro deles não exija 200 pixels por 300 pixels de espaço.