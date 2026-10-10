# Skill "labor-normativa-senasa": instalación y personalización

Skill para redactar, modificar, abrogar y consolidar proyectos normativos de cualquier Programa o área de la
Dirección Nacional de Sanidad Animal del SENASA. Aplica el Manual de Técnicas Legislativas (Res. 401/2010) y la
práctica vigente, busca la normativa relacionada (Digesto SENASA, Infoleg, Boletín Oficial, CNS) y arma el Informe
Técnico (IFTEC) y los antecedentes según la Res. 720/2022. Al empezar cada trabajo identifica sola el programa, la
especie y las ramas del Digesto a partir del material que le pases, así que se puede usar sin personalizar.

Contenido del ZIP `labor-normativa-senasa.zip`:

```
labor-normativa-senasa/
├── SKILL.md                     instrucciones de la skill
└── references/
    ├── digesto-indice.md        árbol completo del índice temático del Digesto (634 ramas) + URL por rama
    ├── cns-indice.md            codificación del CNS, índice general (696 normas con página) y palabras clave
    └── fuentes.md               PDF usados para construirla y qué se tomó de cada uno
```

Los PDF fuente no están en el ZIP. La lista está en `references/fuentes.md`. Si necesitás alguno, pedíselo a
Alejandro Pérez (Programa de Sanidad Porcina).

**Importante: subí a Claude solo el archivo `labor-normativa-senasa.zip`** (sin descomprimir). Este instructivo es
para leer: si lo subís como skill, Claude muestra el error "SKILL.md must start with YAML frontmatter".

**Última versión y CNS:** https://drive.google.com/drive/folders/1wo-0AfhHfJEEUvt6NHH9lnnKQ20og6E2
El CNS (Código de Normas SENASA, 1999) es **optativo**: la skill funciona sin él y solo lo pide si necesita leer
el texto de una norma antigua que no está en el Digesto ni en Infoleg.

---

## Opción A: instalarla tal cual

1. En Claude, activar "Code execution and file creation" (Settings > Capabilities).
2. Ir a Customize > Skills → "+" → "Create skill" → "Upload a skill" y subir `labor-normativa-senasa.zip` sin
   descomprimir.
3. Usarla escribiendo `/labor-normativa-senasa` al principio del mensaje, o pidiendo la tarea normativa directamente.

## Opción B: personalizarla para tu programa (opcional)

1. Abrir un chat nuevo en Claude.
2. Adjuntar `labor-normativa-senasa.zip`.
3. Pegar el prompt de abajo y responder las preguntas que haga Claude.
4. Instalar el ZIP que te devuelva (pasos de la Opción A).

### Prompt para personalizar

```
Adjunto el ZIP de una skill de Claude llamada "labor-normativa-senasa", creada en el Programa de Sanidad Porcina
del SENASA para redactar y modificar proyectos normativos. Quiero ajustarla a mi programa sanitario.

Trabajá en este orden y no modifiques nada hasta que yo confirme:

1. Descomprimí el ZIP y leé SKILL.md y los tres archivos de references/.
2. Haceme un resumen breve de qué hace la skill, de su estructura por secciones y de las fuentes que usa
   (references/fuentes.md), para que yo decida si necesito pedir alguno de los PDF originales.
3. Preguntame, en una sola tanda, lo necesario para fijar en la sección 0 los datos de mi programa:
   - nombre del programa y dirección de la que depende;
   - especies y enfermedades o temas que abarca;
   - normas base del programa (leyes, decretos, resoluciones vigentes) que conozca;
   - comisiones o ámbitos consultivos y si sus conclusiones son vinculantes;
   - ramas del Digesto que le corresponden (proponémelas vos a partir de references/digesto-indice.md);
   - normas modelo del programa que quiera usar como ejemplo además de la Res. 810/25.
4. Mostrame las convenciones de trabajo de la sección 2 (numeración de artículos, incisos, títulos de sección,
   formato de citas, autor de comentarios, nombres de archivo, versiones, artículos nuevos sin numerar, "y/o",
   tiempo verbal) y preguntame cuáles mantengo y cuáles cambio.
5. Con mis respuestas, proponeme los cambios concretos a SKILL.md (qué secciones se tocan y cómo). Esperá mi OK.
6. Recién con mi OK:
   - aplicá los cambios;
   - si cambio el nombre de la skill (p. ej. "labor-normativa-senasa-bovinos"), cambiá el campo name del SKILL.md
     y el nombre de la carpeta, que deben coincidir (minúsculas, números y guiones);
   - ajustá la description para que mencione mi programa (máximo 1024 caracteres, sin los signos < ni >);
   - si te paso normas propias del programa, agregalas en un archivo nuevo references/normas-programa.md
     y mencionalo en SKILL.md;
   - no cambies las reglas del Manual de Técnicas Legislativas ni el procedimiento de la Res. 720/2022.
7. Devolveme el ZIP final con la carpeta de la skill en la raíz, listo para subir en Customize > Skills.
```

---

## Uso diario

- Empezar el mensaje con `/labor-normativa-senasa` (o el nombre que le hayas dado) y describir el caso: norma nueva,
  modificación, abrogación, consolidación, revisión de un borrador o Informe Técnico.
- Adjuntar la norma vigente, el borrador y los antecedentes que tengas.
- La skill primero presenta el diagnóstico y las decisiones a confirmar. Redacta recién cuando le respondés
  "A escribir!".
- **Digesto SENASA:** Claude lo consulta con el conector **Firecrawl**, porque la consulta web común falla por el
  certificado del sitio. Para eso necesitás una cuenta de Firecrawl (firecrawl.dev) conectada a Claude como
  conector; cada página consultada consume un crédito (una búsqueda típica usa entre 3 y 10). Sin Firecrawl, la skill
  usa Chrome si está conectado o te pide que pegues el listado de la rama, y sigue con Infoleg y el Boletín Oficial.
- Si vas a trabajar con normas muy antiguas, adjuntá el PDF del CNS: la skill sabe en qué página buscar cada norma.
