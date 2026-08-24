# Prompt maestro para Claude Code — ASH sales demo

## Objetivo

Construir una **demo visual interactiva, local y premium** de `ASH Member OS` para enseñarla en una llamada comercial a Athletic Social House.

Esto **NO es el MVP**, no debe conectarse todavía a APIs reales y no debe convertirse en un proyecto grande. Es una pieza de venta que debe hacer que el cliente entienda en 30–60 segundos cómo se vería su operación unificada.

## Prompt

Actúa como **senior product designer + senior frontend engineer + especialista en SaaS B2B premium**.

Estamos preparando una demo comercial para un posible cliente real: **ASH | Athletic Social House**.

Antes de tocar código:

1. Lee todo el contexto disponible del repositorio.
2. Lee especialmente `clients/ash/2026-08-24-call-prep.md`.
3. No inventes integraciones reales ni afirmes que algo está conectado si no lo está.
4. Si existe ya una app/frontend adecuado, reutilízalo. Si no existe, crea una demo aislada y limpia dentro de una carpeta claramente identificada, por ejemplo `clients/ash/demo/`.
5. No cambies ni rompas el resto del repositorio.

---

# MISIÓN

Crear un primer prototipo navegable llamado:

# ASH HQ

Subtítulo discreto:

**Member & Community Intelligence**

El objetivo del visual es vender esta idea:

> ASH puede ver en un solo sitio qué está pasando con su waitlist, eventos, comunidad y futuros miembros, y saber quién requiere atención.

No debemos vender "un dashboard". Debe sentirse como el **sistema operativo privado de ASH**.

---

# PRINCIPIOS DE DISEÑO

La interfaz debe sentirse:

- premium
- editorial
- deportiva
- social
- moderna
- sobria
- boutique
- clara
- con mucho aire
- muy alejada del aspecto genérico de un admin template

Evita:

- degradados SaaS morado/azul genéricos
- exceso de tarjetas
- iconos infantiles
- glassmorphism abusivo
- aspecto crypto
- aspecto fintech estándar
- gráficas decorativas sin función
- dashboards sobrecargados

La demo debe parecer software hecho específicamente para una marca de fitness/social club premium.

---

# REFERENCIA DE MARCA

Usa el nombre **ASH | Athletic Social House**.

No copies assets protegidos si no están disponibles en el repositorio. Si el logo real no está disponible, crea una marca tipográfica elegante usando `ASH` y `Athletic Social House`.

Construye una paleta contenida inspirada en:

- fondo marfil / off-white
- negro carbón
- gris cálido
- un acento muy limitado tipo azul atlántico o verde profundo

No fijes una estética chillona.

Tipografía:
- sans serif limpia para UI
- jerarquía editorial fuerte
- números grandes para KPIs

---

# STACK

Prioridad: velocidad y estabilidad.

Si no hay stack frontend existente:

- React
- Vite
- TypeScript
- Tailwind CSS
- Lucide Icons
- Recharts solo si una gráfica aporta valor real

La app debe arrancar localmente con instrucciones simples.

No backend.
No autenticación real.
No base de datos real.
No APIs externas.
No pagos.
No Airtable todavía.

Todos los datos deben ser **mock data claramente ficticios**.

---

# PANTALLA PRINCIPAL QUE DEBE QUEDAR PERFECTA

Ruta inicial: `/`

## Header

Izquierda:
- ASH
- Athletic Social House

Centro o navegación lateral minimalista:
- Overview
- Waitlist
- Members
- Events
- Community
- Automations

Derecha:
- selector de periodo `Last 30 days`
- avatar/equipo discreto

---

# OVERVIEW

Encabezado:

**Good morning, ASH**

Texto secundario:

`Your community is moving. Here’s what needs attention.`

## KPI strip

Usa datos ficticios coherentes:

- Waitlist: `487`
  - +42 this month

- Hot leads: `26`
  - 9 need follow-up

- Event attendees: `184`
  - 61% returning

- Founding members: `38`
  - 7.8% waitlist conversion

No pongas 20 KPIs.

---

# BLOQUE 1 — MEMBER FUNNEL

Visual simple y elegante:

`487 Waitlist → 184 Engaged → 96 High Intent → 38 Founding Members`

Debajo, una frase pequeña:

`12 people moved to High Intent after attending an event this week.`

Debe transmitir progresión de comunidad a membership.

---

# BLOQUE 2 — PEOPLE TO CONTACT

Este es el bloque comercialmente más importante.

Título:

**People to contact**

Subtítulo:

`High-intent people who may need a human touch.`

Tabla/lista premium con 4–5 perfiles mock:

1. **Sofia M.**
   - Source: Instagram
   - Attended: Social Run + Sculpt
   - Intent: Hot
   - Last activity: 2h ago
   - CTA: `View profile`

2. **Lucas R.**
   - Source: Referral
   - Attended: 3 events
   - Intent: Hot
   - Last activity: Yesterday

3. **Marta G.**
   - Source: Website
   - Waitlist: 34 days
   - Opened membership invitation
   - Intent: High

4. **Clara P.**
   - Source: Event
   - Attended: Cheeky Moves
   - Intent: High

Mostrar pequeñas pills de estado, pero sin colores exagerados.

---

# BLOQUE 3 — UPCOMING EVENTS

Título:

**Upcoming events**

Ejemplos ficticios:

### Social Run — Palma
`74 / 90 registered`

Barra de ocupación elegante.

Detalles:
- 28 returning guests
- 17 high-intent prospects

### Cheeky Moves
`38 / 50 registered`

Detalles:
- 12 first-time guests
- 9 already on waitlist

Cada evento debe tener CTA `Open event`.

---

# BLOQUE 4 — ACQUISITION

Título:

**Where the community comes from**

Distribución mock:

- Instagram — 37%
- Events — 29%
- Website — 20%
- Referral — 14%

Mostrarlo con barras horizontales limpias o una visualización extremadamente simple.

No donut chart si hace la pantalla más genérica.

---

# BLOQUE 5 — ACTIVITY FEED

Título:

**Live community activity**

Ejemplos:

- Sofia M. attended Social Run
- Lucas R. moved to High Intent
- 8 new people joined the waitlist
- Marta G. opened the Founding Membership invitation
- Cheeky Moves reached 76% capacity

Añadir timestamps pequeños.

La intención es que el cliente vea que el sistema "está vivo".

---

# PERFIL DE PERSONA

Al hacer click en `View profile`, abrir drawer lateral o modal premium.

Ejemplo:

## Sofia Martinez

**High Intent**

- Joined waitlist: 04 Aug 2026
- Source: Instagram
- Interests: Sculpt, Run Club, Recovery
- Events attended: 2
- Last interaction: 2h ago
- Membership invitation: Not sent

### Timeline
- Joined waitlist
- Registered for Social Run
- Attended Social Run
- Registered for Sculpt
- Attended Sculpt
- Lead score increased

CTA principal:

`Invite to Founding Membership`

Este botón NO debe enviar nada de verdad.
Al pulsarlo, mostrar un toast:

`Demo only — membership invitation would be triggered here.`

Esto es importante para no simular una integración real.

---

# AUTOMATIONS

Crear una pantalla secundaria simple para vender el concepto.

Mostrar 3 automatizaciones activas ficticias:

### Event follow-up
`After attendance → wait 18h → send personalized follow-up`

Status: Active

### High intent alert
`If score > 80 → notify community manager`

Status: Active

### Waitlist nurture
`If no activity for 14 days → re-engagement sequence`

Status: Active

Representarlas como flujos visuales simples, no como un editor complejo.

---

# INTERACCIONES QUE QUIERO EN LA DEMO

Implementa únicamente las que mejoren la venta:

1. navegación entre Overview / Waitlist / Events / Automations
2. abrir perfil de persona
3. filtrar waitlist por estado
4. abrir un evento
5. botón demo de invitación con toast
6. pequeños hover states premium

No invertir tiempo en funcionalidad invisible.

---

# WAITLIST

Tabla premium con columnas:

- Person
- Source
- Joined
- Events
- Last activity
- Intent
- Status

Filtros:
- All
- New
- Engaged
- High Intent
- Hot

Incluye unos 15 registros ficticios.

Usa nombres plausibles en España pero no datos reales.

---

# EVENT DETAIL

Al abrir un evento mostrar:

- registros
- capacidad
- first-time attendees
- returning attendees
- high-intent prospects
- porcentaje que ya está en waitlist

Y una lista:

**People worth following up with**

Este concepto es más importante que una gráfica bonita.

---

# RESPONSIVE

Optimizar primero para portátil 1440×900 / 1366×768, porque se enseñará probablemente compartiendo pantalla en una llamada.

Que también sea razonablemente responsive en tablet.

No priorizar móvil.

---

# COPY

Toda la interfaz del software debe estar en **inglés**, porque encaja mejor con el branding de ASH.

El código y README pueden estar en inglés.

Evita claims como:
- AI powered
- revolutionary
- intelligent platform

si no están respaldados.

La tecnología debe venderse por claridad y utilidad, no por buzzwords.

---

# DEMO MODE

Añade en algún lugar discreto:

`Concept demo · Sample data`

Debe verse profesional pero impedir que el cliente crea que los datos son reales.

---

# ENTREGA

Quiero que ejecutes el trabajo, no solo que me expliques cómo hacerlo.

Al terminar:

1. asegúrate de que compila sin errores;
2. ejecuta lint/typecheck si existe;
3. crea `README.md` dentro de la demo con:
   - cómo instalar
   - cómo ejecutar
   - stack
   - qué es mock
   - siguiente paso para convertirla en producto real
4. enumera los archivos creados/modificados;
5. indica el comando exacto para abrir la demo;
6. no implementes integraciones reales sin autorización.

---

# REGLA DE PRODUCTO

Si tienes que elegir entre:

- añadir más funcionalidades
- mejorar el primer pantallazo que verá el cliente

elige siempre **mejorar el primer pantallazo**.

La demo tiene un único KPI:

> que el cliente vea la pantalla y diga: "quiero tener esto para ASH".

Ahora inspecciona el repositorio y empieza a construirlo.