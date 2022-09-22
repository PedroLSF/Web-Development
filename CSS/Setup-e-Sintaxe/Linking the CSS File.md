# Linking the CSS Fil
Perfeito! Separamos com sucesso a estrutura (HTML) do estilo (CSS), mas a página da web ainda parece sem graça. Por quê?

Quando os códigos HTML e CSS estão em arquivos separados, os arquivos devem ser vinculados. Caso contrário, o arquivo HTML não poderá localizar o código CSS e o estilo não será aplicado.

Você pode usar o elemento "link" para vincular arquivos HTML e CSS. O elemento "link" deve ser colocado no cabeçalho do arquivo HTML. É uma tag de fechamento automático e requer os seguintes atributos:

1. href — Como o elemento âncora, o valor deste atributo deve ser o endereço, ou caminho, para o arquivo CSS.
2. rel — Este atributo descreve a relação entre o arquivo HTML e o arquivo CSS. Como você está vinculando a uma folha de estilo, o valor deve ser definido como folha de estilo.

Ao vincular um arquivo HTML e um arquivo CSS, o elemento "link" terá a seguinte aparência: