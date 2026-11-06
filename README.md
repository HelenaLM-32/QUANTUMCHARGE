# Quantum Charge

![Imagen de campaña de Quantum Charge](public/images/tophero.png)

**Caso de estudio conceptual de branding, packaging y desarrollo web** para una
marca ficticia de bebidas energéticas. El sitio explora cómo trasladar una
identidad visual con referencias a ciencia y deporte desde el envase hasta una
experiencia digital responsive.

> La marca, los productos y el contenido promocional son ficticios. El sitio no
> vende productos ni procesa compras o suscripciones.

## Mi contribución

- Dirección visual y desarrollo front-end.
- Diseño de una identidad y una colección conceptual de cuatro envases.
- Diseño y desarrollo de una landing y una página de proceso creativo.
- Maquetación responsive y consideraciones de accesibilidad, como navegación
  por teclado, enlace para saltar al contenido y respeto por `prefers-reduced-motion`.

## Tecnologías

- [Astro](https://astro.build/)
- HTML semántico y CSS
- Google Fonts: Bebas Neue y Space Mono

## Estructura del sitio

- `/` — presentación de marca y colección de sabores.
- `/proceso/` — caso de estudio con el brief, sistema visual, packaging y
  aplicación digital.

## Desarrollo local

Requiere Node.js 22.23.4 o posterior.

```sh
npm ci
npm run dev
```

Abre `http://localhost:4321`.

## Validación y producción

```sh
npm run check
npm run build
npm run preview
```

`npm run check` valida los componentes y tipos de Astro. La compilación estática
se genera en `dist/`.
