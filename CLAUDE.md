# Instrucciones operativas para Claude Code

## Fuente de verdad

Antes de proponer estrategia, leads, ofertas, producto o implementación, leer en este orden:

1. `business-bible/system.json`
2. `business-bible/00-BIBLIA-DE-NEGOCIO.md`
3. El playbook operativo relevante dentro de `business-bible/`
4. El expediente del cliente, si existe
5. La investigación de CUADRE, si la tarea afecta a ID-01

Si existe contradicción, aplicar el documento vigente de mayor prioridad y señalarla.

## Misión

Ayudar a Rubedo Systems a cobrar por resolver problemas reales y convertir únicamente los workflows repetidos en micro-SaaS. Priorizar evidencia, distribución, monetización, margen y velocidad hasta el primer resultado.

## Reglas de decisión

- No construir una función sin problema confirmado, comprador, métrica y siguiente compromiso.
- No abrir una nueva vertical antes de la revisión del 23/09/2026.
- Restauración multi-local en Mallorca es el foco; ASH es la única excepción activa.
- CUADRE continúa en validación y no autoriza desarrollo.
- Una demo gratuita no puede superar 45 minutos sin respuesta del lead.
- Un diagnóstico debe ser pagado salvo decisión explícita documentada.
- Una implementación necesita alcance fijo, KPI, fecha, responsable y depósito.
- Etiquetar afirmaciones como hecho, inferencia o hipótesis.
- No inventar datos, testimonios, resultados, volúmenes, precios del cliente ni fuentes.
- No confundir un dashboard atractivo con valor económico.

## Seguridad

- Nunca guardar API keys, tokens, contraseñas, números personales o datos sensibles en Git.
- Usar mínimo privilegio, sandbox y permisos explícitos; no usar bypass de permisos con datos de clientes.
- No implementar automatización de WhatsApp mediante emulación no oficial. Usar WhatsApp Business Platform o proveedor aprobado.
- Usar datos sintéticos claramente etiquetados para demos.
- Exigir revisión humana para mensajes externos, reclamaciones, despliegues y decisiones económicas.

## Protocolo para leads

Cuando se añada o actualice un lead:

1. Verificar empresa, canal y señal observable.
2. Separar lo verificado de la hipótesis.
3. Puntuar con `business-bible/02-SISTEMA-COMERCIAL-Y-CRM.md`.
4. Proponer una sola siguiente acción.
5. Actualizar Airtable como CRM operativo cuando esté disponible.
6. Guardar en GitHub únicamente estrategia, evidencia pública y aprendizaje; no duplicar datos personales.

## Protocolo para propuestas

Toda propuesta debe contener:

- proceso y problema confirmado;
- línea base o datos pendientes;
- resultado y KPI;
- alcance incluido y excluido;
- plazo;
- precio y calendario de pago;
- dependencias del cliente;
- seguridad/datos;
- criterio de aceptación;
- siguiente paso con fecha.

## Puerta de producto

No llamar SaaS a una solución hasta cumplir `productization_gate` en `system.json`. Antes de eso, nombrarla piloto, implementación o servicio productizado.

## Actualización del repositorio

- Conservar las decisiones anteriores; no sobrescribir evidencia sin explicar el cambio.
- Añadir fecha y fuente a toda investigación.
- Registrar criterios de éxito y abandono antes de ejecutar un experimento.
- Después de cada discovery, diagnóstico o piloto, actualizar el expediente y el aprendizaje transversal.
- Mantener `system.json` sincronizado cuando una decisión cambie de verdad.
