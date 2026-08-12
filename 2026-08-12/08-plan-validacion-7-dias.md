# Plan de descarte de 7 días — ID-01 CUADRE

**Estado:** el plan original queda supersedido por la auditoría adversarial.  
**Decisión por defecto:** **NO EJECUTAR y NO CONSTRUIR.**

Este documento solo define la última prueba que podría hacerse si se decide intentar refutar el descarte. Los primeros siete días prueban acceso, datos y preventa; el resultado económico debe observarse durante 21–30 días porque una semana no basta para verificar abonos.

Auditoría de referencia: [09-auditoria-adversarial-ID-01.md](09-auditoria-adversarial-ID-01.md).

---

## 1. Qué estaba mal en el plan original

- Pedía tres meses de liquidaciones, aunque gran parte estaría fuera de los 14 días de Uber o del mes aplicable de Glovo.
- Validaba principalmente con la red personal, introduciendo sesgo de confianza, conveniencia y deseabilidad.
- Trataba “detectado” como equivalente a “recuperable”.
- No separaba reclamación presentada, aceptada y dinero abonado.
- No comprobaba antes si la plataforma autorizaba a un proveedor externo.
- Permitía un acuerdo informal por WhatsApp para un servicio con representación, datos y responsabilidad.
- No medía minutos humanos por expediente.
- El umbral de 150 €/local/mes era alto frente al benchmark disponible, pero insuficiente para sostener una comisión del 25 %.

---

## 2. Condiciones previas

No se solicita ninguna liquidación hasta cumplir estas condiciones:

1. **Autorización:** obtener respuesta escrita de Glovo y Uber sobre qué figura permite a un proveedor externo revisar datos y presentar disputas. Si no existe, el restaurante deberá presentar cada expediente.
2. **Sin credenciales compartidas:** el cliente exporta los ficheros; el proveedor nunca recibe su contraseña.
3. **Contrato B2B:** prestación de servicios, mandato específico para actos permitidos, base de cálculo del success fee, limitación de responsabilidad y anexo de protección de datos.
4. **Dinero directo al restaurante:** el proveedor no recibe ni custodia el abono de la plataforma.
5. **Minimización:** eliminar nombre, teléfono, dirección y cualquier dato del consumidor que no sea imprescindible.

Si el punto 1 falla, se descarta el servicio “gestionado” y solo podría evaluarse una herramienta de preparación de expedientes, con una economía distinta.

---

## 3. Muestra mínima

**Diez locales, no tres:**

- 2 contactos cálidos para depurar el flujo;
- 3 referidos;
- 5 completamente fríos.

Los conocidos sirven para encontrar errores operativos. **Solo los clientes fríos cuentan para validar compra.**

Criterio de volumen: registrar GMV mensual real por plataforma. No excluir locales de poco volumen después de ver el resultado; eso sería manipular la muestra.

---

## 4. Ventana analizada

- **Uber Eats España:** últimos 14 días naturales desde la notificación del ajuste.
- **Glovo:** como máximo un mes y solo para los supuestos contractuales aplicables de la cláusula 4.1.
- **Histórico de tres meses:** puede analizarse para aprender formatos y patrones, pero se etiqueta como **fuera de plazo** y no se suma al recuperable.

Cada restaurante debe aportar también su hoja de pedido, porcentaje de comisión pactado y condiciones particulares. Sin contrato individual no se puede afirmar que una comisión es incorrecta.

---

## 5. Cinco estados obligatorios

| Estado | Qué significa | ¿Cuenta como validación económica? |
|---|---|---|
| Cargo contractual | Coincide con lo pactado aunque sea desfavorable | No |
| Discrepancia elegible | Hay base contractual y prueba para reclamar | No |
| Reclamación presentada | La envió un administrador autorizado | No |
| Reclamación aceptada | La plataforma reconoce el ajuste | No |
| Dinero abonado | Aparece el abono en cuenta o liquidación | **Sí** |

Solo el último estado entra en recuperación y success fee.

---

## 6. Entrevista

Preguntas obligatorias:

1. ¿Cómo concilias hoy pedido, liquidación y banco?
2. Enséñame la última discrepancia que detectaste.
3. ¿Qué prueba conservabas?
4. ¿Quién presentó la reclamación y dentro de qué plazo?
5. ¿Cuánto dinero terminó abonándose?
6. ¿Cuántos minutos de trabajo consumió de principio a fin?
7. ¿Darías acceso a un proveedor externo si la plataforma no ofrece un rol delegado formal?
8. ¿Quién firma un contrato y autoriza el tratamiento de los ficheros?

La pregunta decisiva es:

> “Enséñame la última discrepancia que reclamaste: ¿qué prueba conservabas, quién la presentó, dentro de qué plazo y cuánto dinero terminó abonándose?”

No se pregunta si “les gusta la idea”.

---

## 7. Calendario de los primeros siete días

| Día | Trabajo | Evidencia exigida |
|---|---|---|
| 0 | Consultar por escrito a Glovo/Uber el flujo autorizado | Respuesta o documentación oficial |
| 1 | Reclutar 2 cálidos, 3 referidos y 5 fríos | Diez locales identificados |
| 2 | Firmar documentos y recibir exportaciones minimizadas | Contrato, anexo RGPD y datos de ventana vigente |
| 3 | Auditar los dos cálidos y documentar reglas | Cargos separados entre contractual y elegible |
| 4 | Auditar tres referidos y medir tiempo | Minutos por expediente y pruebas requeridas |
| 5 | Auditar cinco fríos | Al menos dos clientes fríos aceptan el success fee |
| 6 | Preparar reclamaciones; las presenta el administrador del restaurante | Justificante de presentación dentro de plazo |
| 7 | Decisión de acceso y preventa | Continuar seguimiento o cerrar la idea |

No hay desarrollo de software durante estos días.

---

## 8. Seguimiento de 21–30 días

Registrar por local y plataforma:

- GMV dentro de la ventana;
- euros contractuales;
- euros elegibles;
- euros presentados;
- euros aceptados;
- euros abonados;
- minutos humanos totales;
- ingreso del proveedor;
- ingreso por hora humana.

Glovo puede tardar días laborables en responder. No se emite un GO económico el día 7.

---

## 9. Umbral de continuación

Deben cumplirse **todos**:

1. Existe flujo autorizado o la oferta se limita contractualmente a preparar expedientes.
2. Al menos 2 clientes fríos firman.
3. Recuperación media **≥300 € realmente abonados por local/mes**.
4. Ingreso del proveedor **≥75 € por local/mes**.
5. Ingreso **≥60 € por hora humana**.
6. Al menos 60 % de las reclamaciones elegibles terminan abonadas.
7. El tratamiento puede realizarse sin datos personales innecesarios.

Estos umbrales son criterios operativos, no datos de mercado.

---

## 10. Criterios de descarte inmediato

- Las plataformas no autorizan al proveedor y los restaurantes no quieren presentar los expedientes.
- Menos de dos clientes fríos firman.
- Recuperación abonada inferior a 300 €/local/mes.
- Ingreso por hora humana inferior a 60 €.
- La mayor parte de lo detectado resulta contractual o carece de prueba.
- La operación exige compartir contraseñas.
- El cliente objetivo necesita menos volumen del que hace viable el modelo.

### Pregunta mortal

**¿En diez locales que no sean amigos se pueden generar, de forma autorizada, al menos 75 € de ingreso bruto por local y mes y 60 € por hora humana, contando únicamente dinero realmente abonado?**

Si no, ID-01 permanece descartado.
