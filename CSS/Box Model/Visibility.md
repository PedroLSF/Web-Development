# Visibility
Os elementos podem ser ocultados da vista com a propriedade de visibility.

A propriedade de visibility pode ser definida com um dos seguintes valores:

* hidden — oculta um elemento.
* visible — exibe um elemento.
* collapse — recolhe um elemento.

```css
<ul>
  <li>Explore</li>
  <li>Connect</li>
  <li class="future">Donate</li>
</ul>
```

```css
.future {
  visibility: hidden;
}
```

No exemplo acima, o item da lista com uma classe de futuro será ocultado da visualização no navegador.

No entanto, lembre-se de que os usuários ainda podem visualizar o conteúdo do item da lista (por exemplo, Donate) visualizando o código-fonte em seu navegador. Além disso, a página da Web apenas ocultará o conteúdo do elemento. Ele ainda deixará um espaço vazio onde o elemento deve ser exibido.

Pergunta: Qual é a diferença entre display: none e visibility: oculto? 

Resposta: Um elemento com display: none será completamente removido da página web. Um elemento com visibility: oculto, no entanto, não será visível na página da web, mas o espaço reservado para ele será.