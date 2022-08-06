# Bordas
Até agora, as tabelas que você criou foram um pouco difíceis de ler porque não têm bordas.

Em versões mais antigas do HTML, uma borda pode ser adicionada a uma tabela usando o atributo border e definindo-o como um número inteiro. Este inteiro representaria a espessura da borda.

    <table border="1">
    <tr>
        <td>73</td>
        <td>81</td>
    </tr>
    </table>

O código no exemplo acima está obsoleto, portanto, não o use. Destina-se a ilustrar convenções mais antigas que você pode encontrar ao ler o código de outros desenvolvedores.

O navegador provavelmente ainda interpretará seu código corretamente se você usar o atributo border, mas isso não significa que o atributo deva ser usado.

Usamos CSS para adicionar estilo a documentos HTML, porque isso nos ajuda a separar a estrutura de uma página de sua aparência. Você pode aprender mais sobre CSS em nossos cursos de CSS.

Você pode obter o mesmo efeito de borda de tabela usando CSS.

    table, td {
        border: 1px solid black;
    }

O código no exemplo acima usa CSS em vez de HTML para mostrar as bordas da tabela.