# Sistema comercial y CRM

## 1. Principio

El CRM sirve para decidir la siguiente acción y aprender qué convierte. No es un almacén de negocios copiados de Google. Airtable es el CRM operativo; GitHub conserva estrategia, evidencia, playbooks y casos, sin duplicar datos personales innecesarios.

## 2. Pipeline y criterios de salida

| Etapa | Definición | Para avanzar |
|---|---|---|
| Prospecto | Cumple ICP y tiene fuente verificable | Señal concreta + decisor/canal |
| Investigado | Hay hipótesis y evidencia pública | Mensaje personalizado preparado |
| Contactado | Primer contacto enviado | Fecha y siguiente seguimiento |
| Respondió | Existe conversación bidireccional | Dolor o falta de dolor registrada |
| Discovery | Llamada acordada o realizada | Proceso, impacto, decisor y datos |
| Diagnóstico propuesto | Alcance/precio enviado | Decisión con fecha |
| Diagnóstico ganado | Pago recibido | Kickoff y datos |
| Implementación propuesta | Diagnóstico confirma retorno | Alcance fijo + KPI + depósito |
| Implementación ganada | Depósito recibido | Fecha de entrega |
| Recurrencia | Resultado requiere operación continua | Acuerdo mensual |
| Perdido | Rechazo o umbral fallido | Motivo normalizado |
| Pausado | Momento inadecuado, pero señal real | Fecha futura concreta |

No usar “interesado” como etapa: es ambiguo.

## 3. Campos mínimos de Airtable

### Identidad y acceso

- Empresa
- Vertical
- Ciudad
- Número de locales
- URL
- Contacto
- Rol del contacto
- Canal autorizado
- Fuente
- Relación de Fran: ninguna / fría / conocida / trabajó allí / referido

No guardar números personales en GitHub. En Airtable, registrar solo los datos necesarios y con acceso restringido.

### Evidencia

- Señal observable
- URL o fuente de la señal
- Dolor: desconocido / hipotético / confirmado / cuantificado
- Proceso afectado
- Volumen mensual
- Coste/fuga estimada
- Fuente de la cifra
- Sistemas implicados
- Acceso a datos: no / parcial / sí

### Comercial

- Etapa
- Score
- Prioridad
- Último contacto
- Próxima acción
- Fecha próxima acción
- Oferta propuesta
- Importe propuesto
- Importe cobrado
- Decisor confirmado
- Motivo de pérdida

### Producto

- Workflow candidato
- Porcentaje común estimado
- Frecuencia de uso
- Integración oficial disponible
- Potencial de recurrencia
- Caso de estudio autorizado

## 4. Score de prioridad / 100

| Criterio | Peso |
|---|---:|
| Acceso al decisor | 25 |
| Dolor demostrado | 25 |
| Impacto económico posible | 20 |
| Urgencia | 10 |
| Datos disponibles | 10 |
| Piloto acotable | 10 |

Aplicar penalizaciones:

- −20 si el contacto o canal no está verificado.
- −20 si el proyecto requiere integración crítica sin API/autorización.
- −15 si el comprador no está identificado.
- −15 si el dolor solo es estético y no afecta conversión, coste o riesgo.
- −10 si la entrega será altamente personalizada.

El score no prevalece sobre una relación directa. Grupo Boulevard es prioridad por acceso y aprendizaje, aunque otro lead tenga más puntos brutos.

## 5. Mensajería

### Contacto cálido

> Hola, [nombre]. Soy Fran; trabajé con vosotros en [contexto]. Ahora estoy ayudando a negocios de restauración a localizar y eliminar trabajo operativo manual. Antes de proponerte nada, quería preguntarte algo muy concreto: ¿seguís juntando a mano información de ventas, compras, personal, reservas o delivery entre locales, o lo tenéis resuelto? Si tiene sentido, lo vemos 10 minutos y si no, te lo digo claro.

### Contacto frío con señal

> Hola, [nombre/equipo]. He visto [señal verificable]. No sé si por detrás os genera [hipótesis de fricción]; prefiero preguntarlo antes de asumirlo. Si lo lleváis manual, os enseño en un minuto cómo mediría el impacto. ¿Quién gestiona esa parte?

### Después de confirmar dolor

> Tiene sentido. Para no venderte una automatización a ciegas, haría primero un diagnóstico acotado: proceso actual, cifra de impacto, tres prioridades y plan de 30 días. Cuesta [precio] y se descuenta si implementamos la primera mejora. ¿Vemos alcance y datos el [día]?

### Seguimiento

1. Día 0: mensaje original.
2. Día 3: aportar una observación o pregunta nueva; no “¿lo viste?”.
3. Día 7: cierre de bucle breve.
4. Día 21–30: solo si existe evento o señal nueva.

Máximo tres intentos sin respuesta antes de pausar.

## 6. Secuencia de ventas

1. **10–15 min:** confirmar si merece discovery.
2. **45–60 min:** discovery estructurado.
3. **24 h:** resumen de problema, impacto y alcance de diagnóstico.
4. **Pago:** antes de pedir trabajo interno relevante.
5. **5 días laborables:** entrega del diagnóstico.
6. **48 h:** decisión sobre implementación.
7. **50 % de depósito:** antes de construir.

## 7. Métricas semanales

### Actividad

- prospectos nuevos cualificados;
- contactos personalizados;
- seguimientos;
- conversaciones con decisor;
- horas invertidas en demos gratuitas.

### Conversión

- respuesta/contacto;
- discovery/respuesta;
- diagnóstico propuesto/discovery;
- diagnóstico pagado/propuesto;
- implementación pagada/diagnóstico;
- días hasta primer pago.

### Economía

- efectivo cobrado;
- pipeline ponderado;
- ticket medio;
- horas por diagnóstico;
- margen de contribución;
- MRR real.

### Aprendizaje

- dolores confirmados;
- hipótesis refutadas;
- workflows repetidos;
- datos entregados por clientes;
- integraciones bloqueantes.

## 8. Umbrales de intervención

- Respuesta <10 % tras 30 contactos muy personalizados: cambiar ICP, señal o canal; no enviar más volumen igual.
- Respuestas pero cero discovery en 10 conversaciones: la pregunta no lleva a dolor o el contacto no es decisor.
- Discovery pero cero diagnóstico pagado en 5 propuestas: el diagnóstico está mal posicionado, el impacto es débil o el precio no está justificado.
- Diagnósticos pagados pero cero implementación en 3 casos: revisar calidad, urgencia y capacidad de ejecución.
- Más de 45 min por demo sin respuesta: detener ese formato.

## 9. Panel mínimo

El dashboard debe mostrar:

1. Efectivo cobrado este mes.
2. Próximas acciones vencidas/hoy.
3. Conversión por etapa.
4. Pipeline por importe y probabilidad.
5. Tiempo invertido en trabajo gratuito.
6. Dolor confirmado por categoría.
7. Workflows repetidos y puerta de productización.

No priorizar gráficos decorativos.

## 10. Leads activos y siguiente acción

| Lead | Estado | Hipótesis | Siguiente acción |
|---|---|---|---|
| Grupo Boulevard | Prioridad 1 | reporting/operativa multi-local manual | contacto directo y llamada de 15 min |
| ASH | Lead caliente | eventos, waitlist y membresías desconectados | discovery y diagnóstico/diseño pagado |
| La Damasco | Prospecto | fricción de confianza/conversión web | microauditoría de 60 s si responde |
| TOKI Sushi | Prospecto | gestión manual de reservas por WhatsApp | preguntar antes de demostrar |
| Prospectos CUADRE | Validación | cargos reclamables no revisados | obtener 3 juegos de liquidaciones |

## 11. Registro de experimentos

Cada experimento comercial debe guardar:

- fecha;
- segmento;
- hipótesis;
- mensaje/oferta;
- número de contactos;
- respuestas;
- discoveries;
- pagos;
- tiempo invertido;
- resultado;
- decisión.

Una prueba sin umbral definido antes de ejecutarla se convierte fácilmente en autoengaño.
