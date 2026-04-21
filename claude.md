# Portfolio Julieta Carmona — Plan Completo
*Documento de contexto para continuar en otro chat*

---

## Objetivo estratégico
Conseguir trabajo remoto internacional como **Vibe Coder / AI Automation Lead** en la consultora de Gonza (NocodeHackers/Modulor Studios) o perfil similar. Plazo: 2 meses. Target: $3,000–4,500 USD/mes.

El portfolio tiene que demostrar que Julieta **construye sistemas**, no solo hace tareas. Cada proyecto se presenta como una decisión de diseño, no como una lista de herramientas usadas.

---

## Stack de referencia (NocodeHackers)
Lo que Gonza enseña y va a mirar en el portfolio:
- **Vibe coding:** Claude Code, Lovable, Bolt, V0, Cursor, Replit
- **Automatización:** n8n, Make, Zapier, Gumloop
- **Bases de datos:** Airtable, Notion, Supabase
- **Web builders:** Framer, Webflow, Netlify
- **Internal tools:** Retool, Appsmith
- **AI:** Claude API, ChatGPT

---

## Los 5 Proyectos

### 01 — Catálogo Interactivo del Parque de Innovación CABA
**Tipo:** Vibe Code
**Stack real:** Airtable + Claude Code + HTML/JS
**Stack a mostrar:** Airtable · Claude Code · Make · HTML/JS · Vercel

**Historia:**
El Parque tenía la necesidad de comunicar su ecosistema de startups a visitantes: tanto en pantallas de TV en el espacio físico como en formato web interactivo. Julieta diseñó y construyó el sistema completo: una fuente única de datos en Airtable que alimenta dos interfaces distintas — el slider de TV y el catálogo web navegable. Make automatiza la sincronización cuando se actualiza el contenido.

**Lo que se suma/embellece:**
- Se agrega Make como capa de automatización (notificaciones cuando se actualiza Airtable)
- Se presenta como "sistema dual" (TV + web), no solo como catálogo

**Estado del demo:**
- Existe versión hosteada en Vercel (sin datos reales, versión pública)
- La versión final con datos reales la tiene el compañero desarrollador y corre conectada a Airtable de producción
- **Frase clave para el portfolio:** *"El deploy final corre contra la base de datos real de producción. Por privacidad, el link público muestra una versión demo con datos ficticios."*

**Pendiente:** Agregar slider de TV a la versión propia usando Claude Code (tiene el código base, el slider no está implementado)

**Resultado a mostrar:**
- Sistema en uso real en el Parque de Innovación CABA
- Eliminó el proceso manual de actualización de contenido en pantallas
- [Agregar métricas si las tiene]

---

### 02 — Infraestructura de Datos del Parque de Innovación CABA
**Tipo:** Automation / Systems
**Stack real:** n8n/Make + Airtable + Claude API + Power BI
**Stack a mostrar:** n8n · Airtable · Make · Claude API · Power BI

**Historia:**
Al llegar al Parque, los datos de contacto estaban dispersos en planillas desconectadas. Julieta construyó desde cero la infraestructura de datos completa: CRM con 10.000+ contactos, pipelines de automatización para onboarding, scoring de contactos, asistente interno con IA (PIA) y dashboards de seguimiento para el equipo directivo.

**Lo que se embellece:**
- Se presenta como sistema integrado completo, no como automatizaciones sueltas
- Se agrega framing de "reemplazó trabajo manual de un equipo" con métricas de tiempo ahorrado
- El asistente PIA se presenta como producto IA construido con Claude API

**Sin assets visuales — cómo lo muestra un senior:**
- Diagrama de arquitectura del sistema (dibujado en HTML/CSS, no screenshots)
- Big numbers como protagonistas: 10.000+ contactos, X horas/semana ahorradas
- Terminal-style snippet mostrando lógica de automatización
- Schema de Airtable (anonimizado o ficticio)

**Resultado a mostrar:**
- CRM de 10.000+ contactos construido desde cero
- [X] horas semanales de trabajo manual eliminadas
- Asistente IA en uso activo por el equipo

---

### 03 — Synerfy: Plataforma B2B de Networking para Eventos
**Tipo:** Product Build / Vibe Code
**Stack a mostrar:** Claude Code · Airtable · n8n · Tailwind · Framer

**Historia:**
Julieta co-fundó Synerfy y construyó el sistema completo de la plataforma: landing de evento white-labeled (colores y branding customizables por cliente), registro automático de participantes, generación de tarjeta digital personalizada, y panel de administración multi-tenant. Una empresa puede deployar un evento de networking end-to-end sin tocar código.

**Lo que se embellece:**
- Se agrega n8n como pipeline de registro (participante se registra → se crea su tarjeta → recibe email de bienvenida → aparece en dashboard)
- Se presenta como producto SaaS, no como proyecto freelance

**Assets existentes (archivos ya construidos):**
- `synerfy-admin-darkmode-V2.html` — Panel admin completo con dark/light mode, multi-tenant, stats
- `synerfy-admin-mockup-V2.html` — Mockup del admin
- `synerfy-event-landing-v2_2.html` — Landing de evento white-labeled con colores variables en CSS
- `tarjeta-digital-V1.html` — Tarjeta digital de participante con múltiples themes

**Colores Synerfy:** `#EC3A5C` → `#FDB848` (gradient principal)

**Resultado a mostrar:**
- Sistema completo deployable end-to-end
- [X] eventos gestionados / [X] participantes
- Multi-tenant: múltiples organizaciones desde un solo panel

---

### 04 — Sistema de Gestión de Proyectos — Educabot
**Tipo:** Vibe Code (construido ahora)
**Stack a mostrar:** Lovable · Supabase · n8n · Airtable

**Historia:**
Al entrar como Delivery Manager en Educabot (edtech de robótica/programación/IA para chicos), el seguimiento de proyectos educativos se hacía en hojas de cálculo dispersas entre tres equipos (técnico, pedagógico y comercial). Julieta construyó una herramienta interna centralizada con visibilidad en tiempo real del avance de cada proyecto, alertas automáticas de hitos y dashboard para el CEO.

**Estado:** Pendiente de construir. El problema es REAL (ella es Delivery Manager ahí). Se construye con Lovable + Supabase + n8n.

**Resultado a mostrar:**
- [X] proyectos activos centralizados
- Eliminó [X] reuniones de seguimiento semanales
- Visibilidad en tiempo real para Fede (CEO) y COO

---

### 05 — Takenos Wallet: UX Design → Prototipo Funcional
**Tipo:** UX Design + Vibe Code
**Stack a mostrar:** Figma · Bolt (o V0) · Vercel

**Historia:**
Julieta diseñó los flujos de pago de la wallet de Takenos desde research hasta entrega en Figma. El diferencial: una vez aprobados los diseños, construyó un prototipo navegable funcional sin esperar al equipo de desarrollo. Esto aceleró el ciclo de feedback con stakeholders.

**Frase clave:** *"Sin esperar al equipo de desarrollo."* — eso es exactamente lo que hace un vibe coder.

**Assets:** Slides de Figma (formato ideal para portfolio: exportar frames clave como PNG + link a prototipo Figma al final, NO iframe)

**Pendiente:** Construir prototipo funcional en Bolt/V0 y deployar en Vercel

---

## Template de Case Study (mismo formato para los 5)

```
HEADER
  [Número del proyecto]
  Título
  Tipo: Vibe Code / Automation / Product Build / UX+Vibe Code
  Stack: [logos de herramientas]
  Año + Contexto (empresa o proyecto)

SECCIÓN 1 — El problema
  1 párrafo. Qué existía antes, qué costaba, en números si hay.

SECCIÓN 2 — Cómo lo pensé  ← acá está la cabeza
  Qué decidí NO hacer. Qué trade-offs.
  Por qué esto es un sistema y no una tarea suelta.
  (Esta sección diferencia un portfolio senior de uno junior)

SECCIÓN 3 — Qué construí
  → Si tiene visuals: screenshots / mockups / demo embebida
  → Si NO tiene visuals (proyecto 02): diagrama de arquitectura CSS + big numbers + snippet de lógica

SECCIÓN 4 — Stack detallado
  Cada herramienta y por qué esa y no otra.

SECCIÓN 5 — Resultado
  Número concreto o cambio observable.

FOOTER
  → Ver demo / Ver siguiente proyecto
```

---

## Diseño del Portfolio

**Archivo principal:** `portfolio_julieta_clean.html` (en /mnt/project/)

**Design tokens:**
- Accent: `#F95564`
- Dark bg: `#120b0c` / `#1a0f10` / `#221417`
- Light bg: `#fdf8f6` / `#f0e8e4`
- Fonts: DM Serif Display (headings, italic), DM Sans (body), Raleway (labels uppercase)
- Border: `rgba(255,255,255,0.07)` dark / `rgba(0,0,0,0.09)` light
- Muted text: `#9a8080` dark

**Estilo general:** editorial, dark-first, minimal, uppercase labels con letter-spacing, glows sutiles en accent color

**Template de case study:** archivo separado `case-study-template.html` con los mismos tokens — listo para duplicar por proyecto

---

## Pendientes por hacer (en orden)

1. **Proyecto 01 — Catálogo:** Agregar slider de TV al código existente con Claude Code
2. **Template case study:** ✅ Ya existe (ver `case-study-template.html`)
3. **Proyecto 04 — Educabot:** Construir en Lovable + Supabase
4. **Proyecto 05 — Takenos:** Construir prototipo en Bolt/V0 + exportar frames de Figma
5. **Escribir copy** de los 5 casos (secciones: problema, cómo lo pensé, resultado)
6. **Integrar los 5 casos** al portfolio principal

---

## Notas importantes

- Julieta NO es desarrolladora — el framing siempre es "vibe coder / builder", no "developer"
- Los proyectos se presentan con criterio: algunas herramientas se suman con lógica aunque no hayan sido las originales (ej. Make en proyecto 01, n8n en proyecto 03)
- La frase *"El deploy final corre contra la base de datos real de producción"* cubre el gap entre versión demo y versión real
- Para el proyecto 02 sin visuals: el senior approach es mostrar arquitectura y números, NO disculparse por no tener screenshots
