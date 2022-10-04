# Position: Sticky
Como os elementos estáticos e relativos posicionados permanecem no fluxo normal do documento, quando um usuário rola a página (ou elemento pai), esses elementos também rolam. E como os elementos posicionados fixos e absolutos são removidos do fluxo de documentos, quando um usuário rola, esses elementos permanecerão em sua posição de deslocamento especificada.

O valor fixo é outro valor de posição que mantém um elemento no fluxo do documento à medida que o usuário rola, mas permanece em uma posição especificada à medida que a página é rolada ainda mais. Isso é feito usando o valor fixo junto com as propriedades de deslocamento familiares, bem como um novo.

```css
.box-bottom {
  background-color: darkgreen;
  position: sticky;
  top: 240px;
}
```

No exemplo acima, o .box-bottom "div" permanecerá em sua posição relativa e rolará normalmente. Quando atingir 240 pixels a partir do topo, ele permanecerá nessa posição até atingir a parte inferior do contêiner pai, onde será “descolado” e voltará ao fluxo do documento.

![GIF](/Images/Sticky.gif)

