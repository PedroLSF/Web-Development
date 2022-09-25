# Why Change the Box Model?
A última lição concentrou-se nos aspectos mais importantes do modelo de caixa: dimensões da caixa, bordas, preenchimento e margem.

O modelo de caixa, no entanto, tem uma limitação complicada em relação às dimensões da caixa. Essa limitação é melhor ilustrada com um exemplo.

```html
<h1>Hello World</h1>
```

```css
h1 {
  border: 1px solid black;
  height: 200px;
  width: 300px;
  padding: 10px;
}
```

No exemplo acima, a caixa de um elemento de título tem bordas sólidas, pretas, com 1 pixel de espessura. A altura da caixa é de 200 pixels, enquanto a largura da caixa é de 300 pixels. Um preenchimento de 10 pixels também foi definido em todos os quatro lados do conteúdo da caixa.

Infelizmente, no modelo de caixa atual, a espessura da borda e o preenchimento afetarão as dimensões da caixa.

Os 10 pixels de preenchimento aumentam a altura da caixa para 220 pixels e a largura para 320 pixels. Em seguida, a borda grossa de 1 pixel aumenta a altura para 222 pixels e a largura para 322 pixels.

Sob este modelo de caixa, a espessura da borda e o preenchimento são adicionados às dimensões gerais da caixa. Isso torna difícil dimensionar com precisão uma caixa. Com o tempo, isso também pode dificultar o posicionamento e o gerenciamento de todo o conteúdo de uma página da Web.

Nesta breve lição, você aprenderá a usar uma técnica diferente que evita completamente esse problema.