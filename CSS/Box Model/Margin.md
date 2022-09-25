# Margin
Até agora, você aprendeu sobre os seguintes componentes do modelo de caixa: conteúdo, bordas e preenchimento. O quarto e último componente do modelo de caixa é a margem.

Margem refere-se ao espaço diretamente fora da caixa. A propriedade margin é usada para especificar o tamanho deste espaço.

```css
p {
  border: 1px solid aquamarine;
  margin: 20px;
}
```

O código no exemplo acima colocará 20 pixels de espaço do lado de fora da caixa do parágrafo em todos os quatro lados. Isso significa que outros elementos HTML na página não podem chegar a 20 pixels da borda do parágrafo.

Se você quiser ser ainda mais específico sobre a quantidade de margem em cada lado de uma caixa, você pode usar as seguintes propriedades:

* margin-top
* margin-right
* margin-bottom
* margin-left

Cada propriedade afeta a margem em apenas um lado da caixa, proporcionando mais flexibilidade na personalização.

```css
p {
  border: 3px solid DarkSlateGrey;
  margin-right: 15px;
}
```

No exemplo acima, apenas o lado direito da caixa do parágrafo terá uma margem de 15 pixels. É comum ver valores de margem usados para um lado específico de um elemento.
