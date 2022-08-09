# Main e Footer
Mais dois elementos estruturais são "main" e "footer". Esses elementos, juntamente com "nav" e "header", ajudam a descrever onde um elemento está localizado com base nos padrões convencionais de desenvolvimento da Web.

O elemento "main" é usado para encapsular o conteúdo dominante em uma página da web. Essa tag é separada do "footer" e do "nav" de uma página da Web, pois esses elementos não contêm o conteúdo principal. Ao usar "main" em vez de um elemento "div", leitores de tela e navegadores da Web são mais capazes de identificar que o que estiver dentro da tag é a maior parte do conteúdo.

Então, como "main" fica quando incorporado ao nosso código? Essa é uma ótima pergunta.

    <main>
        <header>
            <h1>Types of Sports</h1>
        </header>
        <article>
            <h3>Baseball</h3>
            <p>
            The first game of baseball was played in Cooperstown, New York in the summer of 1839.
            </p>
        </article>
    </main>

Como vimos acima, "main" contém uma tag "article" e "header" com elementos filhos que contêm as informações mais importantes relacionadas à página.

O conteúdo na parte inferior das informações do assunto é conhecido como rodapé, indicado pelo elemento "footer". O rodapé contém informações como:

<ul>
<li>Informações de Contato</li>
<li>Informações sobre direitos autorais</li>
<li>Termos de uso</li>
<li>Mapa do site</li>
<li>Referência aos links do topo da página</li>
</ul>

Por exemplo:

    <footer>
        <p>Email me at Codey@Codecademy.com</p>
    </footer>

No exemplo acima, o rodapé é usado para conter informações de contato. A tag "footer" é separada do elemento "main" e normalmente localizada na parte inferior do conteúdo.