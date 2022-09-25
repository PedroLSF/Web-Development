# Border Radius
Desde que revelamos as bordas das caixas, você deve ter notado que as bordas destacam a verdadeira forma da caixa de um elemento: quadrado. Graças ao CSS, uma borda não precisa ser quadrada.

Você pode modificar os cantos da caixa de borda de um elemento com a propriedade border-radius.

```css
div.container {
  border: 3px solid blue;
  border-radius: 5px;
}
```

O código no exemplo acima definirá todos os quatro cantos da borda para um raio de 5 pixels (ou seja, a mesma curvatura que um círculo com um raio de 5 pixels teria).

Você pode criar uma borda que seja um círculo perfeito criando primeiro um elemento com a mesma largura e altura e, em seguida, definindo o raio igual à metade da largura da caixa, que é 50%.

```css
div.container {
  height: 60px;
  width: 60px;
  border: 3px solid blue;
  border-radius: 50%;
}
```

O código no exemplo acima cria um "div" que é um círculo perfeito.