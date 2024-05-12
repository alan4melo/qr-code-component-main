# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./design/Solução%20feita%20por%20Alana.png)

### What I learned

Como centralizar um elemento no página: Essa técnica usa position: absolute para posicionar a div relativamente à janela do navegador e 
top: 50% e left: 50% para movê-la para o centro da página. 
Em seguida, transform: translate(-50%, -50%) é usado para ajustar a posição da div 
de modo que seu centro fique exatamente no meio da página, independentemente do tamanho da div. 
Isso funciona para desktop e dispositivos móveis:

```css
.div-centralizada {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

```

E como adicionar sombra na div usando o box-shadow:
Sendo os atributos em ordem: horizontal shadow, vertical shadow, blur, radius e color.


```css
.div {
box-shadow: 5px 5px 25px hsl(211, 25%, 77%);
}
```

## Continued development

Como distribuir melhor os elementos na página e no conteiner, de forma que o espaçamento, padding, borda e etc seja facilmente editáveis.

## Author

- Alana Melo 
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)