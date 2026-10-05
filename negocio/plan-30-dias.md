# Plan de 30 días (6 de octubre – 4 de noviembre de 2026)

Basado en `negocio/auditoria-2026-10-05.md`. Pensado para una sesión semanal de 2–4 horas; Claude hace la producción con código y la propietaria revisa, publica y aprueba.

**Restricción (decisión de la propietaria, 5/10/2026):** de momento no se abre ninguna tienda nueva, para no pagar la tarifa de apertura. Todo va en **VelvetAcornStudio** (inglés, nursery en acuarela con animales del bosque, 1 listing, 2 ventas).

## Prioridades

- **P0 — Línea bilingüe español-inglés en VelvetAcornStudio: 2 sets de láminas publicados antes del 20 de octubre.** Es la idea con mejor score (73) y la que encaja con la tienda: mismo público, idioma y estilo.
- **P1 — Convertir la lámina de nombre personalizado en plantilla editable** a 7,99–9,99 $ y sacar una versión bilingüe, para que la tienda pase de 1 a 4–5 listings sin trabajo por pedido.
- **P2 — Validar con eRank el planificador para opositores y las rutinas visuales**, sin producir. El planificador queda **APARCADO** hasta que la tienda genere ventas que paguen una segunda tienda en español; meterlo en una tienda de nursery en inglés confundiría a los dos públicos.

Qué **no** hacer este mes: abrir tienda nueva, planificador para autónomos, colorear para KDP, kit de comunión, Etsy Ads de pago, redes sociales distintas de Pinterest.

## Semana 1 (6–12 oct): validar y preparar

- [ ] Exportar las estadísticas de VelvetAcornStudio de los últimos 90 días (visitas, favoritos, keywords). (Propietaria, 10 min.)
- [ ] Contratar eRank un mes (~10 €) y sacar volumen y competencia de: "spanish nursery decor", "bilingual nursery", "spanish lullaby print", "spanish nursery print", "te quiero hasta la luna", "spanish alphabet print", "nursery name print"; y para P2: "planificador oposiciones", "agenda opositor", "rutinas visuales". (Propietaria, 30 min.)
- [ ] Decisión del CEO con esos datos: qué 2 sets bilingües van primero. Una keyword con volumen casi nulo pasa a APARCAR.
- [ ] `/crear-producto` de los 2 sets: ficha, brief de diseño con el estilo acuarela del bosque de la tienda y listing en `negocio/productos/laminas-bilingues/`. (Claude.)

## Semana 2 (13–19 oct): producir y lanzar P0

- [ ] Producir los 2 sets de 3–6 láminas (por ejemplo nanas tradicionales de dominio público y abecedario decorativo con Ñ), en tamaños de impresión habituales en EE. UU. (8x10, 11x14, 16x20) y A4. Medir horas reales. (Claude + revisión de la propietaria.)
- [ ] Mockups, título, 13 tags y descripción en inglés con el ángulo bilingüe. (Claude.)
- [ ] `product-qa`: veredicto APTO, con QA de idioma (acentos, Ñ, sin regionalismos raros) y derechos de las letras comprobados.
- [ ] Publicar a 8–12 $ el set, con un descuento de lanzamiento de dos semanas. (Propietaria, 30 min.)

## Semana 3 (20–26 oct): P1 y marketing

- [ ] Convertir la lámina de nombre en plantilla editable y crear su versión bilingüe ("nombre + significado" o "Te quiero hasta la luna" con nombre). (Claude prepara, la propietaria publica.)
- [ ] Bundle de los 2 sets a 20–25 $.
- [ ] Una acción de marketing: 5 pines en Pinterest por producto, programados.

## Semana 4 (27 oct – 2 nov): medir

- [ ] Primera `/revision-semanal` con los datos de Etsy: visitas, favoritos, ventas y conversión por listing.
- [ ] Registrar aprendizajes en `negocio/aprendizajes.md` (horas reales por producto, keywords que traen visitas).
- [ ] Decidir el siguiente set bilingüe o, si hay ventas, reconsiderar la tienda en español para el planificador.

## Cómo sabremos si funciona (día 30)

| Métrica | Señal para seguir | Señal para parar |
|---|---|---|
| Visitas por listing nuevo | ≥100 en las 2 primeras semanas | <20 |
| Favoritos | ≥5 % de las visitas | ~0 |
| Ventas | ≥5 en total | 0 con ≥200 visitas (problema de oferta o presentación) |
| Horas por set nuevo | ≤3 h | >6 h |

Con muestra pequeña no se cambia de rumbo: un listing nuevo necesita 6–8 semanas para juzgarse. Al día 30 se decide optimizar, crear más variantes o aparcar.

## Presupuesto (<100 €)

eRank 1 mes ~10 € · ~10 listings ~2 € · reserva ~25 € · tienda nueva 0 € · Canva Pro 0 € (se genera con código). Total ≈ 40 €.

## Datos que faltan

- Estadísticas de VelvetAcornStudio (90 días).
- Volúmenes de eRank (semana 1).
- Horas reales del primer set.
