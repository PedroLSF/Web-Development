# Vinculação à página relativa

Até agora, você aprendeu como criar links para páginas da web externas. Muitos sites também possuem links para páginas da Web internas, como Home, About e Contact.

Antes de aprendermos a fazer links entre páginas internas, vamos estabelecer onde nossos arquivos são armazenados. Ao criar sites estáticos de várias páginas, os desenvolvedores da Web geralmente armazenam arquivos HTML no diretório raiz ou em uma pasta principal onde todos os arquivos do projeto são armazenados. À medida que o tamanho dos projetos que você cria aumenta, você pode usar pastas adicionais dentro da pasta principal do projeto para organizar seu código.

    project-folder/
    |—— about.html
    |—— contact.html
    |—— index.html

O exemplo acima mostra três arquivos diferentes — about.html, contact.html e index.html em uma pasta.

Os arquivos HTML geralmente são armazenados na mesma pasta, conforme mostrado no exemplo acima. Se o navegador estiver exibindo index.html, ele também saberá que about.html e contact.html estão na mesma pasta. Como os arquivos são armazenados na mesma pasta, podemos vincular páginas da Web usando um caminho relativo.

    <a href="./contact.html">Contact</a>

Neste exemplo, a tag 

    <a> 

é usada com um caminho relativo para vincular o arquivo HTML atual ao arquivo contact.html na mesma pasta. Na página da web, Contato aparecerá como um link.

Um caminho relativo é um nome de arquivo que mostra o caminho para um arquivo local (um arquivo no mesmo site, como ./index.html) versus um caminho absoluto (um URL completo, como https://www.codecademy.com/ learn/learn-html que está armazenado em uma pasta diferente). O ./ em ./index.html diz ao navegador para procurar o arquivo na pasta atual.