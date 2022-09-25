# Margin Collapse
Como você viu, padding é espaço adicionado dentro da borda de um elemento, enquanto margin é espaço adicionado fora da borda de um elemento. Uma diferença adicional é que as margens superior e inferior, também chamadas de margens verticais, são recolhidas, enquanto o preenchimento superior e inferior não.

As margens horizontais (esquerda e direita), como preenchimento, são sempre exibidas e somadas. Por exemplo, se dois divs com ids #div-one e #div-two estiverem próximos um do outro, eles estarão tão distantes quanto a soma de suas margens adjacentes.

```css
#img-one {
  margin-right: 20px;
}
 
#img-two {
  margin-left: 20px;
}
```

Neste exemplo, o espaço entre as bordas #img-one e #img-two é de 40 pixels. A margem direita de #img-one (20px) e a margem esquerda de #img-two (20px) somam para fazer uma margem total de 40 pixels.

Ao contrário das margens horizontais, as margens verticais não adicionam. Em vez disso, a maior das duas margens verticais define a distância entre os elementos adjacentes.

```css
#img-one {
  margin-bottom: 30px;
}
 
#img-two {
  margin-top: 20px;
}
```

Neste exemplo, a margem vertical entre os elementos #img-one e #img-two é de 30 pixels. Embora a soma das margens seja de 50 pixels, a margem é recolhida, de modo que o espaçamento depende apenas da #img-one margem inferior.

Pode ser útil pensar no colapso das margens verticais como uma pessoa baixa tentando empurrar uma pessoa mais alta. A pessoa alta tem braços mais longos e pode empurrar facilmente a pessoa baixa, enquanto a pessoa com braços curtos não consegue alcançar a pessoa com braços longos.

![image](/Images/VerticalMargin.png)
