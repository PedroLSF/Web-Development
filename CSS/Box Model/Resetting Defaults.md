# Resetting Defaults
Todos os principais navegadores da Web têm uma folha de estilo padrão que usam na ausência de uma folha de estilo externa. Essas folhas de estilo padrão são conhecidas como folhas de estilo do agente do usuário. Nesse caso, o termo agente do usuário é um termo técnico para o navegador.

As folhas de estilo do agente do usuário geralmente têm regras CSS padrão que definem valores padrão para preenchimento e margem. Isso afeta como o navegador exibe os elementos HTML, o que pode dificultar o design ou o estilo de uma página da Web por um desenvolvedor.

Muitos desenvolvedores optam por redefinir esses valores padrão para que possam realmente trabalhar com uma ardósia limpa.

```css
* {
  margin: 0;
  padding: 0;
}
```
O código no exemplo acima redefine os valores padrão de margem e preenchimento de todos os elementos HTML. Geralmente é a primeira regra CSS em uma folha de estilo externa.

Observe que ambas as propriedades são definidas como 0. Quando essas propriedades são definidas como 0, elas não requerem uma unidade de medida.