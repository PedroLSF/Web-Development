# Multiple Classes
Podemos usar CSS para selecionar o atributo de classe de um elemento HTML por nome. E até agora, selecionamos elementos usando apenas um nome de classe por elemento. Se cada elemento HTML tivesse uma única classe, todas as informações de estilo para cada elemento exigiriam uma nova classe.

Felizmente, é possível adicionar mais de um nome de classe ao atributo class de um elemento HTML.

Por exemplo, talvez haja um elemento de título que precise ser verde e em negrito. Você poderia escrever dois conjuntos de regras CSS assim:

```css
.green {
  color: green;
}
 
.bold {
  font-weight: bold;
}
```

Então, você pode incluir essas duas classes em um elemento HTML como este:

```html
<h1 class='green bold'> ... </h1>
```

Podemos adicionar várias classes ao atributo class de um elemento HTML, separando-as com um espaço. Isso nos permite misturar e combinar classes CSS para criar muitos estilos exclusivos sem escrever uma classe personalizada para cada combinação de estilo necessária.