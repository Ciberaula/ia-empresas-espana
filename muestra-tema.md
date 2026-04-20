---
title: Muestra del tema Ciberaula
nav_order: 99
nav_exclude: true
permalink: /muestra-tema/
description: Página de demostración visual del tema Ciberaula — muestra todos los componentes editoriales disponibles.
---

# Muestra visual del tema Ciberaula

Esta es la **entradilla** del artículo — el primer párrafo que debe introducir al lector al contenido. Tiene el borde izquierdo coral y un tamaño ligeramente mayor al cuerpo, para marcar que es la puerta de entrada del texto.
{: .lead}

Después de la entradilla viene el cuerpo normal del artículo. Este texto debería tener una tipografía **Outfit** de 17px con line-height 1.75, cream como fondo y un ancho máximo de 820 píxeles para que la lectura sea cómoda. Los **strong** van en navy más oscuro, y los enlaces como [este que lleva a ciberaula.com](https://www.ciberaula.com) llevan un subrayado sutil en coral.

## Sección de nivel 2

Los H2 tienen Plus Jakarta Sans, color Navy, con un borde inferior fino que separa las secciones. Se usan para organizar el contenido en apartados principales del artículo.

### Subsección H3

Los H3 son Outfit semibold, más pequeños, sin borde. Usa H3 para dividir una sección H2 en subapartados.

## Componentes editoriales disponibles

### Callouts (cajas de aviso)

> Este es un callout informativo. Úsalo para información complementaria útil pero no crítica. El fondo es Sage Light y el borde izquierdo Sage.
{: .callout-info }

> Este es un callout de aviso. Úsalo para plazos importantes, requisitos legales o puntos que no se pueden pasar por alto. El fondo ámbar llama la atención sin ser alarmista.
{: .callout-warning }

> Este es un callout de peligro. Úsalo para errores comunes, prohibiciones o sanciones. El color coral se reserva para lo más serio.
{: .callout-danger }

### Pull-quote (cita destacada)

> Esta guía se publica bajo licencia abierta (CC BY-SA 4.0) para que cualquier empresa, formador o consultor pueda usarla, adaptarla y compartirla sin pedir permiso.
{: .pull-quote }

### Tarjeta de estadística

<div class="stat">
  <span class="stat-number">85%</span>
  <span class="stat-label">de empresas españolas invierten o planean invertir en IA</span>
  <span class="stat-source">Fuente: KPMG 2025</span>
</div>

### Grid de varias estadísticas

<div class="stat-grid">
  <div class="stat">
    <span class="stat-number">36%</span>
    <span class="stat-label">PYMES españolas que ya usan IA</span>
    <span class="stat-source">INE 2024 + DESI</span>
  </div>
  <div class="stat">
    <span class="stat-number">72%</span>
    <span class="stat-label">proyectos IA que fracasan por mala implementación</span>
    <span class="stat-source">McKinsey State of AI 2024</span>
  </div>
  <div class="stat">
    <span class="stat-number">60%</span>
    <span class="stat-label">empresas que prevén IA como miembro activo del equipo en 2026</span>
    <span class="stat-source">Capgemini 2025</span>
  </div>
</div>

### Key-point (idea clave destacada)

La formación del personal en IA no es opcional a partir de agosto 2026: el artículo 4 del AI Act exige alfabetización obligatoria y es **actividad bonificable al 100% con FUNDAE**.
{: .key-point }

## Listas

Las listas con viñetas llevan el marker en coral:

- Primer punto de la lista
- Segundo punto con **texto en negrita**
- Tercer punto con un [enlace interno](/cumplimiento/)

Las numeradas llevan el número en navy:

1. Primer paso del proceso
2. Segundo paso documentado
3. Tercer paso con evaluación

## Tablas

Las tablas usan la cabecera Navy con texto Cream, y filas alternas Warm-White:

| Plazo | Obligación | Impacto en PYMES |
|-------|------------|------------------|
| 2 agosto 2024 | Entrada en vigor del AI Act | Inicio del cómputo de plazos |
| 2 febrero 2025 | Prohibiciones y alfabetización | Plan de formación del personal |
| 2 agosto 2025 | Modelos de propósito general | Transparencia en uso de LLMs |
| 2 agosto 2026 | Sistemas de alto riesgo | Gestión completa obligatoria |

## Código

Inline: `remote_theme: Ciberaula/ciberaula-theme`

En bloque:

```yaml
# _config.yml
title: Mi sitio
remote_theme: just-the-docs/just-the-docs@v0.7.0
color_scheme: light

plugins:
  - jekyll-remote-theme
  - jekyll-seo-tag
```

## Cita normal (sin clase especial)

> Una cita normal tiene un estilo discreto: solo un borde izquierdo gris y el texto en italic. Se usa para referencias o aclaraciones de segunda importancia.

---

Esto es todo. Los componentes se pueden combinar libremente para enriquecer cualquier artículo del ecosistema GEO.
