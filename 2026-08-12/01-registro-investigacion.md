# Registro de investigación — 12 de agosto de 2026

> **Actualización posterior:** la auditoría adversarial independiente cambió el veredicto de ID-01 a **DESCARTAR**. Véase [09-auditoria-adversarial-ID-01.md](09-auditoria-adversarial-ID-01.md). Las conclusiones corregidas prevalecen sobre el barrido inicial.

## 1. Metodología y cobertura

- **Mercados investigados:** España (foco), Unión Europea (origen normativo), EE. UU. (validación de categoría y referencia de precios).
- **Cobertura:** el barrido inicial realizó 34 búsquedas web y 7 lecturas directas. La auditoría posterior contrastó además contratos españoles de Uber y Glovo, competencia en España/Portugal/Italia, prensa económica, CNMC, BOE y AEPD.
- **Categorías de fuente utilizadas:** legislación oficial (BOE, EUR-Lex), organismos y registros públicos (CNMC, MITECO, Ministerio de Transportes, gobierno de Castilla-La Mancha), despachos de abogados y Big Four (PwC, KPMG, Bird&Bird, Garrigues, Fieldfisher, Iberley), prensa sectorial (Restauración News, InfoHoreca, Profesional Horeca, Hostelería Digital, RETEMA, Restaurant Business Online), asociaciones sectoriales (Hostelería de España, ANGED, AFEC, UGT-Aragón), verificadores (Maldita.es), webs y blogs de competidores (con fiabilidad marcada como baja cuando son de parte), términos y condiciones contractuales, y centros de ayuda de plataformas.
- **Fuentes registradas en `02-fuentes.csv`:** 56.

### Limitaciones (declaradas expresamente)

1. **El buscador disponible prioriza resultados de EE. UU.**, lo que degrada la minería de foros en español. No he podido leer hilos de Reddit (r/AutonomosES, r/Hosteleria) ni grupos de Facebook de hosteleros, que serían la mejor fuente de lenguaje real de cliente. La minería de dolor se ha apoyado por tanto en: cláusulas contractuales, prensa sectorial, reclamaciones públicas de OCU y contenido de competidores.
2. **No dispongo de datos verificables de volumen de búsqueda** (Google Trends/keyword tools) y no he inventado ninguno.
3. **No existe una media pública e independiente de dinero realmente abonado por local en España.** El benchmark encontrado (0,5–1 % de incidencias y 60–80 % de recuperación) procede del propio competidor ThinkPaladar y no basta para validar la economía.
4. Dos webs (Fieldfisher y Ministerio de Transportes) devolvieron HTTP 403; su contenido se ha sustituido por fuentes equivalentes (BOE directo y despachos).
5. Los recuentos de empresas por tramo de plantilla no se han verificado contra INE/DIRCE en esta pasada; donde aparecen, están marcados como estimación.
6. El tamaño del mercado delivery, las comisiones contractuales y las reclamaciones de consumidores no prueban que existan cargos erróneos recuperables para el restaurante.
7. La auditoría encontró un competidor directo español y restricciones de acceso/representación que el barrido inicial no había considerado.

---

## 2. Señales relevantes

### Horizonte AHORA (ya se puede vender)

| Señal | Hecho | Fecha | Fuente | Qué abre |
|---|---|---|---|---|
| Contratos de delivery con cargos automáticos al restaurante | Los cargos citados son contractuales: 5 €+IVA solo por cancelación imputable; 0,25 €/min después de 10 min y máximo 2,50 €; entrega incorrecta imputable con penalización de hasta 30 %. El mes natural se vincula a los supuestos operativos de la cláusula 4.1, no a cualquier discrepancia | Junio de 2025; consulta 12/08/2026 | Glovo Partners España (primaria) | **Refuta la interpretación original de ID-01** |
| Ventana de disputa de Uber Eats | La ayuda localizada menciona 30 días, pero el contrato español fija **14 días naturales desde la notificación del ajuste**. Uber restringe la disputa a administradores/managers y excluye servicios externos no autorizados | Contrato 17/10/2025; consulta 12/08/2026 | Uber Eats España (primaria) | **Refuta el plazo y el flujo originales de ID-01** |
| Presión de margen en delivery | Se publican rangos de comisión y tamaño del canal, pero **no una media de cargos indebidos ni recuperaciones** por restaurante español | 2019–2026 | CNMC, asociaciones y prensa sectorial | Contexto; **no valida ID-01** |
| Ley 10/2025 de atención a la clientela | En vigor 28/12/2025, **plazo de adaptación 12 meses → 28/12/2026**. Obliga a: 95 % de llamadas atendidas en <3 min, 2 h para incidencias de servicios continuados, 5 días para cobros indebidos, 15 días hábiles el resto, clave identificativa en soporte duradero, prohibición del contestador como único medio, 24 h/365 en servicios básicos, conservación 5 años, evaluación anual de calidad y **auditoría anual por entidad acreditada ENAC** con publicación de resultados | BOE 27/12/2025 | BOE-A-2025-26698 (primaria) | **ID-02** |
| Plan de Movilidad Sostenible al Trabajo | RD-ley 7/2026 (BOE 21/03/2026) reduce el plazo de 24 a 12 meses: centros con **>200 trabajadores o 100 por turno** deben tenerlo antes del **5/12/2026**; registro en EDIM. Sanción: infracción leve, **101–2.000 €**; devolución íntegra de ayudas públicas vinculadas si se incumple | 20/03/2026 | Economist&Jurist, Tornos, UGT Aragón | **ID-03** |
| Ley 1/2025 de desperdicio alimentario | Obligaciones del art. 6 (plan de prevención, convenios de donación, jerarquía) exigibles desde **2/04/2026**; falta de plan = infracción grave, 2.001–60.000 €. **Microempresas (<10 trabajadores) exentas del plan.** Hostelería de España publicó una **herramienta gratuita** (hosteleriacircular.es) | 2025–2026 | PwC, Restauración News, Hostelería Digital | Descartado (ID-06) |
| Reglamento (UE) de IA plenamente aplicable | Desde **2/08/2026**: transparencia del art. 50 (avisar de que se habla con una máquina, marcar contenido generado por IA), supervisión de GPAI y régimen sancionador. Alto riesgo del anexo III aplazado a 2/12/2027 por el reglamento ómnibus | 02/08/2026 | Blogs jurídicos ES (fiabilidad media) | Radar (ID-15) |
| Ley 11/2023 de accesibilidad (EAA) | Exigible a productos y servicios nuevos desde 28/06/2025; multas de 301 € a 1.000.000 €; microempresas <10 empleados y <2 M€ exentas; norma técnica UNE-EN 301549:2022 | Vigente | Guías jurídicas ES | ID-10 |
| Coste real de la gestión documental CAE | Empresa pequeña (5–10 contratas): 5–8 h/semana; mediana (15–25): 12–15 h/semana; técnico de PRL 22–28 €/h; externalizar: 3.000–8.000 €/año | 12/06/2026 | UCAE | ID-04 |

### Horizonte 6–18 MESES

| Señal | Hecho | Fecha clave | Fuente |
|---|---|---|---|
| SDDR de envases | Se activa por incumplir el objetivo del 70 % (España recogió el 41,3 % en 2023); art. 47 del RD 1055/2022. Fecha señalada: **22/11/2026**, depósito ≥0,10 €. Operador autorizado: Procircular Depósito. **Falta la normativa técnica**; MITECO no ha confirmado calendario. Hostelería exenta en consumo en local, no en *take away* | nov. 2026 | Maldita.es, RETEMA, ANGED, Junta de Castilla-La Mancha |
| Verifactu | Aplazado por RD-ley 15/2025 (BOE 3/12/2025): **1/01/2027** para contribuyentes del IS y **1/07/2027** para el resto | 2027 | Noticias Jurídicas, ICAM |
| Factura electrónica B2B | RD 238/2026 (BOE 31/03/2026); la orden ministerial entra en vigor **1/10/2026**; obligación efectiva: oct. 2027 (>8 M€) y oct. 2028 (resto). Formato EN16931 (UBL/CII/EDIFACT) | 2027–2028 | Iberley, EDICOM, Lealtadis |
| Registro de jornada digital | RD **aún no publicado**; aplazado a septiembre de 2026 tras dictamen desfavorable del Consejo de Estado (23/03/2026). Incluiría acceso remoto de la Inspección | sept. 2026 | Protime, Factorial, TeamSystem |
| Transparencia retributiva | Plazo de transposición de la Directiva (UE) 2023/970 vencido el **7/06/2026** sin norma española. Informes desde 100 empleados | 2026–2027 | Iberley, Bird&Bird |
| NIS2 | Anteproyecto de Ley de Coordinación y Gobernanza de la Ciberseguridad pendiente en las Cortes; 18 sectores, umbral >50 empleados o >10 M€ | 2026–2027 | Legiscope, a3sec |
| PPWR (UE) 2025/40 | Aplicable desde **12/08/2026**; prohibiciones de formatos de un solo uso que afectan a HORECA y hoteles | 12/08/2026 | Prensa sectorial |

### Horizonte 18–36 MESES

| Señal | Hecho | Fuente |
|---|---|---|
| SDDR obligatorio en toda la UE | 1/01/2029 por el Reglamento (UE) 2025/40 | Prensa sectorial |
| Alto riesgo del Reglamento de IA | Anexo III: 2/12/2027; anexo I: 2/08/2028 | Blogs jurídicos |
| Estados de pago en factura electrónica | El RD 238/2026 incorpora la comunicación de estados de pago, base para explotar datos de morosidad | Lealtadis |
| Accesibilidad: fin de la prórroga | Servicios preexistentes, junio de 2030 | Guías jurídicas |

---

## 3. Minería de problemas: qué encontré y qué no

**Encontrado (lenguaje real o hechos económicos):**
- *"revisa tres o cuatro liquidaciones reales y saca la comisión efectiva media, ese es el número con el que tienes que trabajar"* — consejo repetido en guías para hosteleros: revela que **nadie sabe su comisión efectiva real**.
- *"se suman los gastos por reembolsos a clientes (100 % a tu cargo) y penalizaciones por retrasos en la preparación"*.
- Reclamaciones públicas en OCU sobre pedidos cancelados y cobros indebidos con Glovo y Uber Eats (lado consumidor, enero–febrero de 2026) — indican volumen de incidencias, no importe al restaurante.
- *"La burocracia es enorme, de hecho es una de las principales quejas de los prevencionistas"* (CAE).
- Las subcontratas *"tienen que gestionar documentos ante decenas de plataformas CAE, a veces un software por cada cliente"*.
- *"Cierra el trimestre sin perseguir a nadie"* — posicionamiento de Nexus by Peaks: confirma el dolor de las asesorías **y que ya está atendido**.
- ThinkPaladar Delivery Claims ya audita Glovo/Uber, presenta reclamaciones y cobra a éxito en España; comunicaba más de 150 clientes en 2024.

**No encontrado (y por qué importa):**
- Datos independientes de restaurantes españoles que separen **detectado, reclamado, aceptado y abonado**, con GMV y minutos humanos por expediente.
- Sanciones efectivas publicadas por incumplimiento de la Ley 11/2023 de accesibilidad → la urgencia de ID-10 es teórica.
- Evidencia de que Uber o Glovo autorizan a un proveedor nuevo a acceder como usuario delegado y presentar disputas en nombre del restaurante.

---

## 4. Relación con el trabajo ya existente en el workspace

Revisado el índice de proyectos antes de generar ideas, para no duplicar. **No se ha modificado ningún archivo fuera de este directorio y no se ha hecho ningún commit.**

| Proyecto existente | Relación con este barrido |
|---|---|
| `01_MicroSaas/saas_restaurantes` (menú 360°) | Comparte comprador con ID-01, pero no justifica construir un servicio de reclamaciones cuya economía y autorización no están demostradas. |
| `01_MicroSaas/saas_seguridad` (cumplimiento sobre Holded) | Mismo patrón que ID-02: producto de cumplimiento vertical. Si ID-01 muere, la experiencia comercial de este proyecto se reaprovecha en ID-02. |
| `01_MicroSaas/saas_jimenez_pariente` | Confirma que el fundador ya sabe vender software vertical a un negocio de campo; no se solapa. |
| `01_MicroSaas/prospects_españa.csv` y `_archivo_prospecting` | **Reutilizable directamente** como base de la lista de prospectos del día 1, si contiene hostelería. |
| `02_Ecomerce/meta-agent` | Reutilizable el patrón de CLI + credenciales en config, no el código. |
| Ventaja declarada en hostelería y negocios locales | Facilita entrevistas, pero no corrige la falta de autorización, el competidor directo ni la economía unitaria. La puntuación revisada de ID-01 es 22/100. |

**Componentes potencialmente reaprovechables, sin construir ahora:** importación y normalización de ficheros, motor de reglas y generación de informes. No constituyen una razón suficiente para reactivar ID-01.
