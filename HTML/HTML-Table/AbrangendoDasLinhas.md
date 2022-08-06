# Abrangendo Linhas
Os dados também podem abranger várias linhas usando o atributo rowspan.

O atributo rowspan é usado para dados que abrangem várias linhas (talvez um evento continue por várias horas em um determinado dia). Ele aceita um número inteiro (maior ou igual a 1) para denotar o número de linhas que abrange.

Exemplo:

    <table>
        <tr> <!-- Row 1 -->
            <th></th>
            <th>Saturday</th>
            <th>Sunday</th>
        </tr>
        <tr> <!-- Row 2 -->
            <th>Morning</th>
            <td rowspan="2">Work</td>
            <td rowspan="3">Relax</td>
        </tr>
        <tr> <!-- Row 3 -->
            <th>Afternoon</th>
        </tr>
        <tr> <!-- Row 4 -->
            <th>Evening</th>
            <td>Dinner</td>
        </tr>
    </table>

No exemplo acima, há quatro linhas:

1. A primeira linha contém uma célula vazia e os dois cabeçalhos de coluna.
2. A segunda linha contém o título da linha Morning, juntamente com Work, que abrange duas linhas na coluna Saturday. A entrada “Relax” abrange três linhas na coluna de Sunday.
3. A terceira linha contém apenas o título da linha Afternoon.
4. A quarta linha contém apenas a entrada Dinner, já que “Relaxar” se estende até a célula próxima a ela.
Se você quiser ver como o navegador interpreta o código acima, sinta-se à vontade para copiá-lo e colá-lo no editor de código para entendê-lo um pouco melhor.