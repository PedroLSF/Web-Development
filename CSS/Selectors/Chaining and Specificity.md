# Chaining and Specificity
No último exercício, em vez de selecionar todos os elementos "h5", você selecionou apenas os elementos "h5" aninhados dentro dos elementos .description. Esse seletor CSS era mais específico do que escrever apenas h5. Adicionar mais de uma tag, classe ou ID a um seletor CSS aumenta a especificidade do seletor CSS.

Por exemplo, considere o seguinte CSS:

```css
p {
  color: blue;
}
 
.main p {
  color: red;
}
```

Ambas as regras CSS definem como um elemento "p" deve ser. Como .main p tem uma classe e um tipo p como seletor, apenas os elementos "p" dentro do elemento .main aparecerão em vermelho. Isso ocorre apesar de haver outra regra mais geral que diz que os elementos "p" devem ser azuis.