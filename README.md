# Rocketseat Responsividade 💜

Este projeto visa aprendar os conceitos de **responsividade em layouts**, tornando-os flexíveis para diferentes dispositivos (smartphones, tablets, desktops e até impressão). A ideia é adaptar elementos do layout de forma fluida, ajustando-se ao tamanho da tela e garantindo uma experiência de usuário consistente.

## Conteúdos Abordados

### Sobre o Projeto
Esta é uma Masterclass da Rocketseat para iniciantes em responsividade, onde você aprenderá a criar layouts flexíveis e fluidos. 🚀

#### Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript

### 1. Unidades de Medida CSS

Trabalhamos com diferentes unidades de medida para layouts fixos e fluidos:

- **Layout Fixo**: `px` - Pixels
- **Layout Fluido**: `%`, `auto`, `vh`, `vw`
- **Textos Fixos**: `px` (1px = 0.75pt)
- **Textos Fluidos**: `em`, `rem`

### 2. Media Queries CSS

Utilizamos **Media Queries** para aplicar estilos específicos de acordo com o tamanho da tela:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
@media (max-width: 320px) {
  #form h3 {
    font-size: 2rem;
  }
}

```
### 3. Atributo HTML media
É possível usar o atributo media para carregar arquivos CSS específicos:
```html

<link rel="stylesheet" href="responsive.css" media="screen and (max-width: 768px)">
<link rel="stylesheet" href="print.css" media="print">

```
### 4. Imagens Responsivas

Usamos a tag <picture> para exibir diferentes versões de imagem conforme o tamanho da tela, priorizando SVG sempre que possível.

```html

<picture class="image">
    <source media="(min-width: 768px)" srcset="large-image.jpg">
    <source media="(min-width: 320px)" srcset="medium-image.jpg">
    <img src="default-image.jpg" alt="Imagem Responsiva">
</picture>
```

git clone https://github.com/Guilherme-Sbizero/Rockeatseat.git
