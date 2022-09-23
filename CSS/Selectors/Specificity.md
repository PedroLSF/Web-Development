# Specificity
Especificidade é a ordem pela qual o navegador decide quais estilos CSS serão exibidos. Uma prática recomendada em CSS é estilizar elementos usando o menor grau de especificidade para que, se um elemento precisar de um novo estilo, seja fácil de substituir.

IDs são o seletor mais específico em CSS, seguido por classes e, por fim, tipo. Por exemplo, considere o seguinte HTML e CSS:

```html
<h1 class='headline'>Breaking News</h1>
```

```css
h1 {
  color: red;
}
 
.headline {
  color: firebrick;
}
```

No código de exemplo acima, a cor do título seria definida como firebrick, pois o seletor de classe é mais específico que o seletor de tipo. Se um atributo de ID (e seletor) fosse adicionado ao código acima, os estilos no corpo do seletor de ID substituiriam todos os outros estilos do título.

Com o tempo, à medida que os arquivos crescem com o código, muitos elementos podem ter IDs, o que pode dificultar a edição do CSS, pois um novo estilo mais específico deve ser criado para alterar o estilo de um elemento.

Para facilitar a edição de estilos, é melhor estilizar com um seletor de tipo, se possível. Caso contrário, adicione um seletor de classe. Se isso não for específico o suficiente, considere usar um seletor de ID.