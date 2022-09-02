# Audios e Atributos
Agora que aprendemos sobre conteúdo baseado em texto, vamos nos aprofundar em "audio"! Certamente todo mundo precisa de "audio"—de que outra forma você ouviria seu hip hop coreano?

O elemento "audio" é usado para incorporar conteúdo de áudio em um documento. Assim como "video", "audio" usa src para vincular a fonte de áudio.

    <audio>
        <source src="iAmAnAudioFile.mp3" type="audio/mp3">
    </audio>

Neste exemplo, criamos um elemento "audio". Em seguida, criamos um elemento "source" para encapsular nosso link de áudio. Neste caso, iAmAnAudioFile.mp3 é nosso arquivo de áudio. Em seguida, especificamos o tipo usando type e nomeamos o tipo de áudio. Embora nem sempre seja necessário, é recomendável informar o tipo de áudio, pois ajuda o navegador a identificá-lo mais facilmente e determinar se esse tipo de arquivo de áudio é compatível com o navegador.

Vinculamos nosso arquivo de áudio ao navegador, mas agora precisamos fornecer controles. É aqui que entram os atributos. Os atributos fornecem informações adicionais sobre um elemento.

Os atributos nos permitem fazer muitas coisas diferentes em nosso arquivo de áudio. Existem muitos atributos para "audio", mas hoje vamos nos concentrar em controles e src.

* Controles: exibe automaticamente os controles de áudio no navegador, como reproduzir e silenciar.

* Src: especifica a URL do arquivo de áudio.

Como você deve ter notado, já usamos o atributo src no código de exemplo acima. A maioria dos atributos vai na tag de abertura de "audio". Por exemplo, veja como podemos adicionar a funcionalidade de reprodução automática e os controles de áudio:

    <audio autoplay controls>