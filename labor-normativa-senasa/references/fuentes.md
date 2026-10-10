# Fuentes usadas para construir la skill

La skill fue construida en octubre de 2026 en el Programa de Sanidad Porcina (DNSA – SENASA) y generalizada para
cualquier Programa o área de la DNSA, a partir de los
documentos siguientes. Los PDF no están incluidos en la skill: pedirlos a Alejandro Pérez (Programa de Sanidad
Porcina) si se necesitan para revisar o ampliar el contenido.

**Descarga del CNS (PDF, 5,4 MB) y de la última versión de la skill:**
https://drive.google.com/drive/folders/1wo-0AfhHfJEEUvt6NHH9lnnKQ20og6E2

| # | Documento (PDF) | Qué se tomó | Sección de la skill |
|---|---|---|---|
| 1 | **Manual de Técnicas Legislativas – Pautas para la elaboración de disposiciones normativas del SENASA** (UBA, 26/03/2009; 47 pág.) | Estructura del acto, título, epígrafes, anexos, estilo, léxico, gramática, conjunciones, citas, referencias, entrada en vigor, modificación, derogación, abrogación, reviviscencia | 3 a 7 |
| 2 | **Resolución SENASA N° 401/2010** (75 pág., escaneada) | Aprueba el Manual (Anexo II) y el Índice Temático del Digesto (Anexo I) en reemplazo del índice del CNS; fórmula de competencia (art. 8°, inc. h, Decreto 1585/96) | 3.2, 9 |
| 3 | **Curso "La labor normativa del SENASA" – Módulo 1: Análisis de la Ley 27.233** (DAJ – Coordinación de Legislación Sanitaria; 24 diapositivas) | Marco de la Ley 27.233: responsabilidad primaria, régimen de infracciones (Cap. V), red institucional, entes sanitarios | 3.2, 3.4 |
| 4 | **Curso – Módulo 3: El Digesto Normativo del SENASA** (Programa de Reordenamiento Normativo, Res. 466/08; 26 diapositivas) | Estructura de 4 libros, bases del Digesto, índices por parte (Res. 800/10, 31/11, 738/11, 9013/10, 325/11, 121/12, 424/12, 234/12), uso combinado índice + Digesto, ubicación propuesta por el área iniciadora | 9 |
| 5 | **Curso – Módulo 4: Pautas para la consolidación normativa** (texto, 9 pág.) | Seis etapas de la consolidación, comentarios de origen, control de integridad, circulares a resolución, Libro IV aparte, anexos solo para tablas y formularios | 8 |
| 6 | **Curso – Módulo 4: Pautas para la redacción de proyectos normativos consolidados** (diapositivas, 9 pág.) | Resumen de las etapas de consolidación | 8 |
| 7 | **Resolución SENASA N° RESOL-2025-810-APN-PRES#SENASA** (Plan Nacional de Control y Erradicación de la Enfermedad de Aujeszky; BO 24/10/2025) | Modelo de práctica vigente: VISTO con números GDE, considerandos tipo, fórmula de competencia (art. 8°, incs. e y f, Decreto 1585/96), "Inciso a) / Apartado I) / Subapartado i)", títulos de sección sin numerar, epígrafes, anexos con IF, artículos de facultades, abrogación, infracciones, vigencia y forma | 2, 3 |
| 8 | **Resolución SENASA N° RESOL-2019-1649-APN-PRES#SENASA** (procedimiento de proyectos normativos y de consulta) | Antecedente histórico. **Abrogada** por la Res. 720/2022 | 10 (nota) |
| 9 | **Resolución SENASA N° 720/2022** (texto actualizado Infoleg al 16/01/2025; Anexo II sustituido por Res. SENASA 756/2024, vigente desde 1/8/2024) | Programa de Calidad Normativa; procedimiento: FONSE, códigos de trámite, PRESO/PDISP, ANEX, IFGRA, IFTEC (puntos 5.1 a 5.8), visto bueno de áreas, consultas, cuadro de contribuciones, dictamen DAJ, formalización; actualización del Digesto | 10, 11 |
| 10 | **Digesto SENASA – Navegación jerárquica** (captura del sitio, 26 pág., y extracción completa del 9/10/2026 vía Firecrawl) | Árbol completo del índice temático (634 nodos), URLs de listado, búsqueda y ficha | 9.2, 9.3 y `references/digesto-indice.md` |
| 11 | **CNS – Código de Normas SENASA** (1999; 1740 pág.) | Sistema de codificación, índice general de normas con páginas, índice de palabras clave | `references/cns-indice.md` |

## Convenciones de trabajo (no surgen de los PDF)

Las convenciones de la sección 2 (autor de comentarios "Comentarios Senasa", nombres de archivo, versiones v1.0 /
v1.x, artículos nuevos sin numerar hasta consolidar, tratamiento de "y/o", marcado de futuros en revisiones, citas
sin número de Boletín Oficial, numeración 1° a 9° y cardinal desde 10, títulos de sección sin numerar) son
decisiones del Equipo de Porcinos y se mantienen como valores por defecto. Cada programa puede cambiarlas.

## Limitaciones conocidas

- El Digesto (digesto.senasa.gob.ar) no responde a la consulta web común por un problema de certificado SSL; se accede
  con el conector Firecrawl (cada página consume un crédito) o con un navegador conectado.
- La extracción de texto del CNS es a dos columnas: verificar cualquier transcripción contra la página del PDF.
- La fórmula de competencia para disposiciones de la DNSA no figura en los documentos fuente: confirmar con la DAJ.
- Verificar en Infoleg si la Res. 720/2022 tuvo modificaciones posteriores a 2024.
