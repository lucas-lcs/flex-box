# Flex-box
Aprendendo os principais conceitos e propriedades do flex-box 

## Flexbox(Caixa Flexível)
É uma modulo do css que permite organizar, alinha e distribuir espaços entre container(elemento pai) em uma itens(elementos filhos).
> Segue o link com todoas as referencias que foram aplicadas nesse projeto. [Guia para Flex-box](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

##### Propriedade do box fleixvel do elemento pai, isso define se será inline ou bloco dependendo do valor
```css
container {
  "display": "flex"
}
```
#### Para alterar o valor padrão do eixo principal utilizaremos a propriedade: 
```css
.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
```

- resultado padrão sempre será inline
![layout inline](https://github.com/maykbrito/devlinks/assets/77105353/25999e59-4ced-4c3e-a64d-26868f4d878a)

1.1 inline reverse, posicionamos os elementos da direita para esquerda no eixo principal: 
```css
container {
  display: flex;
  flex-direction: row-reverse
}
``` 
- resultado row reverso
![row-reverse](https://github.com/lucas-lcs/flex-box/assets/121250838/f1976506-1723-4437-9918-15072cc292f1)

1.2  column, posicionamos o eixo principal em bloco: 
```css
container{
  display: flex;
  flex-direction: column
}
```
- resultado do block
![layout in block](https://github.com/lucas-lcs/flex-box/assets/121250838/9fcdd3a8-6a97-48d3-ab2c-568e3e87622b)

1.3 column-reverse, posicionamos os elementos de baixo para cima:
```css
container{
  display: flex;
  flex-direction: column
}
```
- resultado do block
![layout in block](https://github.com/lucas-lcs/flex-box/assets/121250838/84ea036c-77c3-4474-b4b5-431194a088f9)


