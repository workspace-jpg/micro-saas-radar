# Registro de investigación — Barrido #2, 12 de agosto de 2026

## 1. Metodología y cobertura

- **Mandato:** terreno nuevo. Categorías explícitamente excluidas por haber sido cubiertas en el barrido #1: cumplimiento normativo fiscal/laboral (Verifactu, factura electrónica, registro de jornada), desperdicio alimentario, atención a la clientela, movilidad al trabajo, CAE, accesibilidad, SDDR, gases fluorados, alquiler de corta duración, licitaciones, NIS2, transparencia retributiva, y todo lo relacionado con hostelería y delivery.
- **Consultas realizadas:** 16 búsquedas web + 1 descarga y extracción directa de fuente oficial.
- **Fuentes registradas:** 22.
- **Fuente primaria obtenida:** FAQ oficial del DeCA del Ministerio de Transportes y Movilidad Sostenible. La web bloquea el servicio de lectura automática (HTTP 403), así que se descargó con petición HTTP normal y se extrajo el texto. Es la fuente que decide el resultado del barrido.

### Limitaciones

1. **No he investigado extensiones de navegador ni Manifest V3**, que estaba en el plan. Se agotó el presupuesto de búsquedas en verificar el DeCA, que era la señal con más recorrido. Queda pendiente para un barrido futuro.
2. Los datos de dolor de talleres (71 % gestiona citas por teléfono) y de clínicas (no-show del 18–22 %, 2.500–7.500 €/mes perdidos) **provienen de blogs de proveedores de software**, es decir, de parte. Fiabilidad baja. No los uso como base de ninguna recomendación.
3. El recuento de tiendas Shopify en España (35.443) es de **BuiltWith y está fechado en mayo de 2025**: es la cifra más reciente que he podido verificar, no un dato de 2026.
4. No he verificado el número exacto de empresas de transporte de viajeros con autorización VD: la estadística oficial existe (Observatorio del Transporte de Viajeros) pero no devolvió la cifra en la búsqueda.

---

## 2. Señales encontradas

### Señal 1 — DeCA: obligación con fecha, mercado ya ocupado

**Hechos verificados en fuente oficial** (FAQ del Ministerio de Transportes, consultada 12/08/2026):

| Hecho | Detalle |
|---|---|
| Fecha | **5 de octubre de 2026**, por la Disposición Transitoria octava de la **Ley 9/2025 de Movilidad Sostenible** |
| Sin gracia | *"No está prevista en las normas ninguna fase adicional, más allá del 5 de octubre, donde no se sancione la obligación de digitalización"* |
| Alcance | Transporte **interior** (nacional y cabotaje) de mercancías **públicas** + **hoja de ruta** del transporte público de viajeros |
| Exento | **Transporte privado complementario** (52.775 empresas quedan fuera) y **servicios de paquetería** |
| El Ministerio NO da app | *"El DeCA no es una aplicación informática del Ministerio... Cada empresa debe disponer de una aplicación donde se gestionen los datos del DeCA, bien de forma propia o bien contratar a un proveedor de servicios"* |
| Sin plataforma central | *"No hay que subir todos los DeCA a ninguna plataforma del Ministerio"*, pero los PDF *"deben estar disponibles en un repositorio para descarga por las autoridades"* |
| Sin certificación | *"No, no hay que certificar las aplicaciones informáticas del DeCA"* → barrera de entrada nula, para cualquiera |
| **Firma NO obligatoria** | Ni en mercancías ni en viajeros. Voluntaria; si se firma, debe ser AdES o QES (eIDAS) |
| Datos mínimos | Mercancías: 8 campos (art. 6 Orden FOM/2861/2012). Viajeros: 6 campos (art. 2 Orden FOM/1230/2013) |
| Responsabilidad | Mercancías: **cargador contractual y transportista efectivo**, ambos obligados a formalizarlo. Viajeros: solo la empresa transportista |
| Sanción | Papel en inspección = infracción grave LOTT: **401–2.000 €** + inmovilización de vehículo y carga |
| Universo | **154.101** empresas de transporte de mercancías (mayo 2026, Ministerio); de ellas **101.326 de transporte público** y 62.272 con vehículos pesados |
| Preparación | Solo el **17 %** se considera preparado; 35 % mal preparado y 23 % nada (Fenadismer + Continental, oct. 2025, n=750) |

**Contra-evidencia que lo descarta:**

- Mercancías: **TrazaQR** vende a **9,90 €/mes** (hasta 75 expediciones) o **0,13 €/expedición**; **Pretium Gestión** ofrece **acceso gratuito hasta el 2 de octubre de 2026**; **Digitaldocu** desde 100 €/mes. Más Dashdoc, Alpega, Routal, BlueCMR, Fieldeas, Logalty, Kaleidotrans, Movingcert, controla-plus, polpoo y "DeCA fácil".
- Viajeros: **CONFEBUS ha lanzado RutaBUS**. Es la confederación del sector: >30 organizaciones federadas, ~2.000 empresas asociadas, >70 % de representatividad.
- Un blog afirmaba que el Ministerio ofrecía un canal de emisión gratuito para autónomos; **la fuente oficial lo desmiente**. Registrado porque muestra por qué no se puede puntuar sobre fuentes secundarias.

**Ideas que la fuente primaria mató directamente:** vender firma electrónica para el DeCA (no es obligatoria), vender certificación de la aplicación (no existe), vender a paquetería o a transporte privado complementario (exentos), vender eCMR como obligación (no lo es: *"No, no es obligatorio el eCMR"*).

### Señal 2 — Shopify retira el checkout heredado el 26 de agosto de 2026

- Shopify retira `checkout.liquid`, *Additional Scripts* y *Shopify Scripts*; los sustituyen las *checkout UI extensions*, *Shopify Functions* y *Shopify Pixels*. Fecha para Basic, Shopify y Advanced: **26 de agosto de 2026**. El bloqueo duro empezó el **13 de agosto de 2026** para ~5.200 tiendas Plus. *Shopify Scripts* → *Functions*: 30 de junio de 2026.
- *"Any Additional Scripts, app script tags, or deprecated customizations on the Thank You page and Order Status page are removed, not migrated"*: se rompen conversiones de Google Ads, píxel de Meta, contenedores de GTM y scripts de afiliación.
- Mercado: **35.443 sitios Shopify en España** (BuiltWith, may. 2025), el 21,83 % del comercio electrónico español, por detrás de WooCommerce.
- Competencia: Elevar (250–1.000 $/mes), Littledata (109–1.900 $/mes), Analyzify (200–500 $ único), WeltPixel, Stape, TagFly, Trackify, Converlay.

### Señal 3 — Google Business Profile endurece la política en 2026

- Aumento de eliminaciones de reseñas sin aviso: pico en julio de 2025 con ~2 % de las ubicaciones monitorizadas perdiendo al menos una reseña en una semana.
- En 2026 se prohíbe pedir que la reseña mencione a un empleado, usar tabletas o quioscos para recogerlas y ofrecer incentivos. Incumplir puede suponer eliminación masiva o suspensión del perfil.
- Perfiles sin actualizar más de 30 días pierden visibilidad progresivamente.
- Fiabilidad: media. Fuentes de agencias y de un hilo de soporte de Google, no comunicación oficial.

### Señal 4 — Tareas administrativas que las empresas siguen contratando a mano

Ofertas de empleo activas en España (agosto 2026) que describen literalmente trabajo automatizable: *"grabación de facturas en el programa PeopleSoft"* (Tragsa), *"cotejo de albaranes con pedidos de compra/entrega e introducción de datos en el sistema"*, *"confirmación de facturas de proveedores"* (Eurofirms), *"grabación y transcripción de datos"*. Señal válida de dolor, pero apunta a una categoría —captura de documentos y conciliación a tres bandas— con competencia consolidada.

### Señal 5 — Amazon: menos dolor, no más

Amazon **redujo** tarifas en 2026: −0,20 €/unidad de media en logística FBA estándar en España (desde el 15/12/2025), −0,45 €/unidad en productos de bajo precio, y comisiones de Ropa del 8 % al 5 %, Hogar del 15 % al 8 %, Alimentación del 8 % al 5 %. Un mercado donde el proveedor acaba de bajar precios es un mal sitio para vender recuperación de costes.

### Señal 6 — WhatsApp Business API

Desde julio de 2025 Meta cobra **por plantilla entregada**, no por conversación. En España: ~0,0077 $ por mensaje de utilidad y ~0,0571 $ por marketing. Un negocio con 100–200 citas/mes gasta 89–150 €/mes en plataformas todo-en-uno. Es un cambio real de coste, pero de importe demasiado pequeño para sostener un producto.

---

## 3. Regla de descarte incorporada al método

> **Regla de la patronal.** Cuando una obligación legal afecta de forma masiva y homogénea a un sector organizado, la asociación sectorial publica una herramienta gratuita o muy barata antes de la fecha límite. Ya ha ocurrido dos veces: Hostelería de España con `hosteleriacircular.es` (Ley 1/2025) y CONFEBUS con RutaBUS (hoja de ruta digital).
>
> **Consecuencia operativa:** antes de puntuar cualquier oportunidad de cumplimiento normativo, comprobar qué ha publicado la patronal del sector. Si ya hay herramienta asociativa, la oportunidad muere salvo que se ataque un segmento que la patronal no cubre.
