# Position: Relative
Uma maneira de modificar a posição padrão de um elemento é definindo sua propriedade position como relative.

Esse valor permite posicionar um elemento em relação à sua posição estática padrão na página da web.

```css
.green-box {
  background-color: green;
  position: relative;
}
```

Embora o código no exemplo acima instrua o navegador a esperar um posicionamento relativo do elemento .green-box, ele não especifica onde o elemento .green-box deve ser posicionado na página. Isso é feito acompanhando a declaração de position com uma ou mais das seguintes propriedades de deslocamento que moverão o elemento para longe de sua posição estática padrão:

* top - move o elemento para baixo a partir do topo.
* bottom - move o elemento para o topo a partir debaixo.
* left - move o elemento para longe do lado esquerdo (para a direita).
* right - move o elemento para longe do lado direito (para a esquerda).

Você pode especificar valores em pixels, ems ou porcentagens, entre outros, para discar exatamente até onde você precisa que o elemento se mova. Também é importante observar que as propriedades de deslocamento não funcionarão se a propriedade position do elemento for static.

```css
.green-box {
  background-color: green;
  position: relative;
  top: 50px;
  left: 120px;
}
```

No exemplo acima, o elemento da classe green-box será movido 50 pixels para baixo e 120 pixels para a direita, de sua posição estática padrão. A imagem abaixo mostra a nova posição da caixa.

![image](/Images/Pstatic.png)

O deslocamento do elemento relativo não afetará o posicionamento de outros elementos.