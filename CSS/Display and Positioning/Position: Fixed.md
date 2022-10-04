# Position: Fixed
Quando a posição de um elemento é definida como absoluta, como no último exercício, o elemento rolará com o restante do documento quando o usuário rolar.

Podemos fixar um elemento em uma posição específica na página (independentemente da rolagem do usuário) definindo sua posição como fixa e acompanhando-o com as propriedades familiares de deslocamento superior, inferior, esquerda e direita.

```css
.title {
  position: fixed;
  top: 0px;
  left: 0px;
}
```

No exemplo acima, o elemento .title permanecerá fixo em sua posição independentemente de onde o usuário rolar na página, como na imagem abaixo:

![image](/Images/POFixed.png)

Essa técnica é frequentemente usada para barras de navegação em uma página da web.