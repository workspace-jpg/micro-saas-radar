# Radar de oportunidades micro-SaaS — Rubedo Systems

Investigación de oportunidades de micro-SaaS para el mercado español, con validación previa a cualquier desarrollo.

- **Contexto del fundador:** una persona, nivel técnico principiante asistido por Claude Code, presupuesto bajo, prioridad = primeros ingresos, MVP de 2 a 4 semanas, un solo proyecto activo.

## Barridos realizados

| Barrido | Fecha | Alcance | Candidatos | Resultado |
|---|---|---|---|---|
| [**#1**](2026-08-12/) | 12/08/2026 | Señales regulatorias, hostelería y negocio local | 18 → 10 → 3 | **ID-01 (76/100)** — recomendación única |
| [**#2**](2026-08-12-barrido-2/) | 12/08/2026 | Terreno nuevo: plataformas y APIs, precios de SaaS, tareas automatizables, verticales fuera de hostelería | 18 → 10 → 3 | Mejor candidato **N-04 (64/100)**. **No supera a ID-01** |

**Conclusión combinada: ID-01 sigue siendo el proyecto único.**

El barrido #2 tuvo su valor en un descarte, no en una idea. La señal más potente de los dos barridos era el **DeCA** —documento de control del transporte, obligatorio el 5 de octubre de 2026, 101.326 empresas afectadas, solo el 17 % preparadas, con inmovilización del vehículo como sanción— y está **ocupada**: doce proveedores en mercancías (uno a 9,90 €/mes, otro gratis hasta la fecha límite) y, en viajeros, la propia patronal del sector (CONFEBUS) distribuyendo su herramienta RutaBUS a ~2.000 asociados.

De ahí salió una regla de descarte permanente: **cuando una obligación legal afecta de forma masiva a un sector organizado, la patronal saca la herramienta gratis antes de la fecha límite.** Ya son dos casos confirmados (Hostelería de España con el desperdicio alimentario, CONFEBUS con la hoja de ruta digital).

> **Estado actual: ID-01 NO está validado.** Está listo para una prueba comercial de 7 días que no requiere escribir código. Este repositorio existe para que la tesis sea auditada y atacada antes de invertir tiempo en construir.

---

## Foco: ID-01 — CUADRE

**Auditoría de liquidaciones de plataformas de delivery para hostelería.**

Revisar cada quincena lo que Glovo, Uber Eats y Just Eat descuentan al restaurante —penalizaciones, pedidos cancelados, cargos por error, comisión sobre pedidos reembolsados— y convertirlo en una reclamación presentada **dentro del plazo contractual, que caduca en 30 días**.

Puntuación: **76/100**. Confianza: **media**.

### La evidencia que sostiene la tesis

**1. Los descuentos están en el contrato, no son una sospecha.**
Fuente primaria: [condiciones de partner de Glovo](https://glovoapp.com/docs/es/legal/terms-partners/), consultadas el 12/08/2026.

| Cláusula | Contenido | Efecto |
|---|---|---|
| 3.1 | Comisión sobre ventas brutas *"sin deducir las devoluciones de los usuarios; e independientemente de si se entregan con éxito"* | Se paga comisión por pedidos reembolsados o no entregados |
| 4.1.e | *"0,25 €/min"* por demora >10 min, máx. 2,5 €/pedido | Micro-penalizaciones difíciles de auditar |
| 4.1.f | Entrega incompleta o incorrecta: *"asumirá el coste total (impuestos incluidos)… más una penalización de hasta el 30 % del valor de los productos + IVA"* | Un pedido de 40 € puede costar 52 € |
| 4.1.g | *"penalización de 5 € + IVA por cada pedido cancelado"* imputable al partner | Acumulativo y silencioso |
| 4.1.h | Reclamación *"únicamente dentro del plazo de un (1) mes natural"* | **El derecho caduca** |
| 3.6 | Liquidación quincenal | Dos oportunidades de revisión al mes |

**2. La ventana de reclamación de Uber Eats es de 30 días** desde el pedido, con herramienta self-serve en Uber Eats Manager y resolución en 5–14 días hábiles ([Uber Help](https://help.uber.com/en/merchants-and-restaurants/article/managing-refunds-for-missing-or-incorrect-orders?nodeId=abc0c3e7-9687-4a00-a956-2c8a16cf0b7e)).

**3. La categoría ya es rentable en EE. UU.** El CEO de Voosh cifra en **2,5–3 % de la facturación total** el dinero atrapado en disputas; un franquiciado de McDonald's declara reclamar **~500 $ por local y mes** ([Restaurant Business Online](https://www.restaurantbusinessonline.com/technology/restaurants-say-theyre-bearing-brunt-delivery-chargebacks)). Actores: Voosh, Deliverect Reclaim, RevGuard, DeliverGuard, DTiQ.

**4. En España no se ha encontrado competidor equivalente.** Nubceo concilia TPV, banco y medios de pago. MyChefTool ataca la comisión empujando el canal propio. Haddock controla escandallos y albaranes. Ninguno audita línea a línea la liquidación de la plataforma ni redacta la reclamación dentro del plazo.

### Economía

- **ICP:** grupo de restauración de 3–15 locales, >5.000 €/mes en plataformas, sin departamento financiero.
- **Precio fase 1:** 25–30 % de lo recuperado (sin coste si no se encuentra nada).
- **Precio fase 2:** 49 €/local/mes + 20 % de éxito ≈ 180 €/cliente/mes.
- **MRR:** 6 clientes = 1.000 € · 17 = 3.000 € · 28 = 5.000 €.
- **MVP:** 3 funciones, **cero integraciones obligatorias**, dificultad 4/10, coste de infraestructura 0–60 €/mes.

### Separación explícita de evidencia

| Nivel | Contenido |
|---|---|
| **Hecho verificado** | Cláusulas contractuales de Glovo · plazo de 30 días de Uber Eats · comisiones del 15–35 % · existencia de la categoría en EE. UU. · ausencia de competidor español tras búsqueda dirigida |
| **Inferencia razonable** | Que el patrón de cargos por error se comporte en España como en EE. UU. · que un operador de 3–10 locales no revisa línea a línea |
| **Hipótesis pendiente** | **El importe medio recuperable por local y mes en España** · la tasa real de éxito de las reclamaciones · si las plataformas permiten un usuario delegado en el portal de partner |

### Criterios de abandono (definidos antes de empezar)

- Fuga media **< 60 €/local/mes** en liquidaciones reales → se abandona.
- Nadie envía liquidaciones tras 8 conversaciones → el problema no importa, o el acceso al nicho no es el que se creía.
- Las plataformas rechazan de plano las reclamaciones en España sin proceso de revisión → se replantea el precio o se abandona.

---

## Cómo está organizado

| Fichero | Contenido |
|---|---|
| [`2026-08-12/00-resumen-ejecutivo.md`](2026-08-12/00-resumen-ejecutivo.md) | Veredicto, prueba principal, riesgo, acción de 24 h |
| [`2026-08-12/01-registro-investigacion.md`](2026-08-12/01-registro-investigacion.md) | Metodología, cobertura, **limitaciones**, señales por horizonte, minería de problemas |
| [`2026-08-12/02-fuentes.csv`](2026-08-12/02-fuentes.csv) | 38 fuentes con URL, fecha de consulta, tipo, qué apoya y qué refuta, fiabilidad |
| [`2026-08-12/03-ideas.csv`](2026-08-12/03-ideas.csv) | 18 candidatos con problema, nicho, comprador, alternativa, MVP, precio, puntuación y estado |
| [`2026-08-12/04-ranking.json`](2026-08-12/04-ranking.json) | Puntuación desglosada por criterio con justificación y penalizaciones |
| [`2026-08-12/05-top-3.md`](2026-08-12/05-top-3.md) | Análisis completo de los 3 finalistas |
| [`2026-08-12/06-nichos-prospeccion.csv`](2026-08-12/06-nichos-prospeccion.csv) | Nichos de entrada, secundarios y anti-nichos + fuentes de prospección con enlaces |
| [`2026-08-12/07-radar-futuro.md`](2026-08-12/07-radar-futuro.md) | Oportunidades de 6–18 y 18–36 meses que **no** deben construirse ahora |
| [`2026-08-12/08-plan-validacion-7-dias.md`](2026-08-12/08-plan-validacion-7-dias.md) | Plan día a día, mensajes de contacto, preguntas de entrevista, criterios de éxito y abandono |
| [`VALIDAR-CON-CHATGPT.md`](VALIDAR-CON-CHATGPT.md) | Prompt de revisión adversarial para contrastar esta tesis con otro modelo |

---

## Los otros dos finalistas (por si ID-01 cae)

- **ID-02 · SAC28** (60/100) — expediente de cumplimiento de la [Ley 10/2025](https://www.boe.es/buscar/act.php?id=BOE-A-2025-26698) de atención a la clientela. Fecha límite **28 de diciembre de 2026**. Compradores localizables en los censos públicos de la CNMC.
- **ID-03 · PMST Express** (52/100) — plan de movilidad sostenible al trabajo, RD-ley 7/2026, fecha límite **5 de diciembre de 2026**. Punto débil: la sanción es infracción leve de 101 a 2.000 €.

## Limitaciones de la investigación

1. El buscador utilizado prioriza resultados de EE. UU.: **no se pudieron leer foros españoles** (Reddit, grupos de hosteleros). La minería de dolor se apoyó en cláusulas contractuales, prensa sectorial y reclamaciones públicas de OCU.
2. No se dispone de datos verificables de volumen de búsqueda y **no se ha inventado ninguno**.
3. **No se han verificado nombres concretos de empresas prospecto** para no fabricar datos: se documenta el método reproducible y las fuentes públicas de partida.
4. Los recuentos de empresas por tramo de plantilla no se han contrastado contra INE/DIRCE.
