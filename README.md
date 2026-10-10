# labor-normativa-senasa

Skill de Claude para redactar, modificar, abrogar y consolidar proyectos normativos de cualquier Programa o área de la
Dirección Nacional de Sanidad Animal del SENASA (Argentina). Aplica el Manual de Técnicas Legislativas
(Res. SENASA 401/2010) y la práctica vigente, busca normativa relacionada (Digesto SENASA, Infoleg, Boletín Oficial,
CNS) y arma el Informe Técnico (IFTEC) y los antecedentes según la Res. SENASA 720/2022.

## Instalación

1. Descargá **`labor-normativa-senasa.zip`** desde la sección **Releases** de este repositorio (columna derecha →
   última versión → *Assets*). No uses el botón verde "Code → Download ZIP": ese archivo agrega una carpeta extra y
   Claude no lo reconoce como skill.
2. En Claude: Settings > Capabilities → activar "Code execution and file creation".
3. Customize > Skills → "+" → "Create skill" → "Upload a skill" → elegir `labor-normativa-senasa.zip` (sin
   descomprimir).
4. Usarla escribiendo `/labor-normativa-senasa` al principio del mensaje, o pidiendo la tarea normativa directamente.

## Contenido

```
labor-normativa-senasa/
├── SKILL.md                     instrucciones de la skill
└── references/
    ├── digesto-indice.md        árbol completo del índice temático del Digesto
    ├── cns-indice.md            codificación e índice del Código de Normas SENASA (1999)
    └── fuentes.md               documentos usados para construirla
```

## Requisitos opcionales

- **Conector Firecrawl** en Claude para consultar el Digesto SENASA (la consulta web común falla por el certificado
  del sitio). Sin él, la skill usa un navegador conectado o pide pegar el listado.
- **CNS.pdf** (Código de Normas SENASA, 1999): solo para leer normas antiguas que no estén en el Digesto ni en
  Infoleg. Disponible como *asset* en Releases.

## Personalización

Ver el prompt de personalización en `INSTRUCCIONES.md`.

## Historial

- v1.0 (oct-2026): versión general para la DNSA, con acceso al Digesto vía Firecrawl.

Autor: Alejandro Pérez – Programa de Sanidad Porcina, DNSA – SENASA. Contenido basado en normativa pública.
