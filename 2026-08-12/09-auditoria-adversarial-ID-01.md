# Auditoría adversarial de ID-01 — CUADRE

**Fecha:** 12 de agosto de 2026  
**Estado:** revisión posterior al barrido inicial  
**Veredicto:** **DESCARTAR ID-01 tal como está planteado. No construir.**

La tesis original falla en tres puntos que son estructurales, no cosméticos:

1. El hueco competitivo en España no existe.
2. La representación y el acceso de terceros están restringidos por las plataformas.
3. No hay evidencia independiente de que el cliente objetivo genere suficiente dinero recuperado para sostener el modelo.

---

## 1. Las tres causas más probables de fracaso

### 1.1. El canal que produce el valor no está bajo control del producto

**Hecho verificado.** [ThinkPaladar Delivery Claims](https://thinkpaladar.com/delivery-claims/) ya ofrece en España auditoría de liquidaciones de Glovo y Uber Eats, detección de penalizaciones y comisiones, presentación de reclamaciones y cobro a éxito. No publica su porcentaje. Consulta: 12/08/2026.

ThinkPaladar no es un experimento sin distribución: comunicaba más de 150 clientes en mayo de 2024 y cerca de 100.000 € de facturación en su primer ejercicio comercial. Fuentes: [Barra de Ideas, 10/05/2024](https://barradeideas.com/thinkpaladar-la-startup-que-rentabiliza-el-delivery-de-los-restaurantes/) y [VIA Empresa, 11/04/2024](https://www.viaempresa.cat/es/empresa/think-paladar-restaurantes-delivery_2196211_102.html).

**Hecho verificado.** Uber indica que las disputas deben realizarlas administradores o managers del restaurante; los servicios externos no están autorizados para solicitar reembolsos y no deben compartirse credenciales. Fuente: [Ayuda de Uber Eats España](https://help.uber.com/es-ES/merchants-and-restaurants/article/gestionar-los-reembolsos-de-pedidos-incompletos-o-incorrectos?nodeId=abc0c3e7-9687-4a00-a956-2c8a16cf0b7e), consulta 12/08/2026.

**Hecho verificado.** Glovo prohíbe al partner facilitar sus credenciales a terceros; los accesos técnicos de integradores o POS deben acordarse con la plataforma. Fuente: [Condiciones de Partners de Glovo España, cláusula 4.1.9](https://glovoapp.com/docs/es/legal/terms-partners/), actualización de junio de 2025, consulta 12/08/2026.

**Inferencia.** Sin autorización expresa de las plataformas, el servicio solo puede analizar exportaciones y preparar expedientes para que los presente el propio restaurante. Eso convierte “nos encargamos de todo” en una promesa que no puede darse por válida.

### 1.2. La economía del cliente objetivo no está demostrada

**No hay evidencia** pública, independiente y española que demuestre una recuperación media superior a 150 €/local/mes para restaurantes de 3–15 locales.

El único benchmark español encontrado procede del propio competidor: incidencias equivalentes al 0,5–1 % de la facturación delivery y recuperación del 60–80 %. Es evidencia comercial de parte, no un estudio independiente. Fuente: [ThinkPaladar Delivery Claims](https://thinkpaladar.com/delivery-claims/), consulta 12/08/2026.

Aplicando ese benchmark favorable:

| GMV delivery por local/mes | Recuperación estimada, 0,3–0,8 % | Ingreso del proveedor al 25 % |
|---:|---:|---:|
| 5.000 € | 15–40 € | 3,75–10 € |
| 20.000 € | 60–160 € | 15–40 € |
| 50.000 € | 150–400 € | 37,50–100 € |

Para recuperar 150 €/mes se requieren aproximadamente 18.750–50.000 € de delivery mensual por local. El umbral original de entrada de 5.000 € de GMV no sostiene el modelo.

**Inferencia.** Detectado, reclamado y abonado son magnitudes diferentes. Solo el importe realmente abonado puede usarse para validar economía e ingresos.

### 1.3. Es una operación de reclamaciones asistida, no un micro-SaaS ligero

**Hecho verificado.** Uber puede exigir fotografías, vídeo, CCTV, recibos firmados u otras pruebas para revisar un ajuste. [Ayuda de Uber Eats España](https://help.uber.com/es-ES/merchants-and-restaurants/article/gestionar-los-reembolsos-de-pedidos-incompletos-o-incorrectos?nodeId=abc0c3e7-9687-4a00-a956-2c8a16cf0b7e), consulta 12/08/2026.

**Hecho verificado.** [Deliverect Reclaim](https://www.deliverect.com/es/reclaim-by-deliverect) combina tecnología con revisión y presentación humana de disputas. Consulta 12/08/2026.

**Inferencia.** La detección puede automatizarse, pero obtener el abono exige juicio, pruebas, presentación y seguimiento. En su primera fase sería consultoría operativa a éxito. Solo podría convertirse en software de margen alto con autorización e integración formal.

---

## 2. Correcciones de hechos del barrido original

| Afirmación original | Corrección verificada |
|---|---|
| No existe equivalente especializado en España. | **Falso.** ThinkPaladar Delivery Claims ofrece prácticamente el mismo servicio para Glovo y Uber Eats. |
| La comisión sobre pedidos reembolsados es dinero reclamable. | **Falso como regla general.** Glovo establece que la comisión de Marketplace se calcula sobre ventas brutas sin descontar devoluciones, aunque la entrega no termine correctamente. Es un cargo contractual salvo error de aplicación. |
| Glovo cobra 5 € por cualquier pedido cancelado. | **Fuera de contexto.** Son 5 € + IVA cuando la cancelación es imputable al partner. |
| Glovo cobra 0,25 €/minuto de demora sin más condiciones. | **Incompleto.** Se activa después de diez minutos desde la llegada indicada del repartidor y tiene un máximo de 2,50 € por pedido. |
| Una entrega incorrecta genera automáticamente un 30 % adicional. | **Engañoso.** Debe ser imputable al partner y la penalización es de hasta el 30 %, además del coste correspondiente. |
| Glovo concede un mes para reclamar cualquier discrepancia. | **Demasiado amplio.** El mes natural está vinculado a los supuestos operativos enumerados en la cláusula 4.1; no se ha verificado que cubra toda comisión o discrepancia contractual. |
| Uber Eats España permite disputar durante 30 días, igual que EE. UU. | **Falso para el criterio operativo seguro.** La ayuda localizada conserva elementos estadounidenses. El contrato español fija 14 días naturales desde la notificación del ajuste. |
| Tres meses de liquidaciones sirven para validar recuperaciones. | **Incorrecto operativamente.** Gran parte del histórico estaría fuera de los 14 días de Uber o del mes de Glovo. Sirve para detectar patrones, no para demostrar recuperabilidad vigente. |
| El fundador puede reclamar usando el portal del cliente. | **No demostrado y contradicho en Uber.** Un mandato del restaurante no anula las restricciones contractuales de la plataforma. |

Fuentes primarias: [Glovo Partners España](https://glovoapp.com/docs/es/legal/terms-partners/), actualización junio de 2025; [condiciones de merchant de Uber Eats España](https://www.uber.com/es/es-es/legal/uber-eats-merchant-terms-and-conditions/), 17/10/2025; [ayuda localizada de Uber](https://help.uber.com/es-ES/merchants-and-restaurants/article/gestionar-los-reembolsos-de-pedidos-incompletos-o-incorrectos?nodeId=abc0c3e7-9687-4a00-a956-2c8a16cf0b7e). Consultadas el 12/08/2026.

---

## 3. Competencia encontrada en España, Portugal e Italia

| Mercado | Producto | Posicionamiento | Precio público |
|---|---|---|---|
| España | [ThinkPaladar Delivery Claims](https://thinkpaladar.com/delivery-claims/) | Auditoría, reclamación y seguimiento para Glovo/Uber; cobro a éxito | Porcentaje no publicado |
| España / internacional | [Deliverect Reclaim](https://www.deliverect.com/es/reclaim-by-deliverect) | Recuperación de reembolsos con tecnología y revisión humana | Porcentaje no publicado |
| Portugal | [Condiciones de Deliverect Portugal](https://www.deliverect.com/pt-pt/terms-of-service) | Reclaim y nombramiento de Deliverect como usuario autorizado | Tarifa por presupuesto |
| Portugal e Italia | [Sinqro PT](https://sinqro.com/pt-pt/learn/how-marketplace-settlements-work) / [Sinqro IT](https://sinqro.com/it-it/learn/how-marketplace-settlements-work) | Conciliación de liquidaciones, pedidos ausentes, reembolsos y comisiones | Configuración inicial desde 29 €/local/mes; no hay tarifa separada del módulo |

**No hay evidencia** pública de que Sinqro presente reclamaciones en nombre del restaurante.

---

## 4. Datos económicos públicos en España

**No hay evidencia** independiente y actual de una media de cargos indebidos o recuperaciones por restaurante español.

La [CNMC, expediente E/CNMC/004/19](https://www.cnmc.es/sites/default/files/2804135_0.pdf), 2019, confirma que las comisiones son una fuente principal de ingresos de las plataformas, pero no publica una media de errores o devoluciones y oculta datos empresariales por confidencialidad.

[Hostelería Madrid](https://www.hosteleriamadrid.com/blog/descubre-como-han-evolucionado-las-comisiones-del-delivery-en-el-ultimo-ano/), consultada el 12/08/2026, ofrece ejemplos de porcentajes de comisión, no de descuentos erróneos ni recuperaciones.

La cifra de 2,5–3 % y el ejemplo de 500 $ por local proceden de EE. UU. y no deben extrapolarse a España sin datos observados.

---

## 5. Riesgo contractual, jurídico y de RGPD

### Modelo a éxito

**Inferencia jurídica; requiere revisión profesional.** Puede estructurarse como prestación B2B de servicios más mandato específico y retribuido para actuaciones extrajudiciales. El abono debe llegar directamente al restaurante y el proveedor factura su porcentaje después. Referencias: [Código Civil, arts. 1255, 1544 y 1709–1713](https://www.boe.es/buscar/act.php?id=BOE-A-1889-4763) y [Real Decreto-ley 19/2018](https://www.boe.es/buscar/doc.php?id=BOE-A-2018-16036), textos consolidados consultados el 12/08/2026.

El mandato no concede acceso técnico ni representación frente a una plataforma que no los autorice.

### Dependencia de plataforma

**Hecho verificado.** Glovo puede modificar sus condiciones con 15 días de preaviso. Un cambio de CSV es reparable; cerrar el canal, acortar plazos o exigir integración aprobada puede destruir el producto. Fuente: [Glovo, cláusula 2.3](https://glovoapp.com/docs/es/legal/terms-partners/), junio de 2025.

### RGPD

Si los ficheros incluyen nombres, teléfonos, direcciones o identificadores vinculables, el proveedor será normalmente encargado del tratamiento del restaurante.

Obligaciones mínimas:

- contrato de encargado conforme al artículo 28;
- minimización y borrado de columnas innecesarias;
- control de acceso, cifrado y política de conservación;
- autorización y contratos con subencargados de IA, hosting y almacenamiento;
- revisión de transferencias internacionales;
- procedimiento ante brechas y devolución o borrado al terminar.

Fuentes: [AEPD sobre encargado del tratamiento](https://www.aepd.es/prensa-y-comunicacion/blog/comunidades-de-propietarios-y-administradores-de-fincas-ante-el-rgpd), 2018; [AEPD sobre protección de datos por defecto](https://www.aepd.es/derechos-y-deberes/cumple-tus-deberes/medidas-de-cumplimiento/proteccion-de-datos-por-defecto), modificada 05/01/2026; [AEPD sobre transferencias internacionales](https://www.aepd.es/derechos-y-deberes/cumple-tus-deberes/medidas-de-cumplimiento/garantias-transferencias-datos-personales), modificada 19/06/2026.

---

## 6. Impacto en el ranking

La penalización original de −10 era demasiado suave. La revisión deja ID-01 en **22/100**:

- score base revisado: 51/100;
- penalizaciones: −29;
- score final: 22/100;
- diferenciación: 0/8 por competidor equivalente;
- viabilidad del MVP: 4/12 porque la detección es sencilla pero la recuperación no;
- disposición de pago: 4/12, sin validación española independiente;
- velocidad al primer ingreso: 3/10, porque el ingreso depende del abono efectivo.

No se recomienda construir automáticamente otro candidato. El siguiente experimento de menor dependencia externa es **ID-05, Recogida trimestral para asesorías**, pero también debe validarse manualmente antes de construir.

---

## 7. Qué pasa con el plan de siete días

El plan original queda **supersedido** porque:

- usa tres meses, aunque gran parte estaría fuera de plazo;
- valida con conocidos, generando sesgo de confianza y deseabilidad;
- contabiliza cargos detectados en lugar de dinero abonado;
- no comprueba primero si existe una figura autorizada para operar;
- considera suficiente un acuerdo informal por WhatsApp;
- no mide minutos humanos por expediente;
- el umbral de 150 € es alto frente al benchmark disponible pero demasiado bajo para la economía del proveedor.

Si se hace una última prueba de descarte, debe exigir:

1. autorización escrita o flujo permitido por cada plataforma;
2. diez locales: dos cálidos, tres referidos y cinco fríos;
3. contrato y comisión pactada de cada restaurante;
4. ventana vigente: 14 días para Uber y un mes solo en los supuestos aplicables de Glovo;
5. cinco estados separados: contractual, discrepancia elegible, presentada, aceptada y abonada;
6. presentación por un administrador autorizado, sin compartir contraseñas;
7. medición de tiempo humano por expediente;
8. continuación únicamente con dos clientes fríos contratados, al menos 300 € abonados por local/mes y al menos 60 € de ingreso por hora humana.

La pregunta de entrevista que faltaba era:

> “Enséñame la última discrepancia que reclamaste: ¿qué prueba conservabas, quién la presentó, dentro de qué plazo y cuánto dinero terminó abonándose?”

---

## 8. Pregunta mortal

**¿En diez locales que no sean amigos se pueden generar, de forma autorizada, al menos 75 € de ingreso bruto por local y mes y 60 € por hora humana, contando únicamente dinero realmente abonado por la plataforma?**

Si la respuesta es no, no hay negocio SaaS: hay un detector de anomalías con una reclamación manual cara detrás.
