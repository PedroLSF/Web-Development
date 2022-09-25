# Overflow
Todos os componentes do modelo de caixa compreendem o tamanho de um elemento. Por exemplo, uma imagem com as seguintes dimensões tem 364 pixels de largura e 244 pixels de altura.

* 300 pixels de largura
* 200 pixels de altura
* 10 pixels de preenchimento à esquerda e à direita
* 10 pixels de preenchimento na parte superior e inferior
* 2 pixels de borda à esquerda e à direita
* 2 pixels de borda na parte superior e inferior
* Margem de 20 pixels à esquerda e à direita
* Margem de 10 pixels na parte superior e inferior

As dimensões totais (364 px por 244 px) são calculadas somando todas as dimensões verticais e todas as dimensões horizontais. Às vezes, esses componentes resultam em um elemento maior que a área de contenção do pai.

Como podemos garantir que podemos visualizar todo um elemento que é maior que a área de contenção de seu pai?

A propriedade overflow controla o que acontece com o conteúdo que transborda ou transborda fora de sua caixa. Os valores mais usados são:

* hidden — quando definido para este valor, qualquer conteúdo que overflows ficará oculto da visualização.
* scroll — quando definido para este valor, uma barra de rolagem será adicionada à caixa do elemento para que o restante do conteúdo possa ser visualizado rolando.
* visible — quando definido para este valor, o conteúdo de overflow será exibido fora do elemento que o contém. Observe que este é o valor padrão.

```css
p {
  overflow: scroll; 
}
```
No exemplo acima, se algum conteúdo do parágrafo transbordar (talvez um usuário redimensione a janela do navegador), uma barra de rolagem aparecerá para que os usuários possam visualizar o restante do conteúdo.

A propriedade overflow é definida em um elemento pai para instruir um navegador da Web sobre como renderizar elementos filho. Por exemplo, se a propriedade de overflow de um div estiver definida para rolar, todos os filhos desse div exibirão o conteúdo transbordante com uma barra de rolagem.

Para uma visão mais detalhada do overflow, incluindo propriedades adicionais como overflow-x e overflow-y que separam os valores horizontal e vertical, vá para a documentação do MDN.