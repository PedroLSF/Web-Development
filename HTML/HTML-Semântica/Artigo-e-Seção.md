# Article e Section
Agora que cobrimos o corpo do HTML semântico, vamos nos concentrar no que pode estar no corpo. Os dois elementos que vamos focar agora são "section" e "article".

"section" define elementos em um documento, como capítulos, títulos ou qualquer outra área do documento com o mesmo tema. Por exemplo, conteúdo com o mesmo tema, como artigos sobre críquete, pode ser colocado em uma única "section". A página inicial de um site pode ser dividida em seções para introdução, notícias e informações de contato.

Aqui está um exemplo de como usar "section":

    <section>
        <h2>Fun Facts About Cricket</h2> 
    </section>

No código acima criamos um elemento "section" para encapsular o código. Em "section" adicionamos um elemento "h2" como título.

O elemento "article" contém conteúdo que faz sentido por conta própria. "article" pode conter conteúdo como artigos, blogs, comentários, revistas etc. Uma tag "article" ajudaria alguém que usa um leitor de tela a entender onde o conteúdo do artigo (que pode conter uma combinação de texto, imagens, áudio etc.) começa e termina.

Aqui está um exemplo de como usar "article":

    <section>
        <h2>Fun Facts About Cricket</h2>
        <article>
            <p>A single match of cricket can last up to 5 days.</p>
        </article>
    </section>

No código acima, o elemento "article" contendo um fato sobre críquete foi colocado dentro do elemento "section". É importante notar que um elemento "section" também pode ser colocado em um elemento "article" dependendo do contexto.