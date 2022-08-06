# Abrangência
E se a tabela contiver dados que abrangem várias colunas?

Por exemplo, um calendário pessoal pode ter eventos que abrangem várias horas ou até vários dias.

Os dados podem abranger colunas usando o atributo 

    colspan. 

O atributo aceita um número inteiro (maior ou igual a 1) para indicar o número de colunas que ele abrange.

    <table>
        <tr>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
        </tr>
        <tr>
            <td colspan="2">Out of Town</td>
            <td>Back in Town</td>
        </tr>
    </table>

No exemplo acima, os dados Out of Town abrangem os cabeçalhos das tabelas de Monday e Tuesday usando o valor 2 (duas colunas). Os dados de Back in Town aparecem apenas sob o título Wednesday.