# Tema 6 — Checklist de Validación

> **Título oficial**: Ley 39/2015 (LPACAP): derechos, interesados y registros. Ley 19/2013 (LTBG): derecho de acceso a la información pública.
> **Versión**: 1.0 — Generación inicial
> **Fecha**: 2026-06-25
> **Revisoras**: María + Ana (IAM) · **Datos volátiles**: Jesús (eTrivium)

---

## Cómo usar este checklist

- **OK** → el criterio se cumple sin cambios.
- **REVISAR** → necesita ajuste o aclaración (indicar qué).
- **NO** → no se cumple o es incorrecto. Justificar.

---

## 1. Fuentes y trazabilidad

- [ ] Las fuentes nucleares son la **LPACAP (Ley 39/2015)** y la **LTBG (Ley 19/2013)** en versión consolidada, más la **Ordenanza de Transparencia de Madrid (2016)**.
- [ ] No existe PDF resumen del cliente para este tema; el contenido se ha generado del **texto oficial** a partir del índice `TEMA_06.docx`.
- [ ] Cada afirmación que reproduce el articulado está referenciada con `[LPACAP, art. X]`, `[LTBG, art. X]` u `[ORD-MAD, art. X]`.
- [ ] Cada pregunta del banco y de los casos puede reconducirse a un artículo concreto.

## 2. Estructura del contenido

- [ ] El `tema-6-indice.md` refleja fielmente la estructura de `tema-6-contenido.md`.
- [ ] Las secciones cubren: LPACAP (objeto y relación con la 40/2015), derechos (art. 13), ámbito digital, interesados (arts. 3-6), identificación y firma (arts. 9-12), registros (art. 16), relación electrónica (art. 14) y plazos (arts. 30-31); LTBG (objeto y principios), publicidad activa (arts. 5-11), derecho de acceso (arts. 12-24), límites e inadmisión, CTBG; y la Ordenanza de Madrid.
- [ ] Los conceptos memorizables aparecen como `[DATO CLAVE EXAMEN]`.
- [ ] Las reproducciones del articulado aparecen como `[CITA NORMATIVA]`.
- [ ] Los ejemplos del Ayto de Madrid / IAM están marcados como `[EJEMPLO AYTO MADRID]`.
- [ ] Los enlaces a otros temas se marcan como `[REFERENCIA CRUZADA]`.

## 3. Rigor jurídico (datos sensibles)

- [ ] LPACAP en vigor el **2 de octubre de 2016**; pareja de la **Ley 40/2015** [DF 7.ª].
- [ ] Catálogo del **art. 13** correcto (a-i), distinguido de los derechos del **interesado** (art. 53).
- [ ] Capacidad de obrar: personas físicas/jurídicas + **menores** (sin asistencia) + **entidades sin personalidad** cuando la ley lo declare [art. 3].
- [ ] Representación: se **presume** para mero trámite; se **acredita** para solicitudes, recursos, desistimiento y renuncia [art. 5.3].
- [ ] **Identificación ≠ firma**: identificar (art. 9) acredita quién; firmar (art. 10) manifiesta voluntad y solo se exige para ciertos actos.
- [ ] **Registro Electrónico General**: uno por Administración, interoperable, 24/7 [art. 16].
- [ ] **Cinco** sujetos obligados a relación electrónica [art. 14.2].
- [ ] Cómputo de plazos: **sábados inhábiles**; días al día siguiente; meses **de fecha a fecha** [arts. 30-31].
- [ ] LTBG = **publicidad activa + acceso + buen gobierno**.
- [ ] Derecho de acceso: **todas las personas**, sin motivar; resolución **1 mes** (ampliable a 2); silencio **negativo**; terceros **15 días** [arts. 17-20].
- [ ] Límites **justificados y proporcionados** [art. 14.2]; causas de **inadmisión** tasadas [art. 18].
- [ ] **Reclamación ante el CTBG**: potestativa y previa; **1 mes** para interponer; CTBG resuelve en **3 meses** (silencio negativo) [art. 24].
- [ ] Ordenanza de Madrid: **Acuerdo del Pleno de 27-jul-2016** (BOAM 17/08/2016); registro de **lobbies**; publicidad activa reforzada.

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-6-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo.
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] **El CSS de cada SVG está aislado (`scope_svg`)**: ningún texto se sale de su caja (verificado por `getBBox` sobre el `index.html` real, los 12 SVG juntos).
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.

## 5. Banco de 150 preguntas

- [ ] Las 150 preguntas tienen 3 opciones y una única respuesta correcta verificable.
- [ ] La distribución A/B/C está equilibrada (~50/50/50) tras el balanceo automático del builder.
- [ ] No hay preguntas ambiguas.
- [ ] Cada respuesta cita su referencia normativa.

## 6. Casos prácticos

- [ ] Los 6 casos mantienen escenario del Ayto de Madrid / IAM.
- [ ] Las cuestiones de cada caso suman 10 puntos.
- [ ] Cada caso tiene solución orientativa y criterios de evaluación.

## 7. Nivel y adecuación al C1

- [ ] Nivel de profundidad adecuado para C1.
- [ ] Se priorizan los datos numéricos memorísticos (plazos, silencio, sujetos obligados).

## 8. Entregables HTML

- [ ] `index.html` autosuficiente (offline), con pestañas y motor de test con penalización 1/3.
- [ ] Imprimible a PDF.
- [ ] Branding Ayuntamiento de Madrid (#0055a0).

## 9. Consistencia inter-temas

- [ ] Referencia cruzada al **Tema 1** (art. 105.b CE — acceso a archivos y registros) coherente.
- [ ] Referencia al **Tema 5** (empleado público obligado a relación electrónica, art. 14.2.e) coherente.
- [ ] Referencia al **Tema 7** (fases del procedimiento) coherente.
- [ ] Referencia al **Tema 32** (firma digital y criptografía, soporte de la firma electrónica) coherente.

---

## Observaciones generales

### Decisiones conscientes que conviene confirmar

1. **Alcance del epígrafe LPACAP**: el enunciado oficial acota derechos (art. 13), interesados (arts. 3-12) y registros (arts. 16-17). Se han añadido, por conexión directa, la **obligación de relación electrónica** (art. 14) y el **cómputo de plazos** (arts. 30-31), imprescindibles para el registro. → Confirmar que el alcance es el deseado.
2. **Profundidad de la LTBG**: aunque el enunciado acota el **derecho de acceso**, se desarrolla también la **publicidad activa** (arts. 5-11) y el **CTBG** por ser inseparables. → Confirmar.
3. **150 preguntas + 6 casos + 12 diagramas + 8 pestañas (con pestaña Índice)**, en paridad con el Tema 5.
4. **Balanceo automático A/B/C** mediante permutación determinista en `build_t6.py`.
5. **Diagramas con CSS aislado** (`scope_svg`) desde el origen, incorporando el fix descubierto en el Tema 5.

### Puntos a vigilar (datos volátiles — validación de Jesús)

- **Vigencia y versión consolidada de la Ordenanza de Transparencia de Madrid (2016)**: confirmada vigente, pero reverificar modificaciones puntuales.
- **Órgano que resuelve la reclamación de acceso en el ámbito municipal madrileño** (CTBG vs órgano autonómico por convenio).
- **Umbrales económicos de publicidad activa** dependientes de la legislación de contratos vigente.

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
