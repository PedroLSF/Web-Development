# Clear
A propriedade float também pode ser usada para flutuar vários elementos de uma só vez. No entanto, quando vários elementos flutuantes têm alturas diferentes, isso pode afetar seu layout na página. Especificamente, os elementos podem “bater” uns nos outros e não permitir que outros elementos se movam adequadamente para a esquerda ou para a direita.

A propriedade clear especifica como os elementos devem se comportar quando se chocam na página. Pode assumir um dos seguintes valores:

left — o lado esquerdo do elemento não tocará em nenhum outro elemento dentro do mesmo elemento que o contém.
right — o lado direito do elemento não tocará em nenhum outro elemento dentro do mesmo elemento que o contém.
both — nenhum lado do elemento tocará em qualquer outro elemento dentro do mesmo elemento que o contém.
none - o elemento pode tocar qualquer um dos lados.

```css
div {
  width: 200px;
  float: left;
}
 
div.special {
  clear: left;
}
```

No exemplo acima, todos os "div"s na página flutuam para o lado esquerdo. O elemento com classe especial não se moveu totalmente para a esquerda porque um "div" mais alto bloqueou seu posicionamento. Ao definir sua propriedade clear para a esquerda, o "div" especial será movido totalmente para o lado esquerdo da página.