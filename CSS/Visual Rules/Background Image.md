# Background Image
CSS tem a capacidade de alterar o plano de fundo de um elemento. Uma opção é transformar o plano de fundo de um elemento em uma imagem. Isso é feito através da propriedade CSS background-image. Sua sintaxe fica assim:

```css
.main-banner {
  background-image: url('https://www.example.com/image.jpg');
}
```

1. A propriedade background-image definirá o plano de fundo do elemento para exibir uma imagem.
2. O valor fornecido para background-image é um url. O URL deve ser um URL para uma imagem. A url pode ser um arquivo dentro do seu projeto ou pode ser um link para um site externo. Para vincular a uma imagem dentro de um projeto existente, você deve fornecer um caminho de arquivo relativo. Se houvesse uma pasta de imagens no projeto, com uma imagem chamada montanhas.jpg, o caminho do arquivo relativo ficaria assim:

```css
.main-banner {
  background-image: url('images/mountains.jpg');
}
```