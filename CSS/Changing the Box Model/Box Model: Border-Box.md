# Box Model: Border-Box
Felizmente, podemos redefinir todo o modelo de caixa e especificar um novo: border-box.

```css
* {
  box-sizing: border-box;
}
```

O código no exemplo acima redefine o modelo de caixa para border-box para todos os elementos HTML. Este novo modelo de caixa evita os problemas dimensionais que existem no modelo de caixa anterior sobre o qual você aprendeu.

Neste modelo de caixa, a altura e a largura da caixa permanecerão fixas. A espessura da borda e o preenchimento serão incluídos dentro da caixa, o que significa que as dimensões gerais da caixa não mudam.

```html
<h1>Hello World</h1>
```

```css
* {
  box-sizing: border-box;
}
 
h1 {
  border: 1px solid black;
  height: 200px;
  width: 300px;
  padding: 10px;
}
```
No exemplo acima, a altura da caixa permaneceria em 200 pixels e a largura permaneceria em 300 pixels. A espessura da borda e o preenchimento permaneceriam inteiramente dentro da caixa.

![image](/Images/WProp.png)