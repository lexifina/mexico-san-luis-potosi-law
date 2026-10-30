# San Luis Potosí: law history in git

The law of the State of San Luis Potosí (Estado Libre y Soberano de San Luis Potosí, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-slp/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

79 ordenamientos with 1491 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE SAN LUIS POTOSI | 152 | as first published, then each reform: 5 January 1918 to 29 September 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE SAN LUIS POTOSI | 77 | as first published, then each reform: 15 April 1947 to 10 October 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE SAN LUIS POTOSI | 66 | as first published, then each reform: 22 June 1947 to 13 November 2019 |
| `codigo-familiar/` | CODIGO FAMILIAR PARA EL ESTADO DE SAN LUIS POTOSI | 51 | as first published, then each reform: 18 March 2009 to 22 October 2026 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE SAN LUIS POTOSI | 13 | as first published, then each reform: 4 September 1999 to 25 December 2025 |
| `codigo-penal/` | CODIGO PENAL DEL ESTADO DE SAN LUIS POTOSI | 121 | as first published, then each reform: 2 October 2014 to 2 August 2026 |
| `codigo-procesal-administrativo/` | CODIGO PROCESAL ADMINISTRATIVO PARA EL ESTADO DE SAN LUIS POTOSI | 6 | as first published, then each reform: 21 July 2017 to 19 September 2024 |
| `ley-agricola/` | LEY AGRICOLA PARA EL ESTADO DE SAN LUIS POTOSI | 6 | as first published, then each reform: 6 August 2021 to 4 March 2026 |
| `ley-ambiental/` | LEY AMBIENTAL DEL ESTADO DE SAN LUIS POTOSI | 78 | as first published, then each reform: 18 December 1999 to 25 June 2026 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE SAN LUIS POTOSI | 27 | as first published, then each reform: 26 November 2019 to 25 June 2026 |
| `ley-de-adquisiciones/` | LEY DE ADQUISICIONES DEL ESTADO DE SAN LUIS POTOSI | 18 | as first published, then each reform: 30 January 1997 to 30 April 2026 |
| `ley-de-aguas/` | LEY DE AGUAS PARA EL ESTADO DE SAN LUIS POTOSI | 63 | as first published, then each reform: 22 January 2006 to 15 May 2026 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE SAN LUIS POTOSI | 4 | as first published, then each reform: 20 June 2020 to 10 June 2024 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL PARA EL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 4 | as first published, then each reform: 21 December 2021 to 3 October 2025 |
| `ley-de-asociaciones-publico-privadas-en-proyectos-para-la-pr/` | LEY DE ASOCIACIONES PUBLICO-PRIVADAS EN PROYECTOS PARA LA PRESTACION DE SERVICIOS DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 10 | as first published, then each reform: 13 June 2012 to 17 June 2024 |
| `ley-de-atencion-a-victimas/` | LEY DE ATENCION A VICTIMAS PARA EL ESTADO DE SAN LUIS POTOSI | 10 | as first published, then each reform: 29 July 2017 to 17 June 2024 |
| `ley-de-atencion-y-apoyo-a-migrantes/` | LEY DE ATENCION Y APOYO A MIGRANTES DEL ESTADO DE SAN LUIS POTOSI | 9 | as first published, then each reform: 14 July 2018 to 4 July 2025 |
| `ley-de-bebidas-alcoholicas/` | LEY DE BEBIDAS ALCOHOLICAS DEL ESTADO DE SAN LUIS POTOSI | 13 | as first published, then each reform: 20 March 2015 to 5 September 2024 |
| `ley-de-bibliotecas/` | LEY DE BIBLIOTECAS DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 5 | as first published, then each reform: 14 September 2012 to 25 May 2018 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 16 | as first published, then each reform: 13 January 2006 to 15 November 2025 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO DE SAN LUIS POTOSI | 14 | as first published, then each reform: 28 August 2015 to 3 October 2025 |
| `ley-de-centros-de-educacion-inicial-y-cuidado-infantil/` | LEY DE CENTROS DE EDUCACION INICIAL Y CUIDADO INFANTIL DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 5 | as first published, then each reform: 7 October 2012 to 7 January 2026 |
| `ley-de-certeza-patrimonial-y-vivienda-social/` | LEY DE CERTEZA PATRIMONIAL Y VIVIENDA SOCIAL DEL ESTADO DE SAN LUIS POTOSI | 1 | as first published: 14 October 2023 |
| `ley-de-ciencia-y-tecnologia/` | LEY DE CIENCIA Y TECNOLOGIA DEL ESTADO DE SAN LUIS POTOSI | 11 | as first published, then each reform: 31 August 2003 to 15 April 2023 |
| `ley-de-comunicacion-social/` | LEY DE COMUNICACION SOCIAL PARA EL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 3 | as first published, then each reform: 23 May 2021 to 2 September 2023 |
| `ley-de-consulta-indigena/` | LEY DE CONSULTA INDIGENA PARA EL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 4 | as first published, then each reform: 7 August 2010 to 22 March 2025 |
| `ley-de-control-de-confianza/` | LEY DE CONTROL DE CONFIANZA DEL ESTADO DE SAN LUIS POTOSI | 3 | as first published, then each reform: 2 October 2018 to 30 June 2026 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 5 | as first published, then each reform: 1 January 2024 to 11 November 2025 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE SAN LUIS POTOSI | 11 | as first published, then each reform: 15 December 2017 to 26 March 2026 |
| `ley-de-cultura/` | LEY DE CULTURA PARA EL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 14 | as first published, then each reform: 11 May 2008 to 13 February 2026 |
| `ley-de-defensoria-social-y-de-oficio/` | LEY DE DEFENSORIA SOCIAL Y DE OFICIO DEL ESTADO DE SAN LUIS POTOSI -ANTES LEY DE DEFENSORIA SOCIAL DEL ESTADO DE SAN LUIS POTOSI- | 3 | as first published, then each reform: 7 August 1999 to 15 September 2006 |
| `ley-de-derechos-linguisticos/` | LEY DE DERECHOS LINGÜISTICOS PARA EL ESTADO DE SAN LUIS POTOSI | 1 | as first published: 6 December 2025 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 29 | as first published, then each reform: 18 April 2008 to 9 June 2026 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 8 | as first published, then each reform: 7 October 2016 to 14 March 2024 |
| `ley-de-donacion-y-trasplantes/` | LEY DE DONACION Y TRASPLANTES PARA EL ESTADO DE SAN LUIS POTOSI -ANTES LEY DE DONACION Y TRASPLANTES DE ORGANOS, TEJIDOS Y CELULAS PARA EL ESTADO DE SAN LUIS POTOSI -ANTES LEY DE DONACION Y TRASPLANTES DE ORGANOS, TEJIDOS Y COMPONENTES PARA EL ESTADO DE SAN LUIS POTOSI- | 8 | as first published, then each reform: 26 March 2014 to 8 January 2026 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE SAN LUIS POTOSI | 22 | as first published, then each reform: 15 May 2020 to 22 October 2026 |
| `ley-de-expropiacion-ocupacion-temporal-y-limitacion-del-domi/` | LEY DE EXPROPIACION, OCUPACION TEMPORAL Y LIMITACION DEL DOMINIO POR CAUSA DE UTILIDAD PUBLICA PARA EL ESTADO DE SAN LUIS POTOSI | 1 | as first published: 7 October 2012 |
| `ley-de-fiscalizacion-superior/` | LEY DE FISCALIZACION SUPERIOR DEL ESTADO DE SAN LUIS POTOSI | 2 | as first published, then each reform: 2 September 2023 to 12 September 2024 |
| `ley-de-fomento-artesanal/` | LEY DE FOMENTO ARTESANAL DEL ESTADO DE SAN LUIS POTOSI | 10 | as first published, then each reform: 25 May 2003 to 15 October 2025 |
| `ley-de-fomento-para-el-desarrollo-forestal-sustentable/` | LEY DE FOMENTO PARA EL DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE SAN LUIS POTOSI | 11 | as first published, then each reform: 19 October 2005 to 26 March 2026 |
| `ley-de-fomento-para-la-lectura-y-el-libro/` | LEY DE FOMENTO PARA LA LECTURA Y EL LIBRO, DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 7 | as first published, then each reform: 19 December 2008 to 10 October 2026 |
| `ley-de-fomento-y-proteccion-del-maiz-criollo-en-el-estado-de/` | LEY DE FOMENTO Y PROTECCION DEL MAIZ CRIOLLO EN EL ESTADO DE SAN LUIS POTOSI | 1 | as first published: 5 October 2018 |
| `ley-de-ganaderia/` | LEY DE GANADERIA DEL ESTADO DE SAN LUIS POTOSI | 12 | as first published, then each reform: 21 May 2017 to 5 June 2026 |
| `ley-de-hacienda/` | LEY DE HACIENDA PARA EL ESTADO DE SAN LUIS POTOSI | 52 | as first published, then each reform: 1 January 1999 to 30 January 2026 |
| `ley-de-hacienda-para-los-municipios-de-san-luis-potosi/` | LEY DE HACIENDA PARA LOS MUNICIPIOS DE SAN LUIS POTOSI | 16 | as first published, then each reform: 7 November 2001 to 15 March 2023 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE SAN LUIS POTOSI PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 27 December 2025 |
| `ley-de-ingresos-para-el-municipio-de-villa-de-arriaga-san-lu/` | LEY DE INGRESOS PARA EL MUNICIPIO DE VILLA DE ARRIAGA, SAN LUIS POTOSI, EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-villa-de-reyes-san-luis/` | LEY DE INGRESOS PARA EL MUNICIPIO DE VILLA DE REYES, SAN LUIS POTOSI, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 2 January 2026 |
| `ley-de-ingresos-para-el-municipio-de-zaragoza-san-luis-potos/` | LEY DE INGRESOS PARA EL MUNICIPIO DE ZARAGOZA, SAN LUIS POTOSI, EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-instituciones-de-desarrollo-humano-y-de-bienestar-soc/` | LEY DE INSTITUCIONES DE DESARROLLO HUMANO Y DE BIENESTAR SOCIAL PARA EL ESTADO DE SAN LUIS POTOSI | 4 | as first published, then each reform: 4 December 2002 to 25 October 2020 |
| `ley-de-juicio-politico/` | LEY DE JUICIO POLITICO DEL ESTADO DE SAN LUIS POTOSI | 7 | as first published, then each reform: 17 April 2019 to 16 April 2026 |
| `ley-de-juntas-de-participacion-ciudadana/` | LEY DE JUNTAS DE PARTICIPACION CIUDADANA DEL ESTADO DE SAN LUIS POTOSI | 6 | as first published, then each reform: 2 December 2021 to 1 April 2026 |
| `ley-de-justicia-electoral/` | LEY DE JUSTICIA ELECTORAL PARA EL ESTADO DE SAN LUIS POTOSI | 5 | as first published, then each reform: 16 June 2020 to 30 June 2026 |
| `ley-de-justicia-indigena-y-comunitaria/` | LEY DE JUSTICIA INDIGENA Y COMUNITARIA PARA EL ESTADO DE SAN LUIS POTOSI | 3 | as first published, then each reform: 2 October 2014 to 10 October 2025 |
| `ley-de-la-comision-estatal-de-derechos-humanos/` | LEY DE LA COMISION ESTATAL DE DERECHOS HUMANOS DEL ESTADO DE SAN LUIS POTOSI | 38 | as first published, then each reform: 18 December 2009 to 31 October 2025 |
| `ley-de-la-defensoria-publica/` | LEY DE LA DEFENSORIA PUBLICA DEL ESTADO DE SAN LUIS POTOSI | 6 | as first published, then each reform: 20 September 2014 to 25 May 2025 |
| `ley-de-la-persona-joven/` | LEY DE LA PERSONA JOVEN PARA EL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 15 | as first published, then each reform: 21 October 2012 to 9 October 2026 |
| `ley-de-lactancia-materna/` | LEY DE LACTANCIA MATERNA PARA EL ESTADO DE SAN LUIS POTOSI | 1 | as first published: 31 October 2025 |
| `ley-de-las-personas-adultas-mayores/` | LEY DE LAS PERSONAS ADULTAS MAYORES PARA EL ESTADO Y LOS MUNICIPIOS DE SAN LUIS POTOSI | 32 | as first published, then each reform: 8 August 2007 to 1 May 2026 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE SAN LUIS POTOSI | 28 | as first published, then each reform: 25 November 2017 to 27 June 2026 |
| `ley-de-los-trabajadores-al-servicio-de-las-instituciones-pub/` | LEY DE LOS TRABAJADORES AL SERVICIO DE LAS INSTITUCIONES PUBLICAS DEL ESTADO DE SAN LUIS POTOSI | 50 | as first published, then each reform: 9 January 1996 to 26 March 2026 |
| `ley-de-mecanismos-alternativos-de-solucion-de-controversias/` | LEY DE MECANISMOS ALTERNATIVOS DE SOLUCION DE CONTROVERSIAS EN MATERIA PENAL PARA EL ESTADO DE SAN LUIS POTOSI | 2 | as first published, then each reform: 29 April 2014 to 5 June 2015 |
| `ley-de-mediacion-y-conciliacion/` | LEY DE MEDIACION Y CONCILIACION PARA EL ESTADO DE SAN LUIS POTOSI | 7 | as first published, then each reform: 16 April 2014 to 12 September 2023 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS DEL ESTADO DE SAN LUIS POTOSI | 19 | as first published, then each reform: 27 October 2013 to 6 July 2024 |
| `ley-de-ordenamiento-territorial-y-desarrollo-urbano/` | LEY DE ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE SAN LUIS POTOSI | 27 | as first published, then each reform: 18 July 2018 to 2 July 2026 |
| `ley-de-pensiones-y-prestaciones-sociales-para-los-trabajador/` | LEY DE PENSIONES Y PRESTACIONES SOCIALES PARA LOS TRABAJADORES AL SERVICIO DEL ESTADO DE SAN LUIS POTOSI | 22 | as first published, then each reform: 22 May 2001 to 17 March 2026 |
| `ley-de-peritos/` | LEY DE PERITOS DEL ESTADO DE SAN LUIS POTOSI | 5 | as first published, then each reform: 23 October 2012 to 21 October 2020 |
| `ley-de-planeacion/` | LEY DE PLANEACION DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 11 | as first published, then each reform: 1 January 2002 to 1 April 2026 |
| `ley-de-presupuesto-y-responsabilidad-hacendaria/` | LEY DE PRESUPUESTO Y RESPONSABILIDAD HACENDARIA DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 22 | as first published, then each reform: 4 March 2016 to 17 April 2026 |
| `ley-de-prevencion-y-atencion-de-la-violencia-familiar/` | LEY DE PREVENCION Y ATENCION DE LA VIOLENCIA FAMILIAR DEL ESTADO DE SAN LUIS POTOSI | 9 | as first published, then each reform: 8 October 2007 to 24 June 2025 |
| `ley-de-prevencion-y-seguridad-escolar/` | LEY DE PREVENCION Y SEGURIDAD ESCOLAR DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 13 | as first published, then each reform: 13 October 2013 to 13 June 2026 |
| `ley-de-proteccion-a-los-animales/` | LEY DE PROTECCION A LOS ANIMALES PARA EL ESTADO DE SAN LUIS POTOSI | 17 | as first published, then each reform: 24 March 2021 to 29 May 2026 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-los-suj/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE LOS SUJETOS OBLIGADOS DEL ESTADO DE SAN LUIS POTOSI -ANTES LEY DE PROTECCION DE DATOS PERSONALES DEL ESTADO DE SAN LUIS POTOSI- | 6 | as first published, then each reform: 20 July 2017 to 11 April 2024 |
| `ley-de-proteccion-del-patrimonio-cultural/` | LEY DE PROTECCION DEL PATRIMONIO CULTURAL PARA EL ESTADO DE SAN LUIS POTOSI | 10 | as first published, then each reform: 31 July 2005 to 30 September 2023 |
| `ley-de-proteccion-y-conservacion-de-arboles-urbanos/` | LEY DE PROTECCION Y CONSERVACION DE ARBOLES URBANOS DEL ESTADO DE SAN LUIS POTOSI | 9 | as first published, then each reform: 18 November 2015 to 9 October 2026 |
| `ley-de-referendum-y-plebiscito/` | LEY DE REFERENDUM Y PLEBISCITO DEL ESTADO DE SAN LUIS POTOSI | 3 | as first published, then each reform: 11 May 2008 to 25 May 2014 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 5 | as first published, then each reform: 24 December 2004 to 28 December 2019 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS PARA EL ESTADO Y MUNICIPIOS DE SAN LUIS POTOSI | 14 | oldest version available, then each reform: 6 June 2017 to 26 March 2026 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE SAN LUIS POTOSI | 88 | as first published, then each reform: 7 January 2005 to 12 October 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
