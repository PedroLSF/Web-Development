# Float
Até agora, você aprendeu como especificar a posição exata de um elemento usando propriedades de deslocamento. Se você está simplesmente interessado em mover um elemento o mais para a esquerda ou para a direita possível no container, você pode usar a propriedade float.

A propriedade float é comumente usada para envolver o texto em torno de uma imagem. Observe, no entanto, que mover elementos para a esquerda ou para a direita para fins de layout é mais adequado para ferramentas como grade CSS e flexbox, sobre as quais você aprenderá mais tarde.

A propriedade float geralmente é definida usando um dos valores abaixo:

* left - move, ou flutua, elementos o mais à esquerda possível.
* right - move os elementos o mais para a direita possível.

```css
.green-section {
  width: 50%;
  height: 150px;
}
 
.orange-section {
  background-color: orange;
  width: 50%;
  float: right;
}
```
No exemplo acima, flutuamos o elemento .orange-section para a direita. Isso funciona para elementos posicionados estáticos e relativos. Veja o resultado do código abaixo:

![image](/Images/Float.png)

Elementos flutuantes devem ter uma largura especificada, como no exemplo acima. Caso contrário, o elemento assumirá a largura total do elemento que o contém e a alteração do valor flutuante não produzirá nenhum resultado visível.
