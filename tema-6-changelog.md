# Tema 6 — Changelog

> **Título oficial**: Ley 39/2015 (LPACAP): derechos de los ciudadanos y registros. Ley 19/2013 (LTBG): derecho de acceso a la información pública.

---

## v1.1 — 2026-06-25 — Correcciones de María (IAM)

**Estado**: Revisión de María aplicada. Pendiente de validación final.

### Cambios

- **Nota de conexión en el art. 13 (§3)**: se enlazan las letras d) (acceso → LTBG y art. 17), g) (identificación/firma → §7) y h) (protección de datos → límite del art. 15 LTBG) con los epígrafes donde se desarrollan, y con el nuevo §4 (art. 53). Evita estudiar esos epígrafes como bloques desconectados.
- **Nuevo §4 — Derechos del interesado en el procedimiento (art. 53)**: faltaba. Catálogo del art. 53.1 (estado de tramitación, no aportar documentos ya en poder de la AP, alegar, asesor…) y derechos del presunto responsable en el procedimiento sancionador (art. 53.2, presunción de no responsabilidad). El enunciado oficial pide "derechos de los ciudadanos… y Registros", y el art. 53 es la concreción de esos derechos una vez iniciado el procedimiento.
- **Nuevo §9 — Los archivos administrativos. El Archivo Electrónico Único (art. 17)**: faltaba. El enunciado habla de "Registros" en plural; se distingue el **registro** de entrada/salida (art. 16) del **archivo** (art. 17), que conserva los documentos de procedimientos finalizados garantizando autenticidad, integridad y consulta en el tiempo. Especialmente relevante para el perfil TIC (infraestructura de preservación de expedientes electrónicos).
- **Desarrollo del Registro de grupos de interés (lobbies)** en §16.1: quién debe inscribirse, carácter **obligatorio**, carácter **público** y qué información se publica (identidad, intereses representados, reuniones con cargos / agendas).
- **+10 preguntas de test** (151-160) sobre el contenido nuevo (art. 53, art. 17 y lobbies). Total: **160 preguntas**.
- **Renumeración** de secciones (15 → 17) y actualización de índice, diagramas (referencias de sección), validación y esquema-resumen en consecuencia.

---

## v1.0 — 2026-06-25 — Generación inicial completa

**Estado**: Pendiente de validación por María / Ana (IAM) y de confirmación de datos volátiles por Jesús (eTrivium).

### Alcance y decisiones

- **Fuentes nucleares**: **LPACAP (Ley 39/2015)** y **LTBG (Ley 19/2013)**, versión consolidada del BOE, más la **Ordenanza de Transparencia de la Ciudad de Madrid** (Acuerdo del Pleno de 27-jul-2016, BOAM 17/08/2016).
- **Sin PDF resumen del cliente** para este tema: el contenido se ha generado del **texto oficial** a partir del índice oficial `TEMA_06.docx` (tratamiento de fuentes de los temas administrativos/legales sin PDF, como T2-T4).
- **Alcance de la LPACAP**: derechos (art. 13), interesados (arts. 3-12), registros (art. 16) según el enunciado oficial, **ampliado** por conexión con la obligación de relación electrónica (art. 14) y el cómputo de plazos (arts. 30-31).
- **Alcance de la LTBG**: derecho de acceso (arts. 12-24) según el enunciado, **ampliado** con publicidad activa (arts. 5-11) y el Consejo de Transparencia y Buen Gobierno (arts. 33-40) por ser inseparables.
- **Verificación de la Ordenanza de Madrid (dato volátil)**: confirmada **vigente** (texto consolidado en transparencia.madrid.es) antes de redactar la sección §14.
- **Diagramas con CSS aislado desde el origen**: el builder `build_t6.py` incorpora `scope_svg` (fix descubierto en el Tema 5 v1.2), de modo que ningún texto se desborda de su caja al convivir los 12 SVG en el `index.html`.
- **Formato de referencia**: Tema 5 (150 preguntas + 6 casos + 12 diagramas + 8 pestañas con Índice).

### Entregables generados

| Fichero | Contenido |
|---|---|
| `tema-6-indice.md` | Índice de 15 secciones + tablas de datos clave |
| `tema-6-fuentes.md` | Registro Tier 1/2/3 + datos volátiles a confirmar por Jesús |
| `tema-6-contenido.md` | Contenido teórico (15 secciones, callouts) |
| `tema-6-diagramas.md` | 12 diagramas SVG accesibles (CSS aislado) |
| `tema-6-test.md` | 150 preguntas tipo examen |
| `tema-6-caso-practico.md` | 6 casos prácticos (IAM / Ayto Madrid), 10 pts c/u |
| `tema-6-validacion.md` | Checklist de validación |
| `index.html` | Web autosuficiente, pestañas, motor test 1/3 |

### QA aplicado

- Contenido contrastado con el texto oficial de la LPACAP, la LTBG y la Ordenanza de Madrid.
- Datos numéricos sensibles verificados (entrada en vigor 2016, plazos de acceso 1 mes, silencio negativo, reclamación CTBG 1/3 meses, sujetos del art. 14.2, cómputo de plazos).
- **Diagramas verificados con CSS aislado** (`scope_svg`) y medición `getBBox` sobre el `index.html` real.
- Balanceo automático A/B/C de las respuestas del test (permutación determinista).
- Refs cruzadas verificadas vs BOAM 10.032 (T1 Constitución, T2 Administración Local, T5 empleado público, T7 fases del procedimiento, T32 firma digital).

### Pendiente

- Validación de contenido por María / Ana (IAM).
- Confirmación de datos volátiles por Jesús (vigencia de la Ordenanza, órgano de reclamación municipal, umbrales económicos).
