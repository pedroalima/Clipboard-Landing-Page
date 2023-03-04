# Frontend Mentor - Clipboard landing page solution 

## Índice

- [Visão geral](#visao-geral)
  - [O Desafio](#o-desafio)
  - [Screenshot](#screenshot)
- [Minha caminhada](#minha-caminhada)
  - [Propriedades](#propriedades)
  - [O que aprendi](#o-que-aprendi)
  - [Recursos](#recursos)
- [Autor](#autor)

## Visão Geral

### O Desafio

Os usuários devem ser capazes de:

- Vizualizar o layout ideal para o site, dependendo do tamanho da tela do dispositivo, mobile ou desktop
- Vizualizar os estados de foco para todos os elementos interativos na página

### Screenshot

<img src="screenshot.png" width="200">

## Minha caminhada

### Propriedades

- Mobile-first
- Semântica HTML5
- CSS Reaproveitável, limpo e flexível


### O que aprendi

Durante a elaboração do header, na criação dos botões, houve um pequeno desafio, o sombreamento. Pude observar que existiam dois estilos de sombra, não sabia dessa funcionalidade. A documentação de box-shadow da MDN foi crucial para o aprendizado.

Trechos de destaque:

```html
<a href="#" class="botao__primario">Download for iOS</a>
```

```css
.botao__primario {
    box-shadow: 
        1px 4px hsl(171, 65%, 36%),
        0px 5px 25px hsl(169, 57%, 72%);
}
```

### Recursos

- [Box Shadow CSS Generator](https://cssgenerator.org/box-shadow-css-generator.html) - Este é um site relevante para quem deseja aprender, aqui podemos simular diversos cenários de sombra.

## Autor

- LinkedIn - [Pedro A. Lima](https://www.linkedin.com/in/pedrolima626/)
