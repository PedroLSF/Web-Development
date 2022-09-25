# Margin Shorthand
E se você não quiser margens iguais nos quatro lados da caixa e não tiver tempo para separar as propriedades de cada lado? Você está com sorte! A margem também pode ser escrita como uma propriedade abreviada. A sintaxe abreviada para margens é a mesma que margem, portanto, se você se sentir confortável com isso, pule para as instruções. Caso contrário, continue lendo para aprender a usar a abreviação de margem!

Semelhante à abreviação de preenchimento, a abreviação de margem permite especificar todas as propriedades de margem como valores em uma única linha:

* margin-top
* margin-right
* margin-bottom
* margin-left

Você pode especificar essas propriedades de algumas maneiras diferentes:

### 4 Values
```css
p.content-header {
  margin: 6px 10px 5px 12px;
}
```

No exemplo acima, os quatro valores 6px 10px 5px 12px correspondem à espessura da margem de cada lado, em rotação no sentido horário. Em ordem, ele especifica o valor da margem superior (6px), o valor da margem direita (10px), o valor da margem inferior (5px) e o valor da margem esquerda (12px) do conteúdo.

### 3 Values

```css
p.content-header {
  margin: 5px 12px 4px;
}
```

Se os lados esquerdo e direito do conteúdo puderem ser iguais, a propriedade abreviada de margem permite que 3 valores sejam especificados. O primeiro valor define o valor margin-top (5px), o segundo valor define os valores margin-left e margin-right (12px) e o terceiro valor define o valor margin-bottom (4px).

### 2 Values
```css
p.content-header {
  margin: 20px 10px;
}
```
E, finalmente, se os lados superior e inferior puderem ser iguais e os lados esquerdo e direito puderem ser iguais, você poderá especificar 2 valores. O primeiro valor define os valores margin-top e margin-bottom (20px), e o segundo valor define os valores margin-left e margin-right (10px).