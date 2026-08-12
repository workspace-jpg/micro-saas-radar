# Radar de oportunidades micro-SaaS — Rubedo Systems

Investigación de oportunidades para el mercado español con validación previa a cualquier desarrollo.

- **Fecha del barrido:** 12 de agosto de 2026
- **Contexto:** fundador solo, nivel técnico principiante asistido por IA, presupuesto bajo y prioridad en primeros ingresos
- **Barrido inicial:** 18 candidatos → 10 rankeados → 3 finalistas
- **Resultado tras auditoría:** **ID-01 descartado; no hay producto autorizado para construir todavía**
- **Siguiente experimento:** validar manualmente ID-05, sin escribir código

> El barrido inicial recomendó ID-01. Una revisión adversarial posterior encontró un competidor directo en España, restricciones contractuales para terceros y ausencia de economía unitaria demostrada. La auditoría posterior prevalece sobre la recomendación original.

---

## Estado actual

### ID-01 — CUADRE

**Auditoría de liquidaciones de plataformas de delivery.**

**Veredicto: DESCARTAR tal como está planteado.**  
**Puntuación revisada: 22/100** frente a 76/100 en el barrido original.

Razones decisivas:

1. [ThinkPaladar Delivery Claims](https://thinkpaladar.com/delivery-claims/) ya ofrece en España auditoría, reclamación y cobro a éxito para Glovo/Uber.
2. [Uber Eats España](https://help.uber.com/es-ES/merchants-and-restaurants/article/gestionar-los-reembolsos-de-pedidos-incompletos-o-incorrectos?nodeId=abc0c3e7-9687-4a00-a956-2c8a16cf0b7e) restringe las disputas a administradores/managers y excluye a servicios externos no autorizados; Glovo prohíbe compartir credenciales.
3. El contrato español de Uber fija **14 días**, no 30, para impugnar ajustes.
4. Los cargos de Glovo citados son contractuales bajo condiciones concretas; no son automáticamente “cobros indebidos”.
5. No hay una media pública e independiente de dinero realmente recuperado por restaurante español.
6. Con el benchmark comercial disponible, un local con 5.000 € de GMV produciría solo 15–40 € recuperados y 3,75–10 € de ingreso al 25 %.

Documento decisivo: [Auditoría adversarial de ID-01](2026-08-12/09-auditoria-adversarial-ID-01.md).

### Siguiente decisión

No se cambia una mala certeza por otra. **ID-05 — Recogida trimestral para asesorías** pasa a ser el siguiente experimento, no una recomendación de construcción. Debe demostrar pago y recurrencia mediante un servicio manual antes de desarrollar software.

---

## Documentos

| Archivo | Contenido |
|---|---|
| [00-resumen-ejecutivo.md](2026-08-12/00-resumen-ejecutivo.md) | Veredicto y decisión actualizados |
| [01-registro-investigacion.md](2026-08-12/01-registro-investigacion.md) | Metodología, cobertura, limitaciones y correcciones |
| [02-fuentes.csv](2026-08-12/02-fuentes.csv) | 56 fuentes con señal, apoyo/refutación y fiabilidad |
| [03-ideas.csv](2026-08-12/03-ideas.csv) | 18 candidatos y estado posterior a la auditoría |
| [04-ranking.json](2026-08-12/04-ranking.json) | Ranking recalibrado y trazabilidad del cambio |
| [05-top-3.md](2026-08-12/05-top-3.md) | Análisis de finalistas con ID-01 corregido |
| [06-nichos-prospeccion.csv](2026-08-12/06-nichos-prospeccion.csv) | Nichos y fuentes de prospección |
| [07-radar-futuro.md](2026-08-12/07-radar-futuro.md) | Oportunidades futuras que no deben construirse ahora |
| [08-plan-validacion-7-dias.md](2026-08-12/08-plan-validacion-7-dias.md) | Plan original sustituido por una prueba de descarte |
| [09-auditoria-adversarial-ID-01.md](2026-08-12/09-auditoria-adversarial-ID-01.md) | Verificación factual, competencia, economía y riesgos |
| [VALIDAR-CON-CHATGPT.md](VALIDAR-CON-CHATGPT.md) | Prompt que originó la revisión adversarial |

---

## Reglas de decisión

- Un cargo detectado no equivale a dinero reclamable.
- Una reclamación presentada no equivale a una reclamación aceptada.
- Una reclamación aceptada no equivale a dinero abonado.
- Solo cuentan clientes fríos y dinero realmente cobrado.
- No se construye software para compensar falta de evidencia comercial.
- Se mantiene un único experimento activo.
