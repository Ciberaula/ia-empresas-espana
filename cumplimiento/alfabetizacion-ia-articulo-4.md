---
title: "El artículo 4 del AI Act: alfabetización en IA obligatoria para empresas"
description: "Guía práctica del artículo 4 del Reglamento (UE) 2024/1689: qué exige, a quién afecta, qué debe cubrir la formación, perfiles profesionales, documentación requerida y errores frecuentes."
author: "Ana María González"
author_role: "Directora de Ciberaula"
published: "2026-04-17"
updated: "2026-04-19"
canonical_url: "https://github.com/Ciberaula/ia-empresas-espana/blob/main/cumplimiento/alfabetizacion-ia-articulo-4.md"
license: "CC BY-SA 4.0"
tags: ["ai-act", "articulo-4", "alfabetizacion-ia", "cumplimiento"]
---

# El artículo 4 del AI Act: alfabetización en IA obligatoria para empresas

El artículo 4 del Reglamento (UE) 2024/1689 obliga a todas las empresas europeas —sin excepción por tamaño— a garantizar que su personal tenga un nivel suficiente de alfabetización en IA. Está en vigor desde el 2 de febrero de 2025. Esta guía explica qué exige, a quién afecta, qué contenidos debe cubrir la formación y cómo documentar el cumplimiento.
{: .lead}

**Última actualización:** 19 de abril de 2026 · **Autora:** Ana María González · **Licencia:** CC BY-SA 4.0

---

<div class="resumen">
<p class="resumen__titulo">Resumen en 30 segundos</p>
<ul>
<li>El artículo 4 obliga a <strong>todas las empresas</strong> que usen o desplieguen IA a garantizar la alfabetización de su personal.</li>
<li>Está <strong>en vigor desde el 2 de febrero de 2025</strong>. Las empresas sin medidas están en incumplimiento.</li>
<li>Exige formación <strong>adaptada al perfil</strong> del trabajador y al contexto de uso de la IA.</li>
<li>El cumplimiento debe ser <strong>demostrable</strong>: documentación, evaluación y certificados.</li>
</ul>
</div>

## Índice

1. [Texto literal y ficha normativa](#texto-literal)
2. [A quién obliga: árbol de decisión](#a-quien-obliga)
3. [Qué significa "nivel suficiente de alfabetización"](#nivel-suficiente)
4. [Los seis bloques temáticos obligatorios](#bloques)
5. [Perfiles profesionales y duración orientativa](#perfiles)
6. [Plan formativo: pasos para cumplir](#plan-formativo)
7. [Documentación mínima para una inspección](#documentacion)
8. [Casos prácticos ilustrativos](#casos-practicos)
9. [Errores frecuentes](#errores)
10. [Preguntas frecuentes](#faq)

---

## <a id="texto-literal"></a>1. Texto literal y ficha normativa

<div class="ficha-normativa">
<dl>
<dt>Norma</dt><dd>Reglamento (UE) 2024/1689</dd>
<dt>Nombre común</dt><dd>AI Act · Reglamento de Inteligencia Artificial</dd>
<dt>Artículo</dt><dd>4 — Alfabetización en materia de IA</dd>
<dt>En vigor desde</dt><dd>2 de febrero de 2025</dd>
<dt>Supervisa en España</dt><dd>AESIA (Agencia Española de Supervisión de la IA)</dd>
<dt>Texto oficial</dt><dd><a href="https://eur-lex.europa.eu/legal-content/ES/TXT/?uri=CELEX:32024R1689">DOUE · CELEX 32024R1689</a></dd>
</dl>
</div>

> Los proveedores y responsables del despliegue de sistemas de IA adoptarán medidas para garantizar que, en la mayor medida posible, su personal y demás personas que se encarguen en su nombre del funcionamiento y la utilización de sistemas de IA tengan un nivel suficiente de alfabetización en materia de IA, teniendo en cuenta sus conocimientos técnicos, su experiencia, su educación y su formación, así como el contexto previsto de uso de los sistemas de IA y las personas o los colectivos de personas en que se van a utilizar dichos sistemas.

Una frase, cinco obligaciones: (1) adoptar medidas activas, (2) garantizar un nivel suficiente, (3) cubrir a todo el personal implicado, (4) incluir a colaboradores externos que actúen en nombre de la empresa, y (5) adaptar el contenido al contexto de uso. No dice "procurar" ni "intentar". Dice **garantizar**.

---

## <a id="a-quien-obliga"></a>2. A quién obliga: árbol de decisión

El artículo 4 se aplica a **proveedores** (desarrollan o comercializan IA) y **responsables del despliegue** (usan IA bajo su autoridad en actividad profesional). Este diagrama determina si tu empresa está obligada:

<svg width="100%" viewBox="0 0 680 490" role="img" style="max-width:680px;margin:1.5rem auto;display:block">
<title>Árbol de decisión: ¿Te aplica el artículo 4?</title>
<defs><marker id="arr" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse"><path d="M2 1L8 5L2 9" fill="none" stroke="context-stroke" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></marker></defs>
<style>
  text{font-family:"Outfit",sans-serif}
  .q{fill:#1B2A4A;font-size:13px;font-weight:600}
  .r{fill:#5F5E5A;font-size:12px}
  .lbl{font-size:12px;font-weight:700}
  .yes{fill:#1D9E75}
  .no{fill:#993C1D}
  .conclusion{fill:#FAFAF7;font-size:14px;font-weight:600}
  .concl-sub{fill:#F0997B;font-size:12px}
  .note{fill:#888780;font-size:11px;font-style:italic}
  @media(prefers-color-scheme:dark){
    .q{fill:#D3D1C7} .r{fill:#B4B2A9} .note{fill:#888780}
    .conclusion{fill:#FAFAF7} .concl-sub{fill:#F0997B}
  }
</style>
<rect x="220" y="12" width="240" height="38" rx="19" fill="#E6EAF4" stroke="#1B2A4A" stroke-width="0.5"/>
<text class="q" x="340" y="35" text-anchor="middle">Tu empresa</text>
<line x1="340" y1="50" x2="340" y2="80" stroke="#888780" stroke-width="1" marker-end="url(#arr)"/>
<rect x="160" y="80" width="360" height="50" rx="8" fill="#E6F1FB" stroke="#185FA5" stroke-width="0.5"/>
<text class="q" x="340" y="100" text-anchor="middle">¿Usa algún sistema de IA</text>
<text class="q" x="340" y="116" text-anchor="middle">en su actividad profesional?</text>
<line x1="520" y1="105" x2="580" y2="105" stroke="#888780" stroke-width="1" marker-end="url(#arr)"/>
<text class="lbl no" x="550" y="97">No</text>
<rect x="582" y="90" width="80" height="30" rx="6" fill="#F1EFE8" stroke="#B4B2A9" stroke-width="0.5"/>
<text class="r" x="622" y="109" text-anchor="middle">No aplica</text>
<line x1="340" y1="130" x2="340" y2="172" stroke="#888780" stroke-width="1" marker-end="url(#arr)"/>
<text class="lbl yes" x="350" y="155">Sí</text>
<rect x="160" y="172" width="360" height="50" rx="8" fill="#E6F1FB" stroke="#185FA5" stroke-width="0.5"/>
<text class="q" x="340" y="192" text-anchor="middle">¿El uso es estrictamente</text>
<text class="q" x="340" y="208" text-anchor="middle">personal y no profesional?</text>
<line x1="160" y1="197" x2="100" y2="197" stroke="#888780" stroke-width="1" marker-end="url(#arr)"/>
<text class="lbl yes" x="130" y="189">Sí</text>
<rect x="18" y="182" width="80" height="30" rx="6" fill="#F1EFE8" stroke="#B4B2A9" stroke-width="0.5"/>
<text class="r" x="58" y="201" text-anchor="middle">No aplica</text>
<line x1="340" y1="222" x2="340" y2="264" stroke="#888780" stroke-width="1" marker-end="url(#arr)"/>
<text class="lbl no" x="350" y="247">No</text>
<rect x="160" y="264" width="360" height="50" rx="8" fill="#E6F1FB" stroke="#185FA5" stroke-width="0.5"/>
<text class="q" x="340" y="284" text-anchor="middle">¿El sistema tiene una excepción</text>
<text class="q" x="340" y="300" text-anchor="middle">específica en el reglamento?</text>
<line x1="520" y1="289" x2="580" y2="289" stroke="#888780" stroke-width="1" marker-end="url(#arr)"/>
<text class="lbl yes" x="550" y="281">Sí</text>
<rect x="582" y="274" width="80" height="30" rx="6" fill="#FAEEDA" stroke="#BA7517" stroke-width="0.5"/>
<text class="r" x="622" y="287" text-anchor="middle">Verificar</text>
<text class="r" x="622" y="300" text-anchor="middle">excepción</text>
<line x1="340" y1="314" x2="340" y2="366" stroke="#888780" stroke-width="1" marker-end="url(#arr)"/>
<text class="lbl no" x="350" y="344">No</text>
<rect x="140" y="366" width="400" height="64" rx="12" fill="#1B2A4A" stroke="#E07A5F" stroke-width="1.5"/>
<text class="conclusion" x="340" y="392" text-anchor="middle">El artículo 4 te aplica</text>
<text class="concl-sub" x="340" y="414" text-anchor="middle">Debes garantizar la alfabetización en IA de tu personal</text>
<text class="note" x="340" y="460" text-anchor="middle">En la práctica, exceptuar a una empresa del artículo 4</text>
<text class="note" x="340" y="476" text-anchor="middle">es casi imposible en la economía actual</text>
</svg>

### Ejemplos de "responsable del despliegue" en España

Si tu empresa da licencias de ChatGPT, Claude, Copilot o Gemini a empleados; usa un chatbot con IA en su web; utiliza un ATS con filtrado automático de CVs; aplica IA en análisis financiero, predicción de ventas o evaluación de clientes; o tiene cualquier herramienta "AI-powered" que el personal use profesionalmente — **es responsable del despliegue**.

### El matiz "en nombre de"

El texto extiende la obligación a **quienes trabajen en nombre de la empresa con sistemas IA**: autónomos, becarios, consultores externos, proveedores subcontratados. Si tu asesoría externa redacta informes para ti usando IA, **tú eres responsable** de garantizar su alfabetización.

### Quién está exento

Uso estrictamente personal y no profesional. Sistemas amparados por excepciones específicas del reglamento (I+D no comercializada, seguridad nacional). En la práctica, exceptuar a una empresa del artículo 4 **es casi imposible** en la economía actual.

---

## <a id="nivel-suficiente"></a>3. Qué significa "nivel suficiente de alfabetización"

El reglamento no define un nivel numérico ni horas mínimas. Deja flexibilidad para que cada empresa adapte el nivel al contexto. Los criterios objetivos se interpretan a partir del propio texto, las directrices de la Oficina Europea de IA y los pronunciamientos de la AESIA.

El estándar mínimo defendible: una **acción formativa estructurada con evaluación y certificado**, adaptada al perfil del trabajador. Un PDF enviado por correo no es formación acreditable. Una charla de 15 minutos sin evaluación tampoco.

---

## <a id="bloques"></a>4. Los seis bloques temáticos obligatorios

Una formación conforme al artículo 4 debe cubrir, adaptados al perfil del alumno, estos seis bloques:

<table>
<thead><tr><th></th><th>Bloque</th><th>Contenido esencial</th></tr></thead>
<tbody>
<tr><td>🧠</td><td><strong>1. Conceptos fundamentales</strong></td><td>Qué es un sistema de IA, diferencia IA tradicional / generativa, qué es un LLM, alucinaciones, sesgos algorítmicos.</td></tr>
<tr><td>🔍</td><td><strong>2. Capacidades y limitaciones</strong></td><td>Qué puede y qué no puede hacer la herramienta. Reconocer cuándo la IA miente con confianza.</td></tr>
<tr><td>⚠️</td><td><strong>3. Riesgos del contexto laboral</strong></td><td>Fuga de datos confidenciales, sesgos en decisiones críticas, dependencia excesiva, responsabilidad por errores.</td></tr>
<tr><td>⚖️</td><td><strong>4. Obligaciones del AI Act</strong></td><td>Cuatro niveles de riesgo, sistemas prohibidos, qué cambia en agosto 2026, documentación exigible.</td></tr>
<tr><td>🛡️</td><td><strong>5. RGPD aplicado a IA</strong></td><td>Datos que nunca se incorporan sin anonimizar, consentimiento, derechos de los afectados, documentación del tratamiento.</td></tr>
<tr><td>👁️</td><td><strong>6. Supervisión humana</strong></td><td>Nunca copiar-pegar sin revisar, cuándo descartar la respuesta de la IA, cómo documentar la intervención humana.</td></tr>
</tbody>
</table>

---

## <a id="perfiles"></a>5. Perfiles profesionales y duración orientativa

El artículo 4 exige adaptación por perfil. Un curso idéntico para todos no cumple. Estos rangos son **propuestas de Ciberaula basadas en 28 años de experiencia en formación corporativa**, no cifras oficiales:

<table>
<thead><tr><th>Perfil</th><th>Quién</th><th>Contenido clave</th><th>Horas</th></tr></thead>
<tbody>
<tr><td><strong>A · Generalista</strong></td><td>Empleados con uso ocasional de IA</td><td>Bloques 1-3 + política interna</td><td>4-6 h</td></tr>
<tr><td><strong>B · Intensivo</strong></td><td>Marketing, ventas, atención al cliente, análisis</td><td>A + prompt engineering + supervisión de outputs</td><td>10-15 h</td></tr>
<tr><td><strong>C · Mandos</strong></td><td>Jefes de departamento, coordinadores</td><td>B + gobernanza + auditoría del equipo</td><td>13-19 h</td></tr>
<tr><td><strong>D · IT/Seguridad</strong></td><td>Sysadmin, CISO, DevOps, desarrollo</td><td>Seguridad IA, prompt injection, evaluación de proveedores</td><td>20-30 h</td></tr>
<tr><td><strong>E · Dirección</strong></td><td>CEO, comité ejecutivo, consejeros</td><td>Estrategia IA + responsabilidad jurídica + sanciones</td><td>3-5 h</td></tr>
<tr><td><strong>F · Cumplimiento</strong></td><td>DPO, asesoría jurídica, compliance</td><td>AI Act artículo por artículo + FRIA + RGPD-IA</td><td>25-40 h</td></tr>
</tbody>
</table>

El principio del reglamento es **proporcionalidad**: una hora no basta, 500 horas es desproporcionado.

---

## <a id="plan-formativo"></a>6. Plan formativo: pasos para cumplir

Un plan formativo conforme al artículo 4 no es "enviar un curso a todos". Es un documento estructurado que la empresa debe poder presentar ante una inspección.

1. **Inventario de perfiles** con exposición a IA (directa o indirecta).
2. **Asignación de perfil formativo** (A-F) a cada puesto.
3. **Selección del formato**: formación interna documentada o entidad formativa externa.
4. **Ejecución** con evaluación y certificado por participante.
5. **Archivo de documentación** permanente como evidencia de cumplimiento.
6. **Actualización cíclica**: al menos anual para perfiles de mayor exposición.

<blockquote class="callout-info">
<p><strong>Financiación.</strong> Esta formación es bonificable con el crédito FUNDAE de la empresa. La gestión operativa (comunicación de inicio, plazos, requisitos técnicos, porcentajes de bonificación) se detalla en nuestra <a href="https://github.com/Ciberaula/guia-formacion-bonificada-fundae">Guía completa de formación bonificada FUNDAE</a>.</p>
</blockquote>

---

## <a id="documentacion"></a>7. Documentación mínima para una inspección

Si llega una inspección, estos documentos deben estar organizados y accesibles:

1. **Plan formativo de alfabetización en IA** firmado por dirección, con fecha y versión.
2. **Inventario de sistemas de IA utilizados** y clasificación de riesgo.
3. **Asignación de perfiles formativos** por puesto o persona.
4. **Registros de formación**: nombre, fecha, duración, contenidos, tutor, evaluación, certificado.
5. **Política interna de uso de IA** firmada por cada empleado.
6. **Designación de responsable** del cumplimiento del artículo 4.
7. **Registro de incidentes** relacionados con IA, con gestión documentada.
8. **Plan de actualización** con calendario de reciclajes.

Sin estos documentos, una inspección puede concluir que la empresa "no ha adoptado medidas" en el sentido del artículo 4, incluso si el equipo está formado de facto. El cumplimiento **es demostrable o no lo es**.

---

## <a id="casos-practicos"></a>8. Casos prácticos ilustrativos

Escenarios construidos a partir de patrones de incumplimiento habituales en empresas españolas. No corresponden a clientes concretos.

<div class="caso-practico">
<h4>Caso 1 · Asesoría fiscal, 28 empleados</h4>
<p>La asesoría da acceso corporativo a ChatGPT Plus a toda la plantilla. Un cliente detecta que en su declaración aparecen datos de otro cliente: el asesor había pegado datos fiscales en ChatGPT.</p>
<p><strong>Incumplimiento:</strong> ausencia de formación documentada (art. 4) + transferencia no consentida de datos personales a tercero (RGPD).</p>
<p><strong>Resolución tipo:</strong> plan formativo urgente por perfiles, política interna firmada, contrato con proveedor IA actualizado a versión sin entrenamiento sobre datos. Implementación: 4-6 semanas.</p>
</div>

<div class="caso-practico">
<h4>Caso 2 · Empresa industrial, 180 empleados</h4>
<p>RRHH usa un ATS con IA para preseleccionar CVs. Un candidato rechazado ejerce su derecho a no ser objeto de decisiones individuales automatizadas (art. 22 RGPD). La empresa no puede justificar el rechazo.</p>
<p><strong>Incumplimiento:</strong> triple. (1) Art. 4 — personal RRHH sin formación sobre el sistema. (2) Supervisión humana ausente — alto riesgo desde agosto 2026. (3) Art. 22 RGPD — falta de información al candidato.</p>
<p><strong>Resolución tipo:</strong> parada del ATS, formación específica para RRHH, reconfiguración del proceso con supervisión humana genuina, actualización de cláusulas informativas.</p>
</div>

<div class="caso-practico">
<h4>Caso 3 · Consultoría tecnológica, 8 empleados</h4>
<p>El CEO piensa que "somos técnicos, no necesitamos formación". Una inspección de la AEPD pregunta cómo se cumple el artículo 4 dado que usan Copilot, Claude API y ChatGPT Team. No hay formación documentada.</p>
<p><strong>Incumplimiento:</strong> el artículo 4 no reconoce la "alfabetización implícita por ser técnico". La obligación es demostrable con documentación.</p>
<p><strong>Resolución tipo:</strong> formación con módulo técnico avanzado (seguridad IA, prompt injection, auditoría de código generado), certificados individuales, política interna.</p>
</div>

---

## <a id="errores"></a>9. Errores frecuentes

<table>
<thead><tr><th></th><th>Error</th><th>Por qué es un problema</th></tr></thead>
<tbody>
<tr><td>❌</td><td><strong>Formar solo a IT</strong></td><td>El art. 4 cubre a todo el personal que use IA, no solo al técnico.</td></tr>
<tr><td>❌</td><td><strong>Un único curso para todos</strong></td><td>El reglamento exige adaptación al perfil. Sin personalización no hay cumplimiento.</td></tr>
<tr><td>❌</td><td><strong>Webinar de 1 hora sin evaluación</strong></td><td>No constituye formación acreditable. El mínimo defendible es acción formativa estructurada con certificado.</td></tr>
<tr><td>❌</td><td><strong>No documentar la formación interna</strong></td><td>Sin documentación, es como si no hubiera existido ante una inspección.</td></tr>
<tr><td>❌</td><td><strong>Olvidar a externos</strong></td><td>Autónomos, consultores y proveedores que usen IA "en nombre de" la empresa están cubiertos.</td></tr>
<tr><td>❌</td><td><strong>No actualizar nunca</strong></td><td>Una formación de 2024 está desactualizada en 2026. Reciclaje bianual mínimo.</td></tr>
<tr><td>❌</td><td><strong>No firmar política de uso</strong></td><td>Formación sin política interna firmada no cierra el círculo.</td></tr>
<tr><td>❌</td><td><strong>Confiar solo en el proveedor</strong></td><td>Que OpenAI cumpla como proveedor no te exime como responsable del despliegue.</td></tr>
</tbody>
</table>

---

## <a id="faq"></a>10. Preguntas frecuentes

### ¿Cuándo empezaron las obligaciones?

<blockquote class="callout-warning">
<p>El artículo 4 está <strong>en vigor desde el 2 de febrero de 2025</strong>. Las empresas sin medidas están en <strong>incumplimiento ya hoy</strong>.</p>
</blockquote>

### ¿Qué sanciones hay?

El artículo 99 del AI Act remite a los Estados miembros la fijación del régimen sancionador para infracciones como el incumplimiento del artículo 4. La cuantía concreta en España dependerá del desarrollo normativo nacional. Para PYMES, el artículo 99.6 establece que la multa será la menor entre el porcentaje y el importe absoluto.

### ¿Vale una formación anterior a febrero 2025?

Si documentó un nivel suficiente para el perfil correspondiente, sí. Pero prácticamente ninguna formación anterior cubre todos los bloques que el reglamento exige.

### ¿Los cursos gratuitos de Google, Microsoft y OpenAI cuentan?

Son apoyo, pero no suelen bastar solos: generalmente no tienen evaluación formal, son específicos de una herramienta y no cubren el marco regulatorio completo.

### ¿Si cambio de herramienta IA necesito nueva formación?

Sí. El artículo 4 exige alfabetización adaptada al sistema que se usa. Cada transición requiere actualización formativa.

### ¿Puede mi empresa impartir la formación internamente?

Sí. Pero requiere docente con nivel técnico suficiente, documentación exhaustiva y evaluación del alumno.

### ¿Cómo demuestro que la formación funcionó?

Evaluaciones de aprendizaje (tests) y, más allá, evaluaciones de transferencia al puesto (encuestas a los 3-6 meses, indicadores de uso responsable). No es obligatorio medir transferencia, pero refuerza enormemente la defensa ante inspección.

---

<div class="cta-formacion">
<h3>¿Necesitas cumplir el artículo 4?</h3>
<p>Ciberaula diseña planes formativos por perfiles para cumplir el AI Act, con documentación auditable. La formación es bonificable con FUNDAE — consulta nuestra <a href="https://github.com/Ciberaula/guia-formacion-bonificada-fundae">guía de formación bonificada</a> para los detalles operativos.</p>
<a href="https://www.ciberaula.com/cursos-bonificados/" class="cta-boton">Ver cursos →</a>
</div>

## Recursos relacionados

- 📘 [El AI Act explicado para empresas españolas](ai-act-guia-empresas-espanolas.md)
- 📗 [AESIA y AEPD: competencias en IA](aesia-aepd-competencias.md)
- ✅ [Checklist de cumplimiento AI Act](checklist-cumplimiento-ai-act.md)
- 📋 [Plantilla de política de uso de IA](plantilla-politica-uso-ia.md)
- 🎓 [Guía completa de formación bonificada FUNDAE](https://github.com/Ciberaula/guia-formacion-bonificada-fundae)

---

*Publicado bajo licencia [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.es). Libre uso con atribución a Ciberaula.*

*© 2026 Ana María González · Directora de Ciberaula · Formación online para empresas desde 1997.*
