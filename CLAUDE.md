# CLAUDE.md

Este archivo proporciona instrucciones a Claude Code al trabajar con el código de este repositorio.

## Descripción general

Sitio personal en GitHub Pages (`veronicagarayr.github.com`). Actualmente tiene un placeholder "en construcción". El objetivo es convertirlo en un **sitio portafolio profesional bilingüe** (español e inglés). Los cambios pusheados a `main` se publican automáticamente vía GitHub Pages — no hay paso de build.

## Estructura

- `index.html` — estructura y contenido de la página
- `style.css` — todos los estilos (separado del HTML para mantener los archivos ordenados)

Sin dependencias externas, sin JavaScript de build, sin toolchain. El CSS se vincula desde el HTML con `<link rel="stylesheet" href="style.css">`.

## Despliegue

Los cambios en `main` quedan en vivo en `https://veronicagarayr.github.com` en segundos via GitHub Pages. Para previsualizar localmente, abrir `index.html` directamente en el navegador.

## Objetivo del sitio

Portafolio profesional que presenta dos áreas de trabajo:

### 1. Diseño gráfico
Mostrar una selección representativa de trabajos en:
- **Diseño editorial** — publicaciones impresas y digitales de temática cultural y artística
- **Cartelismo** — carteles de películas y artes escénicas

### 2. Fotografía autoral
Mostrar trabajo fotográfico de autoría propia.

## Idioma y bilingüismo

- El sitio debe estar disponible en **español e inglés**
- Implementar un selector de idioma simple (toggle ES / EN)
- Todo el contenido textual debe tener ambas versiones
- El idioma por defecto puede ser español

## Convenciones de diseño

El estilo es **minimalista**, con carácter editorial y tipográfico fuerte:

- **Paleta de colores:** blanco y negro. Fondo blanco (`#ffffff`) o negro (`#000000`), texto en el color opuesto. Sin colores de acento salvo grises neutros (`#333`, `#666`, `#999`)
- **Tipografía:**
  - Palo seco geométrica o neogrotesca tipo Helvetica, Neue Haas Grotesk, Inter, o similares disponibles en Google Fonts (ej. `Inter`, `DM Sans`, `Barlow`)
  - Combinada con tipografía clásica serif (ej. `Playfair Display`, `EB Garamond`, `Cormorant`) para contraste y jerarquía
- **Estilo visual:** limpio, con mucho espacio en blanco, grid ordenado, sin ornamentos decorativos
- **Imágenes:** ocupan protagonismo, presentadas sin efectos ni filtros
- **Animaciones:** mínimas o inexistentes; si las hay, solo transiciones suaves de opacidad o posición
- **Responsive:** breakpoints en 768px (tablet), 576px (mobile grande), 375px (mobile pequeño)

## Notas adicionales

- No usar el esquema de colores cálido anterior (degradados naranjas/rosados) — fue reemplazado por el estilo monocromático descrito arriba
- Priorizar la legibilidad y el peso visual de las imágenes por sobre cualquier decoración
