# Minimum and Maximum Height and Width
Como uma página da Web pode ser visualizada por meio de exibições de diferentes tamanhos de tela, o conteúdo da página da Web pode sofrer com essas alterações de tamanho. Para evitar esse problema, o CSS oferece duas propriedades que podem limitar o tamanho da caixa de um elemento: estreita ou larga:

* min-width—esta propriedade garante uma largura mínima da caixa de um elemento.
* max-width—esta propriedade garante a largura máxima da caixa de um elemento.

```css
p {
  min-width: 300px;
  max-width: 600px;
}
```

No exemplo acima, a largura de todos os parágrafos não diminuirá abaixo de 300 pixels, nem a largura excederá 600 pixels.

O conteúdo, como o texto, pode se tornar difícil de ler quando uma janela do navegador é reduzida ou expandida. Essas duas propriedades garantem que o conteúdo seja legível, limitando as larguras mínima e máxima de um elemento.

Você também pode limitar a altura mínima e máxima de um elemento:

min-height — esta propriedade garante uma altura mínima para a caixa de um elemento.
max-height — esta propriedade garante uma altura máxima da caixa de um elemento.

```css
p {
  min-height: 150px;
  max-height: 300px;
}
```

No exemplo acima, a altura de todos os parágrafos não diminuirá abaixo de 150 pixels e a altura não excederá 300 pixels.

O que acontecerá com o conteúdo da caixa de um elemento se a propriedade max-height for definida muito baixa? É possível que o conteúdo saia da caixa, resultando em conteúdo que não é legível. Você aprenderá a contornar esse problema no próximo exercício.