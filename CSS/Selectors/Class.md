# Class
CSS não se limita a selecionar elementos por seu tipo. Como você sabe, os elementos HTML também podem ter atributos. Ao trabalhar com HTML e CSS, um atributo de classe é uma das formas mais comuns de selecionar um elemento.

Por exemplo, considere o seguinte HTML:

```html
<p class='brand'>Sole Shoe Company</p>
```

O elemento de parágrafo no exemplo acima tem um atributo class dentro da tag de abertura do elemento "p". O atributo de classe é definido como 'marca'. Para selecionar este elemento usando CSS, podemos criar um conjunto de regras com um seletor de classe de .brand.

```css
.brand {
 
}
```

Para selecionar um elemento HTML por sua classe usando CSS, um ponto (.) deve ser anexado ao nome da classe. No exemplo acima, a classe é brand, então o seletor CSS para ela é .brand.