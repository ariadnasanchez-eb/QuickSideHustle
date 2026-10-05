# Brief de diseño: kit de baby shower del bosque

Para `design-director`. Ficha: `ficha.md`. Objetivo: un sistema reutilizable (mismas ilustraciones y la misma rejilla) que permita sacar variantes de color por código.

## Dirección visual

- Coherente con la lámina actual de la tienda: acuarela pastel, animales del bosque tiernos (no infantiles en exceso), mucho blanco, follaje suave.
- Tono: tranquilo, cálido, artesanal. Nada de purpurina, oro metálico ni globos.
- Composición: ilustración agrupada en la parte inferior o en una esquina, texto centrado arriba, márgenes amplios (≥0,5 in), legible a 1 metro en carteles.
- Fondo crema liso (imprime bien en casa; nada de fondos de acuarela a sangre en juegos, que gastan tinta).

## Paleta (neutral sage, MVP)

| Uso | Nombre | HEX |
|---|---|---|
| Fondo | Cream | `#FBF7F0` |
| Texto principal | Bark brown | `#5B4636` |
| Acento 1 | Sage | `#A8B5A0` |
| Acento 1 oscuro (líneas, cajas) | Deep sage | `#7D8B74` |
| Acento 2 (zorro) | Soft terracotta | `#D9A07B` |
| Acento 3 | Honey | `#E3C68C` |
| Detalle | Warm beige | `#E8DCCB` |

Variantes futuras (cambiar solo los acentos; la ilustración se recolorea por código o con tintes suaves):
- Blush: `#EBC9C0` / `#C99A8F`
- Dusty blue: `#A9BCC9` / `#7C93A3`

Contraste: el texto siempre en `#5B4636` sobre crema. Nunca texto en sage claro.

## Tipografías (Google Fonts, licencia OFL: uso comercial permitido)

| Rol | Fuente | Uso |
|---|---|---|
| Títulos de guion | **Great Vibes** (alternativa: Allura) | "Baby Shower", "Welcome", "Wishes" |
| Titulares y nombres | **Cormorant Garamond** SemiBold | Nombre de la mamá, títulos de juegos |
| Cuerpo y datos | **Quicksand** Medium | Fecha, dirección, instrucciones, líneas de juego |

Requisito: las tres deben estar en la biblioteca **gratuita** de Canva (verificarlo antes de montar las plantillas). Si alguna no está, sustituirla por una equivalente que sí esté. Máximo 3 fuentes.

## Ilustraciones a crear (PNG con transparencia, 300 ppp)

| ID | Elemento | Tamaño de trabajo | Se usa en |
|---|---|---|---|
| I1 | Zorro sentado (protagonista) | 2.400 px | Invitación, cartel de bienvenida, thumbnail |
| I2 | Conejo | 1.800 px | Invitación, Predictions, Wishes |
| I3 | Oso pequeño | 1.800 px | Cartel de bienvenida, Bingo |
| I4 | Ciervo | 1.800 px | Cartel de bienvenida, Quiz |
| I5 | Erizo | 1.200 px | Wishes, Cards & Gifts |
| I6 | Búho | 1.200 px | Quiz, Answer Key |
| F1 | Rama de helecho y follaje (3 variantes) | 1.800 px | Todas las piezas |
| F2 | Setas y bellotas (grupo pequeño) | 1.000 px | Juegos y reverso |
| F3 | Patrón de hojas en mosaico (tile) | 1.500 px | Reverso de invitación |
| C1 | Composición "grupo de animales" (I1+I2+I3+I4 + F1) | 3.000 px | Cartel de bienvenida, invitación, thumbnail |

Total: 6 animales + 3 recursos de follaje + 1 composición. Cada pieza reutiliza estos recursos; ninguna necesita una ilustración exclusiva.

Si se reutilizan los animales de la lámina actual, confirmar antes su licencia (ver riesgos en `ficha.md`). Si se generan con IA: mismo estilo de acuarela en todos (mismo prompt base y semilla), retoque manual de ojos y patas, y declarar el uso de IA en el listing.

## Composición por pieza

| Pieza | Tamaño | Composición |
|---|---|---|
| Invitación | 5x7 + 0,125 in de sangrado | C1 en el tercio inferior; arriba "Baby Shower" (Great Vibes), "honoring [Name]" (Cormorant), bloque de fecha, hora, lugar y RSVP (Quicksand). Textos editables, ilustración bloqueada |
| Reverso | 5x7 | F3 a sangre al 40 % de opacidad + caja crema central con texto opcional ("Registry" / "Bring a pack of diapers") |
| Cartel de bienvenida | 8x10, 11x14, 18x24 | "Welcome to" (Great Vibes) + "[Name]'s Baby Shower" (Cormorant, grande) + C1 abajo a ancho completo. Misma rejilla escalada; el texto del nombre aguanta hasta 14 caracteres sin romper la línea |
| Cards & Gifts | 8x10 | Título centrado + I5 + F2 abajo |
| Leave a Wish for Baby | 8x10 | Título + I2 + F1 enmarcando |
| Baby Bingo | 5x7 | Título arriba, cuadrícula 4x4 con casilla central "FREE" (I3 pequeña), líneas `#7D8B74` de 1 pt |
| Baby Predictions | 5x7 | 6 líneas: fecha, peso, longitud, color de pelo, se parecerá a, nombre. I2 en una esquina |
| Wishes for Baby | 5x7 | "Wishes for Baby" + 4 líneas + "From:" + I5 + F1 |
| Nursery Rhyme Quiz | 5x7 | 10 frases incompletas con línea, I6 en una esquina. Answer Key con la misma maqueta |

Juegos en dos formatos: 5x7 sencillo con sangrado y 2 por página US Letter con marcas de corte.

## Mockups (thumbnail + 8 imágenes, 2.000x2.000 px o 3.000x2.250 px)

1. **Thumbnail**: flat lay sobre fondo crema/lino con invitación, cartel de bienvenida y 2 juegos visibles; banner superior "EDITABLE IN CANVA · Woodland Baby Shower Bundle". Legible en tamaño miniatura en el móvil.
2. "What's included": cuadrícula de las 8 piezas con nombres.
3. Invitación en primer plano (anverso y reverso) con un sobre kraft.
4. Cartel de bienvenida en caballete en una fiesta (vista de 18x24).
5. Los 4 juegos en una mesa con bolígrafos.
6. "Edit in Canva from your phone": captura de un móvil con la plantilla abierta, en 3 pasos.
7. "Sizes & files": lista de archivos y tamaños.
8. Cartel "Leave a Wish" + tarjetas de deseos en un tarro.
9. (Venta cruzada) "Matching nursery name print": la lámina actual de la tienda con los mismos animales.

Mockups generados por código sobre fondos propios o con licencia comercial (sin fotos de stock sin licencia). Sin texto "sample" que tape el producto; marca de agua suave solo en la invitación de muestra.

## Entregables para producción

- Carpeta `assets/` con I1–I6, F1–F3 y C1 en PNG.
- Plantilla de rejilla (márgenes, tamaños de fuente por pieza) en un archivo de configuración para generar las variantes de color por código.
- Las 2 plantillas de Canva montadas y probadas con una cuenta gratuita.
