# Resumen ejecutivo — Barrido micro-SaaS

**Fecha de investigación:** 12 de agosto de 2026
**Mercado analizado:** España (principal) · UE (marco normativo) · EE. UU. (referencia de categoría)
**Fundador:** perfil principiante-técnico, 1 persona, presupuesto bajo, marca B2B Rubedo Systems, ventaja en hostelería y negocios locales.

---

## 1. Veredicto

**Mejor oportunidad: ID-01 — Auditoría de liquidaciones de plataformas de delivery para hostelería** (nombre provisional: **CUADRE**).

Detectar, cada quincena, el dinero que Glovo / Uber Eats / Just Eat descuentan al restaurante —penalizaciones, pedidos cancelados, cargos por "error de pedido", comisión sobre pedidos reembolsados— y convertirlo en una reclamación presentada **dentro del plazo contractual**, que es de un mes.

### Por qué gana

1. **El descuento está escrito en el contrato, no es una hipótesis.** Las condiciones de Glovo para partners establecen: comisión calculada sobre ventas brutas *"sin deducir las devoluciones de los usuarios; e independientemente de si se entregan con éxito"*; penalización de *"5€ + IVA por cada pedido cancelado"* imputable al partner; *"0,25 €/min"* por demora hasta 2,5 €; y en entrega incompleta/incorrecta el partner *"asumirá el coste total (impuestos incluidos)... más una penalización de hasta el 30% del valor de los productos + IVA"*.
2. **Hay una ventana que caduca.** Glovo: reclamación formal *"únicamente dentro del plazo de un (1) mes natural"*. Uber Eats: las disputas de *order error adjustments* deben presentarse **en 30 días** desde el pedido. Quien no revisa a tiempo, pierde el derecho. Eso convierte una tarea aburrida en algo con fecha.
3. **La categoría ya está validada económicamente en EE. UU.** Voosh, Deliverect Reclaim, RevGuard, DeliverGuard y DTiQ viven de esto; el CEO de Voosh cifra en **2,5–3 % de la facturación total** el dinero atrapado en disputas, y un franquiciado de McDonald's declara reclamar **~500 $ por local y mes**. En España **no he encontrado ningún competidor equivalente**.
4. **Los compradores son localizables hoy y el fundador ya está dentro del nicho.** El directorio de prospectos es la propia app de Glovo/Uber Eats filtrada por ciudad, más su red personal de propietarios de varios locales.
5. **Se puede vender antes de programar y cobrar a éxito.** "Dame tus tres últimas liquidaciones; si no encuentro dinero, no pagas."

### Prueba principal

Cláusulas 3.1, 4.1.e, 4.1.f, 4.1.g y 4.1.h de las condiciones de partner de Glovo (fuente primaria, consultada 12/08/2026) + política de disputas de Uber Eats con límite de 30 días + evidencia de categoría rentable en EE. UU.

### Riesgo principal

**Que en España el importe recuperable por local sea pequeño.** Todo el modelo depende de que la fuga media por local y mes supere los ~150 €. La evidencia de magnitud es estadounidense; en España tengo las cláusulas (hecho) pero **no los importes reales** (hipótesis). Si al auditar 5 liquidaciones reales la fuga media es <60 €/mes, la idea se abandona.

Riesgo secundario: dependencia de plataformas externas (formato de liquidaciones, condiciones de servicio, posible cierre del canal de disputa).

### Acción en las próximas 24 horas

Escribir por WhatsApp a **8 propietarios de hostelería de la red del fundador** con este texto:

> "Estoy montando un servicio que revisa las liquidaciones de Glovo/Uber Eats y reclama lo que te descuentan mal. Necesito 3 restaurantes para probarlo gratis esta semana. ¿Me pasas las liquidaciones de los últimos 3 meses? Si encuentro dinero, lo reclamamos y me llevo el 25 % de lo que recuperes. Si no encuentro nada, no me debes nada y te digo que no sigas."

Objetivo del día 1: **3 juegos de liquidaciones reales en la mano**.

---

## 2. Estado de la evidencia

| Nivel | Contenido |
|---|---|
| **Hecho verificado** | Las cláusulas contractuales de Glovo; el plazo de 30 días de Uber Eats; comisiones del 15–35 %; existencia y financiación de la categoría en EE. UU.; ausencia de competidor equivalente en España tras búsqueda dirigida. |
| **Inferencia razonable** | Que el patrón de cargos por error/reembolso se comporte en España como en EE. UU.; que un operador de 3–10 locales no revisa línea a línea. |
| **Hipótesis pendiente** | El importe medio recuperable por local y mes en España. La tasa de éxito real de las reclamaciones ante Glovo/Uber Eats España. Si las plataformas permiten un usuario delegado en el portal de partner. |

**No estoy declarando la oportunidad validada.** Está *lista para una prueba comercial de 7 días* que puede ejecutarse sin escribir código.

---

## 3. Recomendación única

**VALIDAR ANTES DE DECIDIR** (7 días, coste ~0 €).
No abrir ningún otro proyecto en paralelo. Si la prueba de 7 días arroja ≥3 restaurantes con fuga media ≥150 €/mes y ≥1 acuerdo de éxito firmado, se pasa a MVP de 21 días. Si no, se descarta y el siguiente candidato en la lista es ID-02 (Ley 10/2025 de atención a la clientela), que tiene fecha límite el 28 de diciembre de 2026.
