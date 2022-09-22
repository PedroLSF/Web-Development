# Inline Styles
Embora o CSS seja uma linguagem diferente do HTML, é possível escrever código CSS diretamente no código HTML usando estilos embutidos.

Para estilizar um elemento HTML, você pode adicionar o atributo style diretamente à tag de abertura. Depois de adicionar o atributo, você pode defini-lo igual ao(s) estilo(s) CSS que deseja aplicar a esse elemento.

~~~html
<p style='color: red;'>I'm learning to code!</p>
~~~

O código no exemplo acima demonstra como usar o estilo embutido. O elemento de parágrafo tem um atributo de estilo dentro de sua marca de abertura. Em seguida, o atributo style é definido como color: red;, que definirá a cor do texto do parágrafo para vermelho no navegador.

Se você quiser adicionar mais de um estilo com estilos embutidos, continue adicionando ao atributo style. Certifique-se de terminar os estilos com um ponto e vírgula (;).

~~~html
<p style='color: red; font-size: 20px;'>I'm learning to code!</p>
~~~

É importante saber que os estilos inline são uma maneira rápida de estilizar diretamente um elemento HTML, mas raramente são usados na criação de sites. Mas você pode encontrar circunstâncias em que o estilo inline é necessário, portanto, entender como ele funciona e reconhecê-lo no código HTML é um bom conhecimento. Em breve você aprenderá a maneira correta de adicionar código CSS!