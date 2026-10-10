---
name: labor-normativa-senasa
description: Redacta, modifica, abroga y consolida proyectos normativos del SENASA (resoluciones y disposiciones) para cualquier Programa o área de la Dirección Nacional de Sanidad Animal (bovinos, porcinos, aves, equinos, abejas, rumiantes menores, acuicultura, bienestar animal, epidemiología, registros, movimientos, cuarentena), aplicando el Manual de Técnicas Legislativas (Res. 401/2010) y la práctica vigente; busca normativa relacionada en el Digesto SENASA (vía Firecrawl), Infoleg, Boletín Oficial y CNS, y arma el Informe Técnico (IFTEC) y los antecedentes según la Res. 720/2022. Usarla siempre que el usuario trabaje en un proyecto de resolución o disposición, una modificación o texto ordenado, una revisión de borrador normativo o un informe técnico del SENASA, aunque no la nombre.
---

# Labor normativa SENASA – Sanidad Animal

Skill para los Programas Sanitarios y áreas de la Dirección Nacional de Sanidad Animal (DNSA) del SENASA: producir y
revisar proyectos normativos de alcance general (luchas sanitarias de cualquier especie, bienestar animal,
bioseguridad, registros y habilitaciones, identificación y movimientos, epidemiología, cuarentena e intercambios).

Fuentes que sintetiza esta skill:
- **Manual de Técnicas Legislativas – Pautas para la elaboración de disposiciones normativas del SENASA**
  (UBA, 26/03/2009), aprobado como Anexo II de la Res. SENASA N° 401/2010 ("el Manual").
- **Curso "La labor normativa del SENASA"** (Dirección de Asuntos Jurídicos – Coordinación de Legislación Sanitaria):
  Módulo 1 (Ley 27.233), Módulo 3 (Digesto), Módulo 4 (consolidación normativa).
- **Res. SENASA N° 720/2022** (Programa de Calidad Normativa; Anexo II sustituido por Res. SENASA N° 756/2024,
  vigente desde el 1/8/2024): procedimiento de elaboración de proyectos normativos, Informe Técnico y consultas.
  Abrogó la Res. SENASA N° 1649/2019 (usar 1649/19 solo como antecedente histórico).
- **Res. SENASA N° RESOL-2025-810-APN-PRES#SENASA** (Plan Nacional de Aujeszky): se usa como modelo de la práctica de
  redacción vigente de la DNSA; sus fórmulas sirven para cualquier especie o tema.
- Convenciones de trabajo por defecto (sección 2), que cada programa puede ajustar.

Archivos de referencia (si la skill se instaló con su carpeta `references/`, o si están en el conocimiento del
Proyecto o adjuntos al chat), leerlos cuando la tarea lo requiera:
- `references/digesto-indice.md`: árbol completo del índice temático del Digesto (títulos exactos de todas las ramas).
- `references/cns-indice.md`: codificación del CNS, índice general de normas con página impresa y página del PDF, e
  índice de palabras clave.
- `references/fuentes.md`: documentos usados para construir la skill.
Si no están disponibles, la skill funciona igual: los títulos de las ramas se obtienen del propio Digesto (sección 9.2).

## 0. Identificar el programa y el tema

Antes de buscar o redactar, determinar a partir del material del usuario (y confirmarlo en la propuesta inicial):
- **Programa o área** de la DNSA que propicia la norma y especie(s) o tema(s) alcanzados.
- **Rango del acto**: resolución de la Presidencia del SENASA o disposición de la DNSA (sección 2).
- **Ramas del Digesto** que le corresponden (sección 9.3) y, si existen, el plan o programa nacional vigente del tema.
- **Comisiones o ámbitos consultivos** del tema y si sus conclusiones son vinculantes.
- **Convenciones del equipo** si difieren de las de la sección 2.

Los ejemplos de esta skill vienen mayormente de la Res. 810/25 (Aujeszky) porque es la norma modelo de la práctica
vigente; adaptarlos a la especie y al tema del caso, no copiarlos.

---

## 1. Regla de trabajo: proponer antes de escribir

1. Leer todo lo que el usuario ingresó (proyecto, normas, comentarios, actas, borradores).
2. Identificar el **caso**: (A) norma nueva, (B) modificación, (C) abrogación, (D) consolidación / texto ordenado,
   (E) revisión de un borrador ajeno, (F) Informe Técnico / antecedentes.
3. Presentar **antes de redactar**: diagnóstico, normas relacionadas halladas y su tratamiento, estructura propuesta,
   decisiones a confirmar. Esperar la confirmación del usuario ("A escribir!" o equivalente).
4. Recién entonces redactar y entregar.
5. Respuestas técnicas, precisas, prácticas y directas.

---

## 2. Convenciones por defecto (prevalecen sobre el Manual; cada equipo puede ajustarlas)

| Tema | Regla |
|---|---|
| Numeración de artículos | Ordinales del 1° al 9° (`ARTÍCULO 1°.-` … `ARTÍCULO 9°.-`); cardinales desde el 10 (`ARTÍCULO 10.-`), como dice el Manual. |
| Artículos nuevos en borradores | Se agregan **sin número** (`ARTÍCULO XX.-`) hasta consolidar la versión; recién al consolidar se numera. |
| Subdivisiones | `Inciso a)` → `Apartado I)` → `Subapartado i)`, escribiendo la palabra (práctica de la Res. 810/25). |
| Divisiones superiores al artículo | Títulos de sección **en mayúsculas, sin numerar** (p. ej. `CLASIFICACIÓN SANITARIA`, `VACUNACIÓN`, `MOVIMIENTOS`, `PRESCRIPCIONES FINALES`). No usar "Capítulo I". |
| Citas de normas | Sin número ni fecha de Boletín Oficial (práctica vigente). Ver sección 5. |
| Tiempo verbal | Redactar en presente. En **revisiones** de textos existentes, no corregir automáticamente los futuros: marcarlos con un comentario. |
| "y/o" | No está prohibido: mantener o reemplazar según el contexto (el Manual lo reserva para la disyunción inclusiva). |
| Comentarios y control de cambios | Autor **"Comentarios Senasa"**, iniciales **SENASA**. Los comentarios al margen no deben citar normas que un lector externo al equipo no entendería. |
| Versiones | v1.0 = versión limpia. Desde la v1.1, control de cambios sobre la versión anterior, que se van aceptando con las revisiones internas o externas del equipo del programa. |
| Nombres de archivo | `[Tema]_Proyecto_v1.0.docx` → `[Tema]_Proyecto_v1.1_rev-Senasa.docx` → `v1.2_rev-Senasa`… |
| Anexos reescritos | Se entregan como archivos nuevos sin control de cambios, conservando el formato, los encabezados y los pies originales. |
| Rango del acto | La DNSA solo dicta **Disposiciones**. Las **Resoluciones** las dicta la Presidencia del SENASA. |
| Comisiones asesoras o consultivas | Si sus conclusiones no son vinculantes (p. ej. Comisión Nacional de Sanidad y Bienestar de los Porcinos, RESOL-2021-542-APN-PRES#SENASA), no incluir cláusulas de consulta previa obligatoria. En los considerandos se usa "ha sido puesta en conocimiento". Verificar la norma de creación de cada comisión. |

---

## 3. Estructura del acto (Manual + práctica Res. 810/25)

### 3.1 Encabezado y VISTO
- En el proyecto, el encabezado GEDO queda para Gestión Documental. Usar marcadores:
  `Ciudad de Buenos Aires, XX/XX/XXXX`.
- `VISTO el Expediente N° EX-XXXX-XXXXXXXX- -APN-DGTYA#SENASA; [normas en orden jerárquico y luego cronológico], y`
- El Visto enumera las normas que sirven de base o están relacionadas: leyes → decretos → resoluciones ministeriales o
  de secretaría → resoluciones SENASA, cada grupo en orden cronológico. Cierra con `, y`.
- Base habitual en sanidad animal (verificar vigencia en cada caso; sumar las normas propias del tema):
  - Ley de Policía Sanitaria Animal N° 3.959.
  - Ley N° 27.233 y su Decreto Reglamentario N° DECTO-2019-776-APN-PTE del 19 de noviembre de 2019.
  - Decreto N° 1.585 del 19 de diciembre de 1996 y sus modificatorios (competencias del SENASA).
  - Resolución N° 38 del 3 de febrero de 2012 del entonces MINISTERIO DE AGRICULTURA, GANADERÍA Y PESCA y su
    modificatoria (acciones sanitarias o preventivas).
  - Resoluciones transversales según el tema: RESOL-2018-1-APN-PRES#SENASA (registro y acreditación de veterinarios
    privados y operadores – SUR), RESOL-2024-1446-APN-PRES#SENASA (REDLAB), Res. N° 108/2001 de la ex-SAGPyA
    (convenios con Entes Sanitarios), normas de identificación, RENSPA y tránsito (DT-e) de la especie, y el plan o
    programa nacional vigente del tema.

### 3.2 CONSIDERANDO
- `CONSIDERANDO:` en mayúsculas. Cada considerando empieza con `Que` y termina en punto.
- Orden recomendado:
  1. marco legal (Ley 3.959, Ley 27.233: interés nacional, autoridad de aplicación, responsabilidad primaria del
     productor);
  2. antecedentes normativos del tema y por qué se modifican o reemplazan;
  3. fundamentos técnicos y epidemiológicos (situación sanitaria, estándares de la OMSA, comercio);
  4. instancias de participación (comisiones nacionales o regionales, COPROSA, entes sanitarios, consulta pública);
  5. intervenciones de las áreas.
- Fórmulas de cierre (práctica vigente):
  - `Que la Dirección Nacional de Sanidad Animal [y demás áreas] ha[n] tomado la debida intervención.`
  - `Que la Dirección de Asuntos Jurídicos ha tomado la intervención que le compete.`
  - Resolución: `Que el/la suscripto/a es competente para dictar la presente medida en virtud de las facultades
    conferidas por el Artículo 8°, incisos e) y f), del Decreto N° 1.585 del 19 de diciembre de 1996 y sus modificatorios.`
    (Si la medida es de organización o procedimiento interno, la práctica cita el inciso h) del mismo artículo.)
  - Disposición DNSA: citar la norma que delega la facultad, p. ej. el artículo de "Facultades" de la resolución
    de base. Marcar `[COMPETENCIA A CONFIRMAR CON DAJ]` si no surge claramente de los antecedentes.
- Luego: `Por ello,` + línea de autoridad en mayúsculas, p. ej. `LA PRESIDENTE DEL SERVICIO NACIONAL DE SANIDAD Y
  CALIDAD AGROALIMENTARIA` / `EL DIRECTOR NACIONAL DE SANIDAD ANIMAL` + `RESUELVE:` / `DISPONE:`.
- Variación léxica de la práctica para no repetir el nombre: "el citado / referido / mentado / aludido Servicio
  Nacional", "la mencionada Resolución N° …".
- La parte expositiva no tiene que ser extensa salvo que la complejidad o la novedad lo justifiquen. Si el proyecto
  puede afectar derechos subjetivos, debe constar la intervención del servicio jurídico.

### 3.3 Parte dispositiva: orden
De lo general a lo particular, de lo abstracto a lo concreto, de lo normal a lo excepcional y de lo sustantivo a lo
procedimental:
1. **Prescripciones iniciales**: objeto o aprobación, alcance o ámbito (material, territorial, personal) y definiciones.
2. **Prescripciones principales**: organización, derechos, obligaciones, prohibiciones, procedimientos, régimen de
   clasificación, vacunación, movimientos, registros, rol de los veterinarios acreditados, muestras y laboratorios,
   entes sanitarios.
3. **PRESCRIPCIONES FINALES** (esta sección sí lleva ese título): invitación a provincias y municipios, notificación
   obligatoria, ingreso del personal, fiscalización, certificados, facultades a la DNSA, aprobación de anexos,
   abrogaciones y derogaciones, infracciones, régimen transitorio, vigencia y artículo de forma.

### 3.4 Artículos tipo (práctica)
- **Epígrafe**: todos los artículos llevan epígrafe, salvo el de forma. Formato:
  `ARTÍCULO 5°.- Establecimiento Bajo Vigilancia. Todo establecimiento…`
  El epígrafe es breve (una o dos palabras significativas), único, no repite el título de una división y usa los
  mismos términos que el texto. Para subtemas: `Vacunación protectora.`, `Vacunación de saneamiento.`
- **Definiciones**: `ARTÍCULO 3°.- Definiciones. A los fines de la presente resolución, se entiende por:` +
  incisos en orden alfabético (a, b, c… incluida la ñ).
- **Aprobación de anexo**: `ARTÍCULO X.- Anexo I. [Título]. Aprobación. Se aprueba el/la "[Título]" que, como
  Anexo I (IF-XXXX-XXXXXXXX-APN-DNSA#SENASA), forma parte integrante de la presente resolución.`
- **Facultades**: `Se faculta a la Dirección Nacional de Sanidad Animal del SENASA para dictar las normas técnicas
  complementarias que correspondan…`
- **Abrogación**: `ARTÍCULO X.- Abrogación. Se abroga la Resolución N° 474 del 31 de julio de 2009 de la
  ex-SECRETARÍA DE AGRICULTURA, GANADERÍA, PESCA Y ALIMENTOS del entonces MINISTERIO DE PRODUCCIÓN.`
- **Infracciones**: `El incumplimiento o las transgresiones a la presente norma serán pasibles de las sanciones
  establecidas en el Capítulo V de la Ley N° 27.233 y su Decreto Reglamentario N° DECTO-2019-776-APN-PTE del 19 de
  noviembre de 2019, sin perjuicio de las acciones preventivas que pudieran adoptarse en virtud de lo dispuesto en la
  Resolución N° 38 del 3 de febrero de 2012 del entonces MINISTERIO DE AGRICULTURA, GANADERÍA Y PESCA y su
  modificatoria, o la que en el futuro la reemplace.`
- **Vigencia**: `La presente resolución entra en vigencia a los [CIENTO OCHENTA (180)] días corridos de su
  publicación en el Boletín Oficial.` o `…a partir del día de su publicación en el Boletín Oficial.`
- **Incorporación al Digesto** (optativa, práctica de la Res. 720/22): `Se incorpora la presente resolución al
  Libro III "Reglamentación Agroalimentaria", Parte Tercera "Sanidad Animal", Título Segundo "Luchas Sanitarias",
  Capítulo II, Sección [n°] "[especie]", Subsección [n] "[enfermedad]" del Digesto Normativo del SENASA.` Tomar la
  ubicación exacta del Digesto (sección 9). Ofrecerla, no imponerla.
- **Forma** (último artículo, sin epígrafe): `ARTÍCULO X.- Comuníquese, publíquese, dese a la DIRECCIÓN NACIONAL DEL
  REGISTRO OFICIAL y archívese.`

### 3.5 Título de la norma
El título es expresivo, completo, neutro y no repite el de otra norma vigente. Partes: categoría, número y fecha
(cuando corresponda) y objeto. Si la norma es modificatoria, el título lo dice e identifica la norma modificada, con
el término específico (derogación, incorporación, sustitución, prórroga, suspensión, excepción). Si la norma es
heterogénea ("ómnibus"), el título indica su finalidad.

### 3.6 Anexos
- Al final del articulado, como documentos separados. `ANEXO I` en mayúsculas y negrita, número romano y título.
  Conviene indicar entre paréntesis el artículo que lo aprueba.
- Van en anexo **solo** tablas, cuadros, formularios, listados técnicos, diagramas, planos o textos muy extensos o
  detallados. Lo normativo va en el articulado (Módulo 4): si una norma vieja tiene todo en anexos, al consolidar se
  pasa a artículos, incisos y apartados.
- El artículo relacionado remite expresamente al anexo.
- En GDE cada anexo es un IF: usar el marcador `(IF-XXXX-XXXXXXXX-APN-DNSA#SENASA)`.
- Instructivos y manuales de procedimiento pertenecen al Libro IV del Digesto: evaluar si conviene aprobarlos por
  disposición DNSA separada en lugar de anexarlos.

### 3.7 Formato de números y nombres (práctica)
- Cantidades y plazos: en letras mayúsculas con la cifra entre paréntesis: `TREINTA (30) días corridos`,
  `CIEN (100) reproductores`, `CINCUENTA METROS (50 m)`, `VEINTICUATRO HORAS (24 h)`.
  Precisar siempre si los días son corridos o hábiles.
- Organismos en mayúsculas: `SERVICIO NACIONAL DE SANIDAD Y CALIDAD AGROALIMENTARIA (SENASA)` la primera vez; luego
  `SENASA` o "el citado Servicio Nacional". Dependencias en tipo título: "la Dirección Nacional de Sanidad Animal del
  SENASA", "la Oficina Local del SENASA de la jurisdicción correspondiente".
- `REPÚBLICA ARGENTINA`, `ORGANIZACIÓN MUNDIAL DE SANIDAD ANIMAL (OMSA)` en mayúsculas.
- Siglas: desarrollar la primera vez (DT-e, RENSPA, SUR, REDLAB, COPROSA, etc.).

---

## 4. Redacción (Manual, Capítulo Segundo)

**Estilo**
- Enunciados breves, simples, completos y autosuficientes. La integridad y la univocidad prevalecen sobre la elegancia.
- Sin enunciados sin valor normativo (deseos, recomendaciones, motivaciones): esos van en los considerandos.
- La norma ordena, prohíbe, autoriza, faculta, obliga, regula o sanciona.
- En las enumeraciones, aclarar si son taxativas o ejemplificativas y si son acumulativas o alternativas.

**Léxico**
- Elegir el término según la legislación vigente: primero la definición legal, después la jurisprudencia, después la
  doctrina.
- Homogeneidad: un concepto, un término. Sin sinónimos para el mismo concepto, también respecto de las normas afines
  (alinear con las definiciones de la Ley 27.233, del plan o programa nacional del tema y del Código Terrestre o
  Acuático de la OMSA).
- Repetir el término en lugar de usar pronombres que remitan a otros artículos.
- Evitar extranjerismos. Si son imprescindibles, definirlos.
- Definir solo lo indispensable. Las obligaciones van en el cuerpo, no en las definiciones.

**Gramática**
- Presente del indicativo. El futuro solo para relaciones temporales.
- Usar modalidades deónticas claras: "debe", "puede", "se prohíbe". Si hay duda entre imperativo y facultativo,
  reformular.
- Voz activa con agente identificado. Evitar la pasiva con "se" cuando oculta quién debe actuar: "El productor
  debe…", no "Se deberá…".
- Subjuntivo en: cláusulas relativas con antecedente indeterminado ("un presupuesto que contenga…"), finales ("para
  que…"), temporales prospectivas ("cuando se detecte…" + futuro o mandato) y verbos de mandato o influencia
  ("se prohíbe que ingresen…"). Indicativo con antecedente determinado y en acciones habituales ("cuando ingresan…,
  se alojan…").
- Condicionales: preferir el condicional real `Si + presente → presente/futuro/mandato`. Reemplazar el futuro de
  subjuntivo arcaico ("pudieren", "creare") por el presente. Mantener una sola estructura condicional en todo el texto.
- Sin doble negación.
- Conjunciones:
  - "y" para sumar elementos (comas + "y" antes del último);
  - "o" para alternativas (si debe ser excluyente, decir "solo A o solo B" o "A o B, pero no ambos");
  - "u" antes de palabras que empiezan con o/ho;
  - "solo si…" cuando la condición es exclusiva.
- Remisión residual: Diccionario y reglas de la Real Academia Española.

---

## 5. Citas y referencias (Manual, Capítulos Tercero y Cuarto, con la práctica vigente)

**Cita completa la primera vez**: categoría + número + fecha + organismo emisor completo (sin siglas) + título, si
lo tiene. Por decisión del equipo, sin número ni fecha del Boletín Oficial.
- Resolución GDE: `Resolución N° RESOL-2024-1446-APN-PRES#SENASA del 12 de diciembre de 2024 del SERVICIO NACIONAL DE
  SANIDAD Y CALIDAD AGROALIMENTARIA`.
- Resolución anterior al GDE: `Resolución N° 108 del 16 de febrero de 2001 de la ex-SECRETARÍA DE AGRICULTURA,
  GANADERÍA, PESCA Y ALIMENTACIÓN del entonces MINISTERIO DE ECONOMÍA`.
- Decreto: `Decreto N° 1.585 del 19 de diciembre de 1996` / `Decreto Reglamentario N° DECTO-2019-776-APN-PTE del 19
  de noviembre de 2019`.
- Organismos que ya no existen: "ex-" para el emisor y "entonces" para el ministerio de dependencia.
- Varias normas del mismo emisor: `las Resoluciones Nros. 666 del 2 de septiembre de 2011, 671 del 23 de noviembre
  de 2016 …, todas del SERVICIO NACIONAL…`.
- Normas con modificaciones: agregar "y su modificatoria" o "y sus modificatorias".
- Citas posteriores: forma abreviada `la citada Resolución N° 474/09`.
- Normas no publicadas: agregar `(N.P.)`.

**Citas parciales**: en orden decreciente y separadas por comas: `Artículo 4°, inciso b), apartado I),
subapartado ii) de la Resolución…`. Llegar hasta la división del nivel más bajo necesario. Si la parte citada no es
una unidad formal, transcribirla entre comillas. Si se modifica una norma aprobada como anexo, indicarlo:
`artículo 3° del Anexo I de…`. Los expedientes se citan con su número completo.

**Referencias**:
- Uso restringido; preferir reformular el texto antes que remitir.
- Al reiterar un texto, que sea idéntico y que se note que es repetición.
- Prohibido: "artículo anterior/siguiente", "último inciso", referencias en cadena.
- Las referencias externas pueden ser estáticas o dinámicas. Para que sea estática, decirlo
  expresamente ("conforme su redacción al momento de la emisión de esta resolución"); si no, se interpreta como dinámica.

---

## 6. Entrada en vigor

- Fecha cierta, o fijada en relación con la publicación. Nunca anterior a la publicación.
- La vigencia se fija en la propia norma, no en otra.
- Una norma nunca entra en vigor antes que su norma de base.
- No condicionar la vigencia. Si es inevitable, que la condición sea fácil de conocer.
- Aplicación diferida o gradual: identificar con precisión las disposiciones afectadas. Por ejemplo, los cronogramas
  progresivos de la Res. 810/25 se expresan en días corridos desde la entrada en vigencia.
- Efecto retroactivo: solo excepcional.

---

## 7. Modificación, derogación, abrogación (Manual, Capítulos Sexto y Séptimo)

**Elegir la técnica**
- Pocas intervenciones: modificación explícita textual (sustitución o incorporación) sobre la **norma originaria**,
  nunca sobre sus modificatorias. Si existe un texto ordenado oficial, se cita la norma originaria y el texto ordenado
  más reciente, sin mencionar las modificaciones posteriores.
- Muchas intervenciones, cambio sustancial, regulación dispersa en varias normas, o un tema secundario que pasa a
  tener regulación propia: **texto nuevo integral + abrogación expresa** de lo anterior. Ejemplo: la Res. 810/25
  abrogó la Res. 474/09.
- La Res. 720/22 (Anexo II, punto 3) exige evaluar la consolidación o el reemplazo para evitar la "contaminación
  normativa" cuando el proyecto modifica o amplía normas preexistentes.
- Una norma modificatoria no contiene normas materiales autónomas: si hacen falta, van en una norma separada.
- Respetar la terminología, la estructura y el orden de la norma modificada.

**Verbos y fórmulas** (uno por caso, sin sinónimos)

| Caso | Fórmula | No usar |
|---|---|---|
| Sustitución | `Se sustituye el artículo 5° de la Resolución N° …, el que queda redactado de la siguiente manera: "ARTÍCULO 5°.- …".` | "deroga y sustituye", "modifícase" genérico |
| Incorporación | `Se incorpora como inciso k) del artículo 9° de la Resolución N° … el siguiente texto: "…".` | "se agrega", "se añade", "se incluye", "se amplía", "se integra" |
| Derogación (parcial) | `Se deroga el inciso c) del artículo 4° de la Resolución N° …` | "se deja sin efecto", "se elimina", "se suprime", "en cuanto se oponga" |
| Abrogación (total) | `Se abroga la Resolución N° …` | "abrógase en cuanto se oponga", "todas las disposiciones incompatibles", "a los efectos de la presente" |
| Prórroga / suspensión | Indicar expresamente qué norma y por cuánto tiempo (explícita textual). | — |
| Excepción | Excepción explícita textual. | Excepciones implícitas |
| Sustitución masiva de una expresión | `Dondequiera que aparezca la expresión "A", se sustituye por "B".` | — |

**Reglas de detalle**
- Un artículo modificatorio por cada artículo modificado. Si se modifican varios incisos de un mismo artículo, se
  admite un solo artículo modificatorio, pero evaluar la sustitución total del artículo.
- Si el artículo es breve, sustituirlo completo aunque solo cambie una frase. Si la frase está en un inciso o
  apartado identificable, sustituir ese inciso o apartado.
- **Nunca renumerar** el articulado al derogar o incorporar.
- Los artículos incorporados se numeran con bis, ter, quáter… (entre bis y ter: "bis-1"). Si van al final, toman el
  número siguiente al último antes del de forma. Si los artículos tienen epígrafe, el incorporado también lo lleva.
- Las derogaciones y abrogaciones se redactan en forma explícita, precisa y exhaustiva, en las Prescripciones finales.
- No hace falta abrogar normas de vigencia temporal ya vencida ni normas solo modificatorias, porque agotan su objeto.
- Reviviscencia: abrogar una norma abrogatoria o modificatoria no revive el texto anterior. Hay que reescribirlo.

**Una norma por unidad de materia**: una modificatoria puede alcanzar varias normas solo si hay unidad de materia o
de causa.

---

## 8. Consolidación normativa (Módulo 4)

1. **Relevar** las normas vigentes del tema (índice del Digesto, Infoleg, Boletín Oficial, CNS):
   - excluir lo que modifica directamente el Decreto 4238/68, que ya es un texto ordenado;
   - incluir las circulares, órdenes de servicio o notas que impongan obligaciones a los administrados: deben pasar a
     resolución o disposición;
   - separar los manuales de procedimiento y protocolos especiales (Libro IV).
2. **Esqueleto** con los grandes temas, alineado en lo posible con el índice temático. Justificar las diferencias.
3. **Borrador**:
   - copiar los textos de origen, con un **comentario de origen** en cada fragmento (`Origen: Res. SENASA N° …, art. …`);
   - incorporar los textos ya modificados en su redacción vigente;
   - consolidar por temas; la numeración de los artículos es correlativa entre temas.
4. **Control de integridad**: tabla de correspondencia artículo de origen → artículo nuevo, o "derogado
   deliberadamente" con su motivo. Lo que no se traslade pierde vigencia con la abrogación.
5. **Adecuación al Manual**, con control de cambios: presente, estructura, anexos solo para tablas y formularios.
6. **Actualización** de fondo (opcional), con control de cambios aparte.
7. **Aprobación**: una resolución que aprueba el texto ordenado y abroga expresamente todas las normas consolidadas.
   Los proyectos de consolidación están exceptuados de la consulta (Res. 720/22, Anexo II, punto 7.4.4).

---

## 9. Búsqueda de normativa relacionada

### 9.1 Orden de trabajo
1. **Material del usuario**: primero lo que cargó en el chat o el proyecto.
2. **Ubicación temática**: con el índice del Digesto (sección 9.3), definir la rama del tema (p. ej. Libro III,
   Parte Tercera, Título Segundo, Capítulo II, Sección 1° Bovinos, Subsección 1 Brucelosis Bovina). Revisar también
   las ramas transversales: registros y habilitaciones, sistema de información sanitaria (DTA/DT-e), bienestar animal,
   epidemiología, cuarentena e intercambios, laboratorio, productos veterinarios y vacunas, Libro II (Ley 3.959,
   enfermedades, protección de animales) y Libro I (OMSA, MERCOSUR).
3. **Digesto SENASA** (sección 9.2): listar las normas que la DAJ clasificó en cada rama y abrir sus fichas
   (vigencia, publicación, normas que reemplaza, enlace a Infoleg).
4. **Infoleg** (texto actualizado y relaciones "modifica / modificada por"; identifica las normas si el Digesto no
   estuvo disponible):
   - Búsqueda por norma (tipo + número + año; mínimo dos criterios) o por texto, con dependencia "SERVICIO NACIONAL
     DE SANIDAD Y CALIDAD AGROALIMENTARIA".
   - Ficha: `https://servicios.infoleg.gob.ar/infolegInternet/verNorma.do?id=NNNNNN` → muestra "Esta norma modifica o
     complementa a…" y "Esta norma es complementada o modificada por…".
   - Texto original: `https://servicios.infoleg.gob.ar/infolegInternet/anexos/{A}-{B}/{id}/norma.htm`
     Texto actualizado: `…/{id}/texact.htm` ({A} = id redondeado hacia abajo a múltiplo de 5000; {B} = A + 4999;
     ej.: id 374512 → `370000-374999`).
   - Infoleg publica las normas de alcance general: muchas disposiciones o resoluciones internas no figuran.
5. **Boletín Oficial** (texto oficial desde 2016; digitalizado desde 1995):
   - Búsqueda avanzada en la primera sección por organismo, tipo, número y fecha.
   - Aviso: `https://www.boletinoficial.gob.ar/detalleAviso/primera/{id}/{AAAAMMDD}`. Los anexos se publican como
     archivos aparte en la edición web.
6. **CNS – Código de Normas SENASA (1999)**: recopilación oficial de la normativa del SENASA vigente en 1999
   (Res. SENASA 642/1999), reemplazada luego por el Digesto. Es un PDF de 1740 páginas y **es optativo**: solo hace
   falta para leer el texto de normas antiguas (SAG, SAGyP, ex-SENASA, ex-IASCAV) que no estén ni en el Digesto ni en
   Infoleg. El Digesto ya tiene el PDF de muchas normas antiguas: buscar ahí primero.
   - Para **identificar** normas antiguas no hace falta el PDF: usar `references/cns-indice.md` (código, tema,
     palabra clave, página impresa y página del PDF; página PDF = página impresa + 72).
   - Si hay que **leer** una norma que solo está en el CNS y el usuario no adjuntó el PDF: explicarle en una línea qué
     es el CNS, indicarle la norma y la página del PDF donde está, y decirle dónde conseguirlo (carpeta de descarga:
     https://drive.google.com/drive/folders/1wo-0AfhHfJEEUvt6NHH9lnnKQ20og6E2, o pedírselo a quien compartió la skill). Mientras tanto, seguir trabajando:
     citar la norma con los datos del índice y marcarla `[TEXTO NO VERIFICADO – CNS p. N]`.
   - Si el usuario adjunta el PDF, leer las páginas indicadas (el texto está a dos columnas: verificar el orden).
   - Códigos: `RZ` = Res. ex-SENASA (sanidad animal, antes de 1996), `RS` = Res. SENASA, `RX` = Res. ex-SAyG,
     `RY` = Res. ex-SAGyP, `RE` = Res. de Secretaría de Estado, `DZ` = Disp. ex-SENASA, `DE` = Decreto, `LE` = Ley.
     En la cita final, convertir el código a la forma completa (p. ej. RZ 510/96 → "Resolución N° 510 del 26 de
     agosto de 1996 del ex-SERVICIO NACIONAL DE SANIDAD ANIMAL").
7. **Vigencia**: confirmar con la ficha del Digesto ("Reemplaza a", "Fecha disponibles"), con Infoleg ("modificada
   por", "abrogada por") y con la norma posterior más reciente del tema. El CNS refleja 1999. Muchas de sus normas
   están abrogadas o reemplazadas (p. ej. Aujeszky: RZ 510/96 → Res. SAGPyA 474/09 → Res. SENASA 810/25).

### 9.2 Digesto SENASA

El Digesto (`https://digesto.senasa.gob.ar/`) es la fuente que clasifica la normativa vigente según el índice temático
de la DAJ. Conviene consultarlo antes que Infoleg porque, para cada rama del índice, devuelve directamente qué normas
la componen, y cada ficha trae vigencia, publicación y normas reemplazadas.

**Cómo acceder.** La consulta web común falla por el certificado SSL del sitio. Usar, en este orden:
1. **Conector Firecrawl** (`firecrawl_scrape`, formato `markdown`, `onlyMainContent: true`, `maxAge: 0` para datos al
   día). Funciona sin problemas de certificado. Si devuelve un error de resolución DNS o de conexión, reintentar
   **una vez**: suele ser transitorio.
2. Si Firecrawl no está conectado o vuelve a fallar: navegador conectado (Claude in Chrome o navegador integrado).
3. Si tampoco hay navegador: seguir con Infoleg y el Boletín Oficial y **ofrecer** al usuario pegar el listado de la
   rama. Nunca detener la tarea por el Digesto.

Cada página consultada con Firecrawl consume un crédito: consultar solo las ramas y fichas que el caso necesita
(típicamente 3 a 10 páginas) y no recorrer el árbol completo (la página `/subjects/tree` es muy extensa: no
scrapearla; usar la sección 9.3, `references/digesto-indice.md` o la búsqueda por texto).

**URLs útiles.** Cada listado muestra unos 10 registros por página. Si indica más registros (p. ej. "13
registros"), seguir el enlace de la página 2 que trae el propio listado (`/items/browse/page/2?…`). El panel
"Refinar búsqueda" del listado también enumera los títulos de todas las normas del resultado.

| Consulta | URL |
|---|---|
| Normas de una rama del índice | `https://digesto.senasa.gob.ar/items/browse?advanced[0][element_id]=94&advanced[0][type]=is+exactly&advanced[0][terms]={TÍTULO EXACTO DE LA RAMA}` |
| Búsqueda por texto | `https://digesto.senasa.gob.ar/items/browse?search={términos+separados+por+más}` |
| Ficha de una norma | `https://digesto.senasa.gob.ar/items/show/{id}` (el id surge de los listados) |
| PDF de la norma | enlace "Descargar" de la ficha (`items/show/{id}?download={n}`) |

El título de la rama va exacto, como figura en el índice (con el guion largo "–" y los paréntesis), codificado para
URL. Ejemplo: `Subsección 2 – Enfermedad de Aujeszky` → `Subsecci%C3%B3n+2+%E2%80%93+Enfermedad+de+Aujeszky`. Los
títulos exactos de los niveles principales están en la sección 9.3 y el árbol completo en
`references/digesto-indice.md`. Si no se conoce el título exacto de una rama, hacer primero la búsqueda por texto:
cada resultado muestra su ubicación completa en el índice, de donde se copia el título exacto. Algunos títulos se
repiten en distintos libros: verificar en los resultados la ruta completa.

**Qué extraer.**
- **Listado de una rama**: cantidad de registros; por cada norma, título (p. ej. "Resolución SENASA N° 0810/2025"),
  descripción, ubicación completa en el índice (una norma puede estar en varias ramas) y enlace "Fuente" a Infoleg.
- **Ficha**: fecha, resumen, vigencia ("Fecha disponibles"), publicación en el Boletín Oficial (fecha, número,
  página), normas que reemplaza o abroga ("Reemplaza a"), anexos y PDF.

**Estrategia.** Los listados pueden traer normas clasificadas en varias ramas o con clasificaciones dudosas
(p. ej. una norma de calidad de granos dentro de una rama de brucelosis): incluir solo las que tienen relación real
con el proyecto. Empezar por la rama específica del tema; después la búsqueda por texto, que encuentra normas
clasificadas en otras ramas (laboratorio, epidemiología, vacunas, Libro II). Abrir la ficha solo de las normas que
van a entrar en la tabla de antecedentes. El Digesto puede tener demoras de actualización: las normas muy recientes
se confirman en el Boletín Oficial.

**Para qué sirve además**: proponer la ubicación de la norma nueva en el índice, dato que pide el expediente, y el
artículo optativo de incorporación al Digesto (sección 3.4).

### 9.3 Índice temático del Digesto: estructura de Sanidad Animal

LIBRO TERCERO: REGLAMENTACIÓN AGROALIMENTARIA → `Parte Tercera - Sanidad Animal`. Títulos exactos de los niveles
principales (copiarlos tal cual para la URL; el árbol completo, con subsecciones y apartados, está en
`references/digesto-indice.md` o se obtiene con la búsqueda por texto):

- `Título Primero - Gestión Sanitaria – Registros, Habilitaciones y Sistemas`
  - `Capítulo I - Gestión General de Sanidad Animal`
  - `Capítulo II - Control de Gestión Sanitaria` (identificación animal por especie)
  - `Capítulo III - Registros y Habilitaciones (identificación animal)` (RENSPA, engorde a corral, predios de
    exportación, granjas, centros de inseminación, remates feria, lavaderos de camiones, transporte de hacienda,
    profesionales, productores porcinos, otros registros, Clave Única de Identificación Ganadera)
  - `Capítulo IV - Sistema de Información Sanitaria` (SIGSA/SGS: DTA, DT-e, libreta sanitaria equina, tránsito de
    colmenas, certificado sanitario general)
- `Titulo segundo - Luchas Sanitarias`
  - `Capítulo I – Reglamentos`
  - `Capítulo II – Programas de Prevención, Control y Erradicación de enfermedades animales`
    - `Sección 1° - Bovinos` (brucelosis, tuberculosis, EEB, garrapata, leucosis, sarna, fiebre aftosa, mosca de los cuernos)
    - `Sección 2° - Rumiantes menores`
    - `Sección 3° - Porcinos` (PPC, Aujeszky, triquinosis, tuberculosis, influenza, tenencia, planes de contingencia)
    - `Sección 4° - Equinos (Programas de Prevención, Control y Erradicación)`
    - `Sección 5° - Aves (Programas de Prevención, Control y Erradicación)`
    - `Sección 6° - Abejas`
    - `Sección 7° - Animales acuáticos (Programas de Prevención, Control y Erradicación)`
    - `Sección 8° - Conejos` · `Sección 9° - Caracoles` · `Sección 10° - Camélidos Americanos`
    - `Sección 11° - Enfermedades comunes a varias especies animales` (hidatidosis, rabia, carbunclo)
  - `Capítulo III – Bienestar Animal` (protección legal, insensibilización, habilitación de transporte, alimentos
    orgánicos, Comisión Nacional Asesora, alimentación forzada)
- `Título tercero – Epidemiología`
  - `Capítulo I – Régimen General de Epidemiología` · `Capítulo II – Fiebre aftosa` ·
    `Capítulo III –Vigilancia Epidemiológica` · `Capítulo IV – Contingencia y Emergencia Sanitaria` ·
    `Capítulo V – Bioestadística y Epidemiología Analítica` · `Capítulo VI – Análisis de Riesgo`
- `Título Cuarto – Cuarentena Animal / Intercambios Internacionales`
  - `Capítulo I – Animales vivos` · `Capítulo II – Material de Multiplicación Animal` ·
    `Capítulo III – Productos de Origen Animal y Otras Mercancías`
- `Titulo Quinto: Agricultura Familiar` · `Título Sexto: Registros Sanitarios`

Otras ramas relevantes para la DNSA: Libro III, Parte Cuarta (productos veterinarios, vacunas y alimentos para
animales) y Parte Quinta (laboratorio animal); Libro II, Parte Primera – Legislación Sanitaria (policía sanitaria,
importación de animales, enfermedades, reproducción, identificación, transporte de ganado, zoonosis, protección de
animales); Libro I (OMSA, MERCOSUR); Libro IV (normas de procedimiento, manuales, protocolos especiales).

Los títulos del Digesto respetan la grafía del sitio, incluidas sus inconsistencias ("Titulo" sin tilde, guion corto
o largo, espacios): si una URL con el título exacto no devuelve resultados, usar la búsqueda por texto.

### 9.4 Informe de antecedentes (salida estándar de la búsqueda)

| Norma (cita completa) | Emisor | Fecha | Objeto | Vigencia / modificaciones | Fuente (URL) | Tratamiento en el proyecto |
|---|---|---|---|---|---|---|

El tratamiento puede ser: citar en el VISTO, fundamentar en un CONSIDERANDO, sustituir o derogar parcialmente,
abrogar, mantener o remitir. Señalar las superposiciones o contradicciones con el proyecto y los términos definidos
de forma distinta. Indicar siempre la fuente consultada y la fecha de consulta. Si no se pudo verificar la vigencia,
decirlo.

---

## 10. Procedimiento de aprobación (Res. 720/2022, Anexo II t.s. Res. 756/2024)

Verificar en Infoleg si hay modificaciones posteriores a 2024.

1. **Autorización**: formulario **FONSE** ("Formulario Propiciar y/o Modificar Normas SENASA") en GEDO, elevado a la
   Unidad Presidencia. Lleva como archivos de trabajo la propuesta, los antecedentes y el informe técnico, firmados
   por una autoridad con sello no menor a Director/a o Coordinador/a.
2. **Expediente**: código de trámite `ACTO00005 – Proyecto de Resolución` o `GENE00039 – Proyecto de Disposición`.
3. **Propuesta normativa**: clara y accesible, conforme al Manual (Res. 401/2010) y a las buenas prácticas
   regulatorias (OCDE; Decisión CMC MERCOSUR N° 20/18). Se vincula como **PRESO** (resolución) o **PDISP**
   (disposición). Los anexos van como documento **ANEX**. Evaluar la consolidación si modifica otras normas.
4. **Antecedentes normativos**: versiones **actualizadas**, en orden jerárquico y temporal, unificadas en un PDF
   generado como **IFGRA** con la referencia "ANTECEDENTES NORMATIVOS".
5. **Informe Técnico (IFTEC)**: ver sección 11.
6. **Visto bueno de las áreas sustantivas** si el proyecto es transversal: CINCO (5) días hábiles, prorrogables.
7. **Consultas** (la interna y la pública nacional son simultáneas):
   - Interna: TRES (3) días hábiles.
   - Pública Nacional: en la web del SENASA, hasta DIEZ (10) días hábiles.
   - Internacional (medidas MSF, notificación a la OMC): hasta SESENTA (60) días hábiles; el silencio cuenta como
     conformidad.
   - Excepciones: urgencia justificada, emergencia o riesgo para la salud, dispensa de la autoridad, o
     consolidación u ordenamiento normativo.
8. **Resultado de las consultas**: en DIEZ (10) días hábiles, cuadro de aceptaciones y rechazos (documento IF), que
   se publica de forma anónima. Además, respuesta individual por correo institucional a cada participante.
   Columnas del cuadro:

   | Origen del aporte | Aporte | Incorporación total | Incorporación parcial | Rechazo | Justificación de la respuesta |
   |---|---|---|---|---|---|
   | Consulta Interna | | | | | |
   | Consulta Pública Nacional | | | | | |
   | Consulta Pública Internacional | | | | | |

   Los aportes no son vinculantes.
9. **Dictamen de la DAJ**: DIEZ (10) días hábiles. Si hay que subsanar, el área tiene CINCO (5) días hábiles y la
   DAJ hace la revisión final en CINCO (5) días hábiles.
10. **Formalización**: PRESO o PDISP definitivo, firmado por una autoridad no menor a Director/a Nacional, con la
    referencia "PROYECTO DEFINITIVO PARA LA FORMALIZACIÓN DEL ACTO ADMINISTRATIVO" y el Word como archivo de trabajo.
    Luego pasa a Gestión Documental para la firma y la publicación en el Boletín Oficial.

---

## 11. Informe Técnico (IFTEC)

Redactarlo de forma íntegra y fundamentada, en prosa técnica y con los mismos términos que la propuesta.
Estructura mínima (Res. 720/22, Anexo II, punto 5):

**5.1 Identificación**: actividad a regular o norma a actualizar. Indicar si afecta otras normas (abroga, sustituye,
incorpora) o si es una consolidación, y si **crea, modifica o suprime trámites, procedimientos o registros**.

**5.2 Análisis técnico**: razones concretas, objeto (qué se implementa, adecua, mejora o sustituye), impacto social
y ambiental esperado. Enumerar las alternativas de procedimientos o tecnologías evaluadas, explicar la elegida y su
justificación económica (quién paga: productor, SENASA, terceros).

**5.3 Justificación técnica y económica de la metodología**: procedimientos y tecnologías seleccionados, su
instrumentación, las alternativas y por qué la elegida es la más idónea. Valoración de los efectos positivos y
negativos sobre consumidores, administrados y sector. Recursos presupuestarios disponibles.

**5.4 Ámbito geográfico**: regional o nacional.

**5.5 Ámbito temporal**: vigencia desde y hasta cuándo, plazos de instrumentación total o parcial (cronogramas).

**5.6 Recursos humanos**: estimación en días u horas-hombre o personal, necesidades de capacitación y de adecuación
de áreas.

**5.7 Gobiernos locales y evaluación**: acciones recomendadas a provincias y municipios donde el SENASA no tiene
jurisdicción, medidas equivalentes, y mecanismos e indicadores para evaluar en un plazo razonable si se cumplió la
finalidad.

**5.8 Registros nuevos**: si el proyecto crea registros, debe pasar por la JEFATURA DE GABINETE DE MINISTROS
(artículo 12 del Decreto N° DECTO-2017-891-APN-PTE del 1 de noviembre de 2017).

Conviene apoyar el 5.2 y el 5.3 con:
- datos epidemiológicos (brotes, prevalencia, estatus de los establecimientos según los sistemas del SENASA);
- estándares de la OMSA (capítulo y artículo del Código Terrestre o del Código Acuático);
- impacto comercial y en las negociaciones sanitarias;
- consensos de las comisiones o ámbitos consultivos del tema;
- costo para el productor y para el SENASA.

Los datos que no estén en el material provisto se dejan como marcadores `[DATO A COMPLETAR: …]`: nunca inventar cifras.

---

## 12. Flujos por caso

**A. Norma nueva**
1. Antecedentes (sección 9).
2. Rango y competencia.
3. Esqueleto por secciones.
4. Propuesta para aprobar.
5. Redacción v1.0 limpia.
6. Lista de verificación.
7. Si se pide, IFTEC y antecedentes.

**B. Modificación**
1. Obtener el texto vigente actualizado de la norma originaria.
2. Decidir entre modificación textual y texto nuevo con abrogación (sección 7).
3. Cuadro comparativo: Texto vigente | Texto propuesto | Fundamento.
4. Redactar los artículos modificatorios.

**C. Abrogación**
1. Verificar que lo que se quiere conservar quede en otra norma.
2. Revisar las normas que remiten a la abrogada (referencias rotas).
3. Redactar la cláusula explícita y exhaustiva.

**D. Consolidación**
Sección 8. Entregables: tabla de correspondencia, borrador con comentarios de origen y texto ordenado.

**E. Revisión de un borrador (v1.x)**
1. Trabajar sobre el .docx con control de cambios, autor "Comentarios Senasa".
2. Cambios de forma (Manual) y de fondo en cambios separados o identificables.
3. Futuros marcados con un comentario.
4. Comentarios breves, comprensibles para un lector externo.
5. Antes de editar, listar los cambios propuestos.

**F. Informe Técnico y antecedentes**
Sección 10 y sección 11.

**Archivos Word**: usar la skill o herramienta de .docx disponible. El control de cambios y los comentarios deben
ser nativos de Word (autor "Comentarios Senasa"), no texto coloreado.

---

## 13. Lista de verificación final

- [ ] Rango y autoridad firmante correctos. Competencia citada en el último considerando.
- [ ] VISTO completo, en orden jerárquico y cronológico, con citas completas sin número de Boletín Oficial.
- [ ] Considerandos con "Que…" y punto final; intervenciones de las áreas y de la DAJ; "Por ello,".
- [ ] Artículos: 1° a 9° ordinales y desde 10 cardinales; epígrafes en todos salvo el de forma; incisos, apartados y
      subapartados con la nomenclatura del equipo.
- [ ] Secciones en mayúsculas sin numerar; las prescripciones finales en su sección.
- [ ] Presente del indicativo, voz activa, sujeto obligado identificado, sin doble negación ni futuro de subjuntivo.
- [ ] Términos homogéneos y alineados con las definiciones; siglas desarrolladas; números en letras con la cifra.
- [ ] Sin referencias del tipo "anterior/siguiente"; citas parciales hasta el nivel mínimo.
- [ ] Anexos: solo tablas, cuadros o formularios; aprobados por artículo con su IF; remisión desde el articulado.
- [ ] Modificaciones sobre la norma originaria, con el verbo correcto y sin renumerar.
- [ ] Derogaciones y abrogaciones explícitas y exhaustivas, sin "en cuanto se oponga".
- [ ] Infracciones (Ley 27.233, Cap. V; Decreto 776/19; Res. MAGyP 38/12), vigencia y artículo de forma.
- [ ] Vigencia de todas las normas citadas verificada, con la fuente y la fecha de consulta.
- [ ] Marcadores pendientes listados al final (EX, IF, datos, competencia).
- [ ] Nombre de archivo y versión según la convención.