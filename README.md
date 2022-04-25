# Anotações
Informações e curiosidades sobre front e back.

## Links

**[@Shape Divider](https://www.shapedivider.app/)** Plataforma para estilização de CSS.

**[@Spline Tool](https://spline.design/)** Plataforma para criar interações em 3D e adicionar aos sites (disponível também para ReactJs).

## Comandos

Tamanhos utilizados no desenvolvimento responsivo.

```bash
  #Mobile
  @media only screen and(max-widht: 600px) {
    .....
  }

  #Tablet
  @media only screen and(max-widht: 768px) {
    .....
  }

  #Laptop
  @media only screen and(max-widht: 992px) {
    .....
  }

  #LargScreen
  @media only screen and(max-widht: 1200px) {
    .....
  }
```

Checando o tema de preferência do usuário:

```bash
  # Em CSS
  @media (prefers-color-scheme: dark) {
    .....
  }
  
  @media (prefers-color-scheme: light) {
    .....
  }
```

```bash
  # Em JS
  const query = window,matchMedia(
    '(prefers-color-scheme: dark)'
  );
  
  # Verdadeiro caso a preferência seja dark
  query.matches;
  
  # Para acompanhar se houver um evento de mudança
  query.addEventListener('change', res => {
    res.matches;
  });
```

Criando estilos alternados em uma lista de elementos:

```bash
  li:nth-child(odd) {
    background-color: #FFFFFF;
    .....
  }
  
  li:nth-child(even) {
    background-color: #000000;
    .....
  }
```

## Bibliotecas JS

**Glide.js** Slider JavaScript para criar carrosséis modernos e com deslizamento suave.

**Croppie** Um plugin JS para cortar Imagens rapidamente com diversas configurações.

## UI/UX

**[@Jitter Video](https://jitter.video/)** Plataforma de criação de vídeos e animações curtas, com diversos templates disponíveis.
