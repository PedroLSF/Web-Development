# Padding Shorthand
Outra implementação da propriedade padding permite especificar exatamente quanto preenchimento deve haver em cada lado do conteúdo em uma única declaração. Uma declaração que usa várias propriedades como valores é conhecida como propriedade abreviada.

A abreviação de preenchimento permite especificar todas as propriedades de preenchimento como valores em uma única linha:

* padding-top
* padding-right
* padding-bottom
* padding-left

Você pode especificar essas propriedades de algumas maneiras diferentes:

### 4 Values
```css
p.content-header {
  padding: 6px 11px 4px 9px;
}
```

No exemplo acima, os quatro valores 6px 11px 4px 9px correspondem à quantidade de preenchimento de cada lado, em rotação no sentido horário. Em ordem, ele especifica o valor de preenchimento superior (6px), o valor de preenchimento direito (11px), o valor de preenchimento inferior (4px) e o valor de preenchimento esquerdo (9px) do conteúdo.

### 3 Values

```css
p.content-header {
  padding: 5px 10px 20px;
}
```

Se os lados esquerdo e direito do conteúdo puderem ser iguais, a propriedade abreviada de preenchimento permite que 3 valores sejam especificados. O primeiro valor define o valor de preenchimento superior (5px), o segundo valor define os valores de preenchimento esquerdo e direito (10px) e o terceiro valor define o valor de preenchimento inferior (20px).

### 2 Values
```css
p.content-header {
  padding: 5px 10px;
}
```
E, finalmente, se os lados superior e inferior puderem ser iguais e os lados esquerdo e direito puderem ser iguais, você poderá especificar 2 valores. O primeiro valor define os valores padding-top e padding-bottom (5px), e o segundo valor define os valores padding-left e padding-right (10px).