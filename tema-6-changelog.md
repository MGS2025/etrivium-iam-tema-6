# Tema 6 — Changelog

> **Título oficial**: Ley 39/2015 (LPACAP): derechos de los ciudadanos y registros. Ley 19/2013 (LTBG): derecho de acceso a la información pública.

---

## v1.4 — 2026-10-06 — Revisión de diagramas

**Motivo**: barrido de los diagramas de los 40 temas tras la revisión jurídica y de normas.

### Cambios

- Revisión visual de todos los diagramas, captura a captura (la medición automática no detecta contraste, flechas mal dirigidas ni textos pegados al borde): corregidos textos que se salían de su caja o del lienzo, cajas que se tocaban, flechas que no llegaban a su destino y textos con poco contraste. Sin cambios de contenido.

---

## v1.3 — 2026-10-01 — Revisión jurídica

**Estado**: revisión jurídica aplicada. Texto contrastado con las versiones consolidadas del BOE (LPACAP, LRJSP, LTBG) y con la Ordenanza de Transparencia de la Ciudad de Madrid (BOCM nº 196 de 17/08/2016; sin modificaciones según la edición del BOE de 24/06/2026).

### Cambios de la revisión

- **§15**: se elimina del ejemplo del Ayuntamiento la frase sobre el órgano que resuelve la reclamación en Madrid («dato a verificar») y su referencia.
- **Fuentes**: se elimina la nota sobre el origen del material y la tabla de material de partida; la fila del temario oficial (BOAM 10.032) pasa a las fuentes primarias.

### Correcciones de contenido (contra el texto consolidado)

- **Art. 53.1 LPACAP**: el catálogo tiene nueve letras (a-i); se elimina una letra inexistente («utilizar las lenguas oficiales») y se reordenan las demás. Art. 53.2 completado.
- **Art. 9.2 LPACAP**: se sustituye «clave concertada» por la redacción vigente de la letra c) (tras el RDL 14/2019 y la Ley 11/2022). La exigencia de firma se cita en el **art. 11.2** (no en el art. 10), con «declaraciones responsables o comunicaciones».
- **Art. 3 LPACAP**: la novedad de la exposición de motivos es la capacidad de obrar de grupos de afectados y entidades sin personalidad, no la de los menores.
- **DF 7.ª LPACAP**: se añade que registros, apoderamientos, punto de acceso general y archivo único producen efectos desde el 2 de abril de 2021; derogación de la Ley 30/1992 y la Ley 11/2007 citada en la DD única.
- Literalidad corregida en arts. 1.1, 4.1, 13, 16.1, 16.3, 16.4, 17, 30.1, 30.4 y 31.2 LPACAP, y arts. 1, 5.4, 9, 13, 14.1, 15, 17.3, 18.1, 23.1 y 24 LTBG.
- **Art. 24.6 y DA 4.ª LTBG**: el convenio sirve para atribuir la reclamación al CTBG, no para crear un órgano autonómico.
- **Ordenanza de Madrid**: principios del art. 4 tal como los enumera la norma; ámbito de los arts. 2 y 3; recursos y reclamaciones del art. 26; Registro de lobbies según los arts. 34-39.

### Reglas generales

- Títulos de las cajas: **Dato clave**, **Cita normativa**, **Ejemplo de aplicación en el Ayto** y **Relación con otros temas**; la leyenda ya no promete que algo aparezca en el examen.
- Se eliminan las valoraciones fuera de las cajas y las promesas sobre el examen («de los más preguntados», «muy preguntada»…).
- Citas de artículos: «artículo» completo cuando forma parte de la oración.
- **Test**: las 160 preguntas se reescriben a partir del texto literal del precepto citado, con distractores que son variaciones leves; respuestas repartidas 54/53/53 entre a, b y c.
- Casos prácticos, índice, diagramas (D2, D5, D6, D8, D9, D10, D11, D12) y validación ajustados a lo anterior.

---

## v1.2 — 2026-09-06 — Ficha de extensión y tiempo de estudio

**Estado**: sin cambios de contenido. Solo se añade información sobre el propio tema.

**Motivo**: petición del IAM (Jesús Cuadrado, 02-09-2026) al validar el Tema 30. Acepta la extensión de los temas «compuestos» a condición de que se informe de «su extensión en palabras y tiempo estimado de estudio». Al revisarlo se vio que ese dato solo aparecía en 16 de los 40 temas, y que faltaba justo en los más largos.

### Alcance

- Ficha bajo la cabecera del tema, y al final de la pestaña Índice donde esa pestaña existe:
  - **Extensión**: ~5.300 palabras · 12 diagramas · 160 preguntas de test
  - **Tiempo estimado de estudio**: 11-13 horas (primera vuelta completa, sin contar repasos)
- La cifra de palabras de la tabla de entregables se sincroniza con la ficha, para que el tema no muestre dos recuentos distintos.
- Las horas salen de una fórmula común a los 40 temas, para que sean comparables entre sí: contenido a 1.500 palabras/hora (ritmo de estudio activo), diagramas a una hora por cada cinco y test a dos minutos por pregunta. Se publica como intervalo de dos horas.
- Generado con `_tools-qa/ficha_estudio.py`, idempotente y reejecutable tras cualquier regeneración con `build_tNN.py`.

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
