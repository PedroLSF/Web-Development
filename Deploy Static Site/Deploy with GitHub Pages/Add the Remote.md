# Add the Remote
Em seguida, o Git precisa saber qual repositório armazenará o conteúdo do seu site.

Nesse caso, o repositório será aquele que você criou no GitHub anteriormente.

Para especificar o repositório usando o Git, teremos que adicionar o controle remoto e rotulá-lo como origem.

O controle remoto é a URL do repositório que armazenará o conteúdo do seu site.

A origem é um alias para o controle remoto. Você pode pensar em um alias como uma abreviação ou um nome substituto. Isso significa que, em vez de ter que digitar sempre a URL remota longa várias vezes, você pode simplesmente referir-se a ela como origem mais tarde.

No terminal, você pode adicionar o controle remoto com o seguinte comando:

    git remote add origin https://github.com/your-user-name/your-user-name.github.io.git

No exemplo acima, https://github.com/your-user-name/your-user-name.github.io.git é a URL remota que se refere ao repositório que você criou no GitHub anteriormente. 

Novamente, você substituiria seu nome de usuário pelo seu nome de usuário real do GitHub.

Nota: Certifique-se de que o URL do seu controle remoto esteja digitado corretamente. Caso contrário, você corre o risco de uma implantação com falha.


NOTA:

Importante: Se você cometer um erro acidentalmente ao adicionar a URL remota, poderá recomeçar e remover o controle remoto com o seguinte comando:

    git remote rm origin

Confirme se o controle remoto foi adicionado com sucesso, digitando o seguinte:

    git remote -v

Este comando lista todos os controles remotos do Git e seus URLs correspondentes.