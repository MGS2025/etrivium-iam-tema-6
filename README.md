# ETRIVIUM IAM — Tema 6

**Ley 39/2015, de 1 de octubre, del Procedimiento Administrativo Común de las Administraciones Públicas: derechos de los ciudadanos en sus relaciones con las Administraciones Públicas y registros. Ley 19/2013, de 9 de diciembre, de transparencia, acceso a la información pública y buen gobierno: derecho de acceso a la información pública. Ordenanza de Transparencia de la Ciudad de Madrid (27 de julio de 2016).**

Material de estudio para la oposición **C1 — Técnico Auxiliar TIC del Ayuntamiento de Madrid** (temario BOAM 10.032).

## Contenido

- **`index.html`** — web autosuficiente (offline) con 8 pestañas: Inicio, Índice, Contenido, Diagramas, Test, Casos, Validación y Fuentes. Motor de test con corrección automática y penalización 1/3.
- **`tema-6-indice.md`** — índice y datos clave.
- **`tema-6-contenido.md`** — contenido teórico (15 secciones).
- **`tema-6-diagramas.md`** — 12 diagramas SVG (CSS aislado, sin desbordes).
- **`tema-6-test.md`** — 150 preguntas tipo examen.
- **`tema-6-caso-practico.md`** — 6 casos prácticos (IAM).
- **`tema-6-fuentes.md`** — registro normativo y datos volátiles a confirmar.
- **`tema-6-validacion.md`** — checklist de validación (María / Ana).
- **`tema-6-changelog.md`** — historial de versiones.
- **`build_t6.py`** — generador del `index.html` desde los `.md` (conversor propio + `scope_svg`).

## Estado

**v1.0 — Generación inicial.** Pendiente de validación por María / Ana (IAM) y de confirmación de datos volátiles por Jesús (eTrivium): vigencia de la Ordenanza de Madrid, órgano de reclamación municipal y umbrales económicos de publicidad activa.

## QA aplicado

- 150 preguntas con 3 opciones únicas y respuesta válida; distribución A/B/C equilibrada (51/51/48).
- 12 diagramas SVG con CSS aislado (`scope_svg`); **0 textos fuera de caja** (verificado por `getBBox` sobre el render real).
- Ortografía es_ES (hunspell) sin typos reales.
- Referencias cruzadas verificadas contra el temario oficial BOAM 10.032.

## Fuentes

Ley 39/2015 (BOE), Ley 40/2015 (BOE), Ley 19/2013 (BOE) y Ordenanza de Transparencia de la Ciudad de Madrid (BOAM nº 7724, 17/08/2016), todas en versión consolidada.
