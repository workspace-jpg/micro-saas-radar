# Plan de validación de 7 días — ID-01 CUADRE

**Del 12 al 19 de agosto de 2026. Coste en dinero: 0 €. Coste en tiempo: 3–5 h/día. Sin escribir una línea de código.**

Objetivo único: **saber cuántos euros al mes pierde de verdad un restaurante español en las liquidaciones de las plataformas.** Todo lo demás es secundario.

---

## Lista de prospectos: 30–50 nombres

**Método (reproducible en 90 minutos):**

1. **Red personal (objetivo: 15–25 nombres).** Recorrer la agenda del móvil y de WhatsApp y marcar a todo propietario o encargado de hostelería. Priorizar quien tenga **más de un local**.
2. **Apps de delivery por ciudad (objetivo: 20–30 nombres).** Abrir Glovo y Uber Eats con la ubicación fijada en la ciudad objetivo, recorrer las categorías de mayor volumen (hamburguesa, pizza, sushi, poke, kebab) y anotar **las marcas que aparecen con varios locales**: esas son las que tienen volumen y no tienen departamento financiero.
3. **Cruce con Google Maps** para obtener teléfono, web y nombre del propietario cuando aparezca en las reseñas.
4. **Asociaciones provinciales de hostelería** (Hostelería de España y federaciones) para conseguir presentaciones cuando el contacto frío no funcione.

**Ficha mínima por prospecto:** nombre comercial · nº de locales · plataformas en las que aparece · contacto · vía de acceso (frío / conocido / referido) · estado.

*Nota de honestidad: no he verificado nombres concretos de empresas en esta investigación para no fabricar datos. El listado se genera con el método anterior en menos de dos horas, y los diez enlaces públicos de partida están en `06-nichos-prospeccion.csv`.*

---

## Mensaje de contacto

**WhatsApp / cara a cara (red personal):**

> "Oye, estoy montando un servicio que revisa las liquidaciones de Glovo y Uber Eats y detecta lo que te descuentan mal: pedidos cancelados, penalizaciones, comisión sobre pedidos que se reembolsaron. Necesito 3 restaurantes para probarlo esta semana. ¿Me pasas las liquidaciones de los últimos 3 meses? Si encuentro dinero, lo reclamamos juntos y me llevo el 25 %. Si no encuentro nada, no me debes nada y te lo digo claro."

**Correo/frío (2 líneas, sin adjuntos):**

> Asunto: *lo que Glovo te descontó en julio*
> "Reviso liquidaciones de plataformas de delivery y busco cargos reclamables. Lo hago gratis con tus 3 últimas liquidaciones y te digo en 48 h si hay dinero que recuperar. Solo cobro si recuperas. ¿Te las miro?"

---

## Cinco preguntas de entrevista (abiertas, no dirigidas)

1. ¿Cómo sabes cada mes cuánto has vendido realmente por plataformas y cuánto te ha llegado al banco?
2. Cuéntame la última vez que algo no te cuadró en una liquidación. ¿Qué hiciste?
3. ¿Qué pasa en tu local cuando un cliente reclama un pedido incompleto?
4. ¿Quién revisa las liquidaciones y cuánto tiempo le dedica?
5. Si te dijera que el mes pasado te descontaron X € de más, ¿qué harías con esa información?

**Prohibido preguntar:** "¿pagarías por una herramienta que...?"

---

## Prototipo

No hay software. El entregable es un **informe de una página** (Excel + PDF) por restaurante:

- Comisión efectiva real por plataforma frente a la pactada.
- Tabla de cargos detectados: concepto, fecha, importe, motivo por el que es reclamable, **días que quedan para reclamar**.
- Total reclamable.
- Texto de la reclamación listo para copiar y enviar.

---

## Oferta y precio que se intenta cobrar

- **Auditoría inicial:** gratuita (es el anzuelo y la fuente de datos).
- **Éxito:** **25 % de lo recuperado**, facturado cuando el cliente cobra o ve el abono en la siguiente liquidación.
- **Compromiso que se pide:** acuerdo por escrito —aunque sea un WhatsApp explícito— de que si se recupera, se paga. Eso es lo que convierte un cumplido en una validación.

---

## Calendario

| Día | Tarea | Resultado esperado | Tiempo | Criterio para continuar |
|---|---|---|---|---|
| **1 · Mié 12** | Listar 30–50 prospectos con el método de arriba. Enviar 8 mensajes a la red personal. | Lista hecha, 8 mensajes fuera | 3 h | ≥2 respuestas |
| **2 · Jue 13** | Recoger liquidaciones. Enviar 15 mensajes más. Preparar la plantilla de auditoría en Excel. | ≥3 juegos de liquidaciones reales | 4 h | ≥3 juegos recibidos |
| **3 · Vie 14** | Auditar a mano el primer juego. Anotar cada tipo de cargo encontrado. | Primer informe + catálogo de reglas | 5 h | Se detecta ≥1 cargo reclamable |
| **4 · Lun 17** | Auditar los juegos 2 y 3. Consolidar la cifra media de fuga por local y mes. | 3 informes + la cifra clave | 5 h | **Fuga media ≥150 €/local/mes** |
| **5 · Mar 18** | Entregar los informes en persona o por videollamada. Hacer las 5 preguntas. Pedir el acuerdo de éxito. | ≥1 acuerdo de éxito por escrito | 4 h | ≥1 acuerdo |
| **6 · Mié 19** | Presentar la primera reclamación real ante la plataforma con el cliente. Contactar 10 prospectos más con el caso real. | Reclamación enviada, 10 contactos nuevos | 4 h | Reclamación admitida a trámite |
| **7 · Jue 20** | Decisión. Escribir el informe de resultados en este mismo directorio. | GO / NO-GO documentado | 2 h | — |

**Mínimo de conversaciones reales exigido: 8** (no mensajes enviados: conversaciones).

---

## Criterios de éxito (los tres a la vez)

1. **≥3 restaurantes** auditados con liquidaciones reales.
2. **Fuga media ≥150 € por local y mes** en cargos reclamables o comisión mal aplicada.
3. **≥1 acuerdo de éxito por escrito** y **≥1 reclamación presentada**.

## Criterios de abandono

- Fuga media **<60 €/local/mes** → la economía no existe. Se abandona ID-01 y se pasa a ID-02.
- Nadie envía liquidaciones tras 8 conversaciones → el problema no le importa a nadie, o el fundador no tiene el acceso que cree tener. Igualmente decisivo.
- Las plataformas rechazan de plano las reclamaciones en España sin proceso de revisión → el producto queda reducido a un informe informativo; se replantea el precio (solo suscripción baja) o se abandona.

## Qué NO cuenta como validación

Me gusta la idea · suena interesante · avísame cuando lo tengas · un registro en una landing · un "me apunto al beta".

## Evidencia que autoriza empezar el MVP

Los tres criterios de éxito cumplidos **y** un catálogo de al menos **cinco reglas de detección** escritas a partir de liquidaciones reales. Sin esas cinco reglas, no hay producto que programar.

---

## Después del día 7 (solo si hay GO)

- Días 8–30: MVP de tres funciones descrito en `05-top-3.md`.
- Los tres primeros clientes entran a **49 €/local/mes + 20 % de éxito**, con precio congelado 12 meses a cambio de permitir usar su caso (anonimizado) en la venta.
