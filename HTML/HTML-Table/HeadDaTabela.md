# Head
No último exercício, os títulos da tabela foram mantidos dentro do corpo da tabela. Quando o corpo de uma tabela é seccionado, no entanto, também faz sentido seccionar os cabeçalhos das colunas da tabela usando o elemento 

    <thead>.

    <table>
        <thead>
            <tr>
            <th></th>
            <th scope="col">Saturday</th>
            <th scope="col">Sunday</th>
            </tr>
        </thead>
        <tbody>
            <tr>
            <th scope="row">Morning</th>
            <td rowspan="2">Work</td>
            <td rowspan="3">Relax</td>
            </tr>
            <tr>
            <th scope="row">Afternoon</th>
            </tr>
            <tr>
            <th scope="row">Evening</th>
            <td>Dinner</td>
            </tr>
        </tbody>
    </table>

No exemplo acima, o único elemento novo é "thead". Os títulos da tabela estão contidos dentro deste elemento. Observe que o cabeçalho da tabela ainda requer uma linha para conter os cabeçalhos da tabela.

Além disso, apenas os títulos das colunas vão para o elemento "thead". Podemos usar o atributo scope em elementos "th" para indicar se um elemento "th" está sendo usado como cabeçalho "row" ou "col".