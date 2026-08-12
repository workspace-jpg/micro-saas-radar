# Resumen ejecutivo — Barrido micro-SaaS

**Fecha del barrido:** 12 de agosto de 2026  
**Fecha de la auditoría adversarial:** 12 de agosto de 2026  
**Mercado:** España  
**Restricciones:** fundador solo, nivel técnico principiante asistido por IA, presupuesto bajo y necesidad de primeros ingresos rápidos.

---

## 1. Veredicto actualizado

**DESCARTAR ID-01 — CUADRE tal como está planteado. No construir.**

La auditoría independiente encontró tres fallos estructurales:

1. **El hueco competitivo no existe.** [ThinkPaladar Delivery Claims](https://thinkpaladar.com/delivery-claims/) ya ofrece en España auditoría de Glovo/Uber Eats, presentación de reclamaciones y cobro a éxito.
2. **El acceso y la representación están restringidos.** Uber excluye a servicios externos no autorizados de las disputas y prohíbe compartir credenciales; Glovo también prohíbe facilitar credenciales a terceros.
3. **La economía del ICP no está demostrada.** No hay evidencia pública e independiente de que un local español genere más de 150 € al mes realmente abonados. El único benchmark encontrado es comercial y apunta a recuperaciones del 0,3–0,8 % del GMV.

La auditoría completa, con fuentes y clasificación entre hecho, inferencia y ausencia de evidencia, está en [09-auditoria-adversarial-ID-01.md](09-auditoria-adversarial-ID-01.md).

---

## 2. Errores que cambian la decisión

| Supuesto original | Corrección |
|---|---|
| No había competidor equivalente en España | ThinkPaladar ofrece prácticamente el mismo servicio |
| Uber Eats España concedía 30 días | El contrato español fija 14 días naturales desde la notificación del ajuste |
| Los cargos citados de Glovo eran “dinero mal descontado” | Son cargos contractuales bajo condiciones concretas; solo un error de aplicación sería reclamable |
| El fundador podía presentar reclamaciones desde el portal del cliente | No está demostrado; Uber lo contradice para terceros no autorizados |
| Tres meses de liquidaciones validaban recuperabilidad | Gran parte del histórico estaría fuera de plazo |
| 150 €/local/mes bastaban para validar | Puede ser demasiado optimista como recuperación y demasiado bajo para sostener el ingreso del proveedor |

---

## 3. Economía recalculada

El benchmark comercial de ThinkPaladar afirma incidencias del 0,5–1 % del GMV y recuperación del 60–80 %. Eso equivale a aproximadamente **0,3–0,8 % del GMV realmente recuperado**.

| GMV delivery/local/mes | Recuperación estimada | Ingreso al 25 % |
|---:|---:|---:|
| 5.000 € | 15–40 € | 3,75–10 € |
| 20.000 € | 60–160 € | 15–40 € |
| 50.000 € | 150–400 € | 37,50–100 € |

**Conclusión:** el ICP original de más de 5.000 €/mes no sostiene una operación manual a éxito.

---

## 4. Ranking y recomendación

- **ID-01:** de 76/100 a **22/100**; estado **DESCARTADO TRAS AUDITORÍA**.
- La penalización original de −10 era insuficiente; la revisión aplica −29 por dependencia de plataforma, restricciones de terceros, economía no demostrada, intensidad operativa y RGPD.
- No se autoriza la construcción automática de ID-02, ID-03 ni otra idea.
- **Siguiente experimento recomendado:** validar manualmente **ID-05 — Recogida trimestral para asesorías**, porque depende menos de plataformas externas y puede venderse como servicio antes de programar.

ID-05 sigue teniendo competencia y riesgo de integración. “Siguiente experimento” no significa “producto validado”.

---

## 5. Decisión operativa

1. **No ejecutar el antiguo plan de ID-01 ni construir su MVP.**
2. Si se insiste en una última prueba de descarte, comprobar primero autorización de plataforma y medir exclusivamente dinero abonado, clientes fríos y minutos humanos.
3. Preparar una validación separada de ID-05 con entrevistas de comportamiento y preventa manual.
4. Mantener un solo proyecto activo: no abrir desarrollo hasta conseguir evidencia de pago.

### Pregunta mortal de ID-01

> ¿En diez locales que no sean amigos se pueden generar, de forma autorizada, al menos 75 € de ingreso bruto por local y mes y 60 € por hora humana, contando únicamente dinero realmente abonado?

Si la respuesta es no, no existe un negocio SaaS viable.
