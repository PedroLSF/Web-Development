# ID
Muitas vezes é importante selecionar um único elemento com CSS para dar a ele seu próprio estilo único. Se um elemento HTML precisar ser estilizado exclusivamente, podemos fornecer um ID usando o atributo id.

```html
<h1 id='large-title'> ... </h1>
```

Em contraste com a classe que aceita vários valores e pode ser usada amplamente em um documento HTML, o id de um elemento só pode ter um único valor e ser usado apenas uma vez por página.

Para selecionar o ID de um elemento com CSS, acrescentamos o nome do id com um sinal de número (#). Por exemplo, se quiséssemos selecionar o elemento HTML no exemplo acima, ficaria assim:

    #large-title {
    
    }

O nome do id é título grande, portanto, o seletor CSS para ele é #título grande.