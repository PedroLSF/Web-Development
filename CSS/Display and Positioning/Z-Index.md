# Z-Index
Quando as caixas em uma página da Web têm uma combinação de posições diferentes, as caixas (e, portanto, seu conteúdo) podem se sobrepor, dificultando a leitura ou o consumo do conteúdo.

```css
.blue-box {
  background-color: blue;
}
 
.green-box {
  background-color: green;
  position: relative;
  top: -170px;
  left: 170px;
}
```

No exemplo acima, o elemento .green-box se sobrepõe ao elemento .blue-box.

A propriedade z-index controla o quanto um elemento deve aparecer para trás ou para frente na página da Web quando os elementos se sobrepõem. Isso pode ser pensado como a profundidade dos elementos, com elementos mais profundos aparecendo atrás de elementos mais rasos.

A propriedade z-index aceita valores inteiros. Dependendo de seus valores, os inteiros instruem o navegador sobre a ordem em que os elementos devem ser colocados em camadas na página da web.

```css
.blue-box {
  background-color: blue;
  position: relative;
  z-index: 1;
}
 
.green-box {
  background-color: green;
  position: relative;
  top: -170px;
  left: 170px;
}
```

No exemplo acima, definimos a posição .blue-box para relativa e o z-index para 1. Mudamos a posição para relativa, porque a propriedade z-index não funciona em elementos estáticos. O z-index de 1 move o elemento .blue-box para frente, porque o valor z-index não foi especificado explicitamente para o elemento .green-box, o que significa que ele tem um valor z-index padrão de 0. Dê uma olhada a imagem de exemplo abaixo:

![image](/Images/ZIndex.png)

