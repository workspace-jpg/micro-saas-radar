# Prompt de validación adversarial

Copia y pega el bloque completo en ChatGPT (o en cualquier otro modelo con acceso a internet). Está diseñado para que **intente tumbar** la tesis, no para que la aplauda.

---

```
Actúa como un inversor escéptico y operador de SaaS B2B que ha visto fracasar
decenas de micro-SaaS. Tu trabajo NO es animarme: es encontrar la razón por la
que esto va a fracasar, o demostrarme que no la hay.

CONTEXTO
Soy fundador solo, nivel técnico principiante asistido por IA, presupuesto bajo,
mercado España. Necesito primeros ingresos rápido. Solo voy a construir UN
producto. Un barrido de investigación ha seleccionado la oportunidad "ID-01" y
quiero contrastarla antes de invertir tiempo.

LEE ESTOS DOCUMENTOS ANTES DE RESPONDER
1. https://raw.githubusercontent.com/workspace-jpg/micro-saas-radar/main/README.md
2. https://raw.githubusercontent.com/workspace-jpg/micro-saas-radar/main/2026-08-12/00-resumen-ejecutivo.md
3. https://raw.githubusercontent.com/workspace-jpg/micro-saas-radar/main/2026-08-12/05-top-3.md
4. https://raw.githubusercontent.com/workspace-jpg/micro-saas-radar/main/2026-08-12/01-registro-investigacion.md
5. https://raw.githubusercontent.com/workspace-jpg/micro-saas-radar/main/2026-08-12/02-fuentes.csv
6. https://raw.githubusercontent.com/workspace-jpg/micro-saas-radar/main/2026-08-12/04-ranking.json
7. https://raw.githubusercontent.com/workspace-jpg/micro-saas-radar/main/2026-08-12/08-plan-validacion-7-dias.md

TAREA 1 — VERIFICACIÓN DE HECHOS
Comprueba con búsquedas propias, sin fiarte de lo que dice el documento:
a) Las cláusulas citadas de las condiciones de partner de Glovo en España
   (comisión sobre ventas brutas sin deducir devoluciones; 5 € + IVA por pedido
   cancelado; 0,25 €/min por demora; hasta el 30 % del valor en entrega
   incorrecta; plazo de reclamación de 1 mes natural). ¿Siguen vigentes hoy?
   ¿Se han citado fuera de contexto?
b) El plazo de 30 días de Uber Eats para disputar cargos por error de pedido:
   ¿aplica igual en España que en EE. UU.?
c) ¿Existe ya en España, Portugal o Italia algún producto o servicio que audite
   liquidaciones de plataformas de delivery y reclame cargos indebidos? Busca en
   español, portugués e italiano. Si existe, dime precio y posicionamiento.
d) ¿Hay algún dato público (asociaciones, prensa sectorial, informes) sobre el
   importe medio que las plataformas descuentan a los restaurantes en España?

TAREA 2 — ATAQUE A LA TESIS
Contesta a cada punto sin diplomacia:
1. ¿Por qué NO existe ya este producto en España, si el problema es tan obvio y
   la categoría es rentable en EE. UU.? Dame las tres explicaciones más
   probables y di cuál es la más creíble.
2. ¿Qué pasa si Glovo y Uber Eats España rechazan sistemáticamente las
   reclamaciones o no tienen proceso formal de revisión para partners?
3. ¿El cliente objetivo (3-15 locales) tiene realmente volumen suficiente para
   que la fuga supere los 150 €/local/mes, o ese umbral solo lo alcanzan las
   grandes cadenas, que ya tienen departamento financiero?
4. ¿Un modelo a éxito (25-30 % de lo recuperado) es defendible legalmente en
   España sin ser intermediación regulada? ¿Qué figura contractual encaja?
5. Riesgo de condiciones de uso: ¿puede el fundador acceder al portal de partner
   del cliente como usuario delegado sin incumplir los términos de la
   plataforma? ¿Y presentar reclamaciones en su nombre?
6. ¿Qué impide que Glovo o Uber Eats maten el negocio cambiando el formato de
   las liquidaciones o cerrando el canal de disputa?
7. ¿Es esto un SaaS o es una consultoría disfrazada? Sé duro con esta pregunta.
8. Riesgo de datos personales: las liquidaciones pueden contener datos de
   consumidores finales. ¿Qué obligaciones de RGPD aparecen y cambian la
   viabilidad para un fundador solo?

TAREA 3 — COMPARACIÓN
El barrido descartó o puntuó por debajo otras 17 ideas (están en 03-ideas.csv y
04-ranking.json). Revisa el ranking y dime:
- si alguna idea descartada merecía más puntuación de la que recibió, y por qué
- si la penalización aplicada a ID-01 (-10) es demasiado suave
- si cambiarías la recomendación única y por cuál

TAREA 4 — EL PLAN DE 7 DÍAS
Revisa 08-plan-validacion-7-dias.md y responde:
- ¿El umbral de éxito (150 €/local/mes de fuga media) está bien calibrado o es
  autocomplaciente?
- ¿Qué sesgo tiene validar con restaurantes de la red personal del fundador, y
  cómo lo corregirías sin perder velocidad?
- ¿Qué pregunta falta en la entrevista?

FORMATO DE RESPUESTA
1. Veredicto en una línea: CONSTRUIR / VALIDAR / DESCARTAR.
2. Las 3 razones más fuertes por las que esto fracasará, ordenadas por
   probabilidad, cada una con la evidencia que la sustenta.
3. Errores de hecho encontrados en los documentos, con la corrección y su fuente.
4. Qué cambiarías del plan de 7 días.
5. La única pregunta que, si se responde mal, mata la idea.

REGLAS
- Cita fuentes con enlace y fecha en todo lo que afirmes.
- Distingue explícitamente hecho verificado / inferencia / especulación.
- Si no encuentras evidencia de algo, di "no hay evidencia", no rellenes el hueco.
- No suavices las conclusiones. Si la idea es mala, dilo en la primera línea.
```

---

## Qué hacer con la respuesta

1. Si ChatGPT encuentra **un competidor español operando**, es un hallazgo real: hay que analizar su precio y posicionamiento antes de seguir.
2. Si encuentra **errores de hecho en las cláusulas citadas**, hay que corregir el repositorio: la tesis entera se apoya en ellas.
3. Si solo devuelve objeciones genéricas ("el mercado es competitivo", "necesitarás marketing"), ignóralas: no son evidencia.
4. **Ninguna respuesta de un modelo sustituye a las 3 auditorías reales del plan de 7 días.** La única validación que cuenta es un hostelero enseñándote su liquidación.
