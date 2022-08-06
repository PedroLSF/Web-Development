# Body
Com o tempo, uma tabela pode crescer para conter muitos dados e se tornar muito longa. Quando isso acontece, a tabela pode ser seccionada para facilitar o gerenciamento.

Tabelas longas podem ser seccionadas usando o elemento do corpo da tabela: 

    <tbody>.

O elemento 

    <tbody>

deve conter todos os dados da tabela, excluindo os títulos da tabela (mais sobre isso em um exercício posterior).

    <table>
            <tr>
            <th></th>
            <th>Saturday</th>
            <th>Sunday</th>
            </tr>
            <tbody>
                <tr>
                <th>Morning</th>
                <td rowspan="2">Work</td>
                <td rowspan="3">Relax</td>
                </tr>
                <tr>
                <th>Afternoon</th>
                </tr>
                <tr>
                <th>Evening</th>
                <td>Dinner</td>
                </tr>
            </tbody>
    </table>
