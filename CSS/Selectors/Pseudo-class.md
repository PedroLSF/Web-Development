# Pseudo-class
Você pode ter observado como a aparência de certos elementos pode mudar, ou estar em um estado diferente, após determinadas interações do usuário. Por exemplo:

* Quando você clica em um elemento "input", uma borda azul é adicionada mostrando que está em foco.
* Quando você clica em um link "a" azul para visitar outra página, mas quando você retorna o texto do link é roxo.
* Quando você está preenchendo um formulário e o botão de envio fica acinzentado e desabilitado. Mas quando todos os campos estiverem preenchidos, o botão fica com a cor indicando que está ativo.

Estes são todos exemplos de seletores de pseudo-classe em ação! Na verdade, :focus, :visited, :disabled e :active são todas pseudo-classes. Fatores como interação do usuário, navegação no site e posição na árvore do documento podem dar aos elementos um estado diferente com pseudoclasse.

Uma pseudoclasse pode ser anexada a qualquer seletor. É sempre escrito como dois pontos : seguido por um nome. Por exemplo p:hover.

```css
p:hover {
  background-color: lime;
}
```

