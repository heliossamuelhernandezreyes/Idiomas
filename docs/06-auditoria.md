# Auditoría integral del repositorio Idiomas

**Fecha:** 2026-10-30  
**Alcance:** los cinco documentos iniciales de la rama main, la conversación actual del creador y antecedentes recuperados de 2025.  
**Principio:** documentar, contrastar y corregir; **no diseñar un idioma distinto**.

## 1. Hallazgos corregidos

| Hallazgo | Problema previo | Acción efectuada |
|---|---|---|
| Vocabulario histórico omitido | El repositorio decía que *Kron*, *Nan*, *Aru*, *Dore*, etc., solo eran menciones del asistente | Se añadió [antecedentes de 2025](05-antecedentes-2025.md), con atribución histórica, no como canon vigente |
| Pronombres de dos épocas | No se diferenciaban *Shu/Derelem* de *tho/deish* | Se conservan ambos repertorios sin imponer equivalencias |
| Escritura incompleta | Solo constaban consonantes/vocales compuestas | Se añadieron las **tres formas posicionales históricas** y la ausencia de mayúsculas |
| Uso de *-do* | Se presentaba como un único proceso posible | Se documentaron por separado su uso nominal histórico y *akroshdo* progresivo |
| *na/a* mal descritos | Un texto antiguo sugería fonotáctica demasiado estricta | Se prioriza la **elección flexible por agilidad o claridad**, influida ocasionalmente por el contexto precedente |
| Tener | Antes constaba como «no se ha proporcionado» | Registrados *nietch* = «tengo» y *deish jor nietch*, manteniendo el orden verbal como **experimental** |
| Plurales | Se asumía que bastaba un sufijo universal | Se preservó *jor* sin marca de número y la relevancia contextual de *sh* |
| *-il/-hil* | El asistente dedujo erróneamente «akroshil = correré en caso de que» | Se retiró esa conjetura del canon y se preservaron ambas declaraciones literales del creador |
| *na* como número | Homografía ignorada | Se documentó *Na* = uno (histórico) junto a *na/a* artículo (actual), sin inferir etimología |
| *Fam* | Valor histórico doble omitido | Se conserva tanto «nueve» como «mucho» en material histórico |

## 2. Lo establecido directamente en la conversación de 2026

- Grafemas composicionales: consonantes capaces de albergar vocales/auxiliares; *mirenee* («belleza») se escribe con un signo compuesto.
- *Ik/Ih* explicitan identidad; el sujeto se interpreta en referencia al hablante por defecto salvo construcción orientada externamente.
- *Do* pertenece a «hacer», no a «necesitar». Formas registradas *doih, thosdo, deido, doklish, deidos, doas, idof, doal, dail, dahil*.
- *Manih* («necesito»), *manish*, *manal*, *manhil*, *manas*.
- *Akrosh* («correr»), *akroshdo*, *acroshsor*, *akroshdal*, más distintas formas de posibilidad con *-il/-hil* que permanecen ambiguas.
- *Far* se relaciona con incertidumbre; *far'il* y *far'hil* están diferenciados; *freidas* es una construcción modal dirigida a otra persona que funciona con diferentes verbos.
- Familia interrogativa *degosh, degoshco, degoshi, degoshda, degol, deimosh* con uso pragmático contextual.
- *Na/a* artículo indefinido flexible; *na* también puede condensar artículo y predicación en *des na jor*.
- *Jor* tanto humano como humanos; *des* él, *deish* ellos y *sh* relacionada con pluralidad.
- *Nietch* tengo; la construcción *deish jor nietch* se propone, **pero la sintaxis de los verbos está en evaluación**.

## 3. Aspectos NO resueltos (no deben generar formas automáticas)

1. Diferencia precisa entre **-il** y **-hil**, y análisis de la contradicción textual en «akroshil ... akroshhil o akroshil».
2. Reglas de orden de palabras (SOV, SVO, flexibilidad) y concordancia de *nietch*.
3. Alcance y segmentación de *degoshdal, déaio, ihsconateru, serelam, kis lam*.
4. Cuándo *sh* y *ish* expresan plural y qué función tiene *-s* en cada contexto.
5. Alcance de *do* como verbo y de *-do* en palabras distintas de épocas diferentes.
6. Pronunciación precisa, inventario fonológico y grafemas originales no aportados visualmente.
7. Relación entre la numeración histórica y el léxico actual (en particular *Na* y *Fam*).
8. Relación entre pronombres de 2025 y los de 2026.

## 4. Control de calidad editorial

- Toda traducción incluida como **confirmada** fue proporcionada explícitamente por el creador, no inferida por similitud morfológica.
- Todo ejemplo en **experimentación** queda marcado.
- Formas de distintas épocas se conservan sin declararlas sinónimos o errores.
- La expresión «futuro imperfecto» se preserva como terminología del creador, no se equipara automáticamente al tiempo tradicional de otra lengua.
- **La canción** *Ik nam a jor* se documenta por su título y significado confirmados; **no se inventa la letra ni se añade audio al repositorio**.
- El corpus JSON conserva las traducciones individuales, su estatus y sus notas; no se usa para entrenar reglas automáticas todavía.

## 5. Conclusión

La documentación había avanzado, pero estaba dispersa y confundía en varios pasajes las inferencias del analista con los datos del creador. La estructura actual conserva **versión vigente, antecedentes y ambigüedades** por separado, para que nuevas aportaciones corrijan el estado sin borrar la evolución de la lengua.

**Siguiente fase técnica recomendada (no implementada en esta auditoría):** digitalizar muestras originales de los glifos y escribir pruebas de lectura y composición una vez que el creador aporte reglas completas.
