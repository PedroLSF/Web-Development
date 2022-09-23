# Important
!important pode ser aplicado a declarações específicas, em vez de regras completas. Ele substituirá qualquer estilo, não importa quão específico seja. Como resultado, quase nunca deve ser usado. Uma vez que !important é usado, é muito difícil substituir.

A sintaxe de !important em CSS é assim:

```css
p {
  color: blue !important;
}
 
.main p {
  color: red;
}
```

Como !important é usado no atributo color do seletor p, todos os elementos p aparecerão em azul, mesmo que haja um seletor .main p mais específico que define o atributo color como vermelho.

Uma justificativa para usar !important é quando se trabalha com várias folhas de estilo. Por exemplo, se estivermos usando o framework CSS Bootstrap e quisermos substituir os estilos de um elemento HTML específico, podemos usar a propriedade !important.