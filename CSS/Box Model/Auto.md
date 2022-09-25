# Auto
A propriedade margin também permite que você centralize o conteúdo. No entanto, você deve seguir alguns requisitos de sintaxe. Dê uma olhada no exemplo a seguir:

```css
div.headline {
  width: 400px;
  margin: 0 auto;
}
```

No exemplo acima, margin: 0 auto; irá centralizar as divs em seus elementos contidos. O 0 define as margens superior e inferior para 0 pixels. O valor auto instrui o navegador a ajustar as margens esquerda e direita até que o elemento seja centralizado no elemento que o contém.

Para centralizar um elemento, uma largura deve ser definida para esse elemento. Caso contrário, a largura do div será definida automaticamente para a largura total do elemento que o contém, como o "body", por exemplo. Não é possível centralizar um elemento que ocupe toda a largura da página, pois a largura da página pode mudar devido ao tamanho da tela e/ou da janela do navegador.

No exemplo acima, a largura da div é definida como 400 pixels, que é menor que a largura da maioria das telas. Isso fará com que o div centralize dentro de um recipiente