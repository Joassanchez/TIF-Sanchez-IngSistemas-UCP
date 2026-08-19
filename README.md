# PFG — LLMOps aplicado a sistemas RAG

Arquitectura basada en evaluación híbrida para la detección de drift semántico
y actualización de bases vectoriales.

**Estudiante:** Sánchez, Joaquín Sebastián — DNI 45.452.416
**Carrera:** Ingeniería en Sistemas de la Información — UCP Sede Posadas, Comisión A
**Cátedra:** Proyecto Final de Grado
**Docente:** PosDr. Darío Ezequiel Díaz

## Qué es este proyecto

Sistema RAG con una capa LLMOps que supervisa continuamente la calidad de las
respuestas y detecta cuándo el conocimiento de la base vectorial pierde
vigencia (aunque el sistema siga respondiendo con coherencia lingüística).
Ante degradación detectada, orquesta la actualización controlada del
conocimiento, con validación humana previa a producción (human-in-the-loop).

Entorno de validación: corpus normativo (Boletín Oficial), elegido por su
alta tasa de cambio y por exponer metadatos de vigencia/derogación.

## Estructura del repositorio

```
00-gestion/       Bitácora, anexos, actas, seguimiento del proyecto
01-relevamiento/  Entrevistas, encuestas, datos de campo con organizaciones reales
02-analisis/      Estado del arte, benchmarking, análisis de mercado
03-requisitos/    Requisitos funcionales/no funcionales, trazabilidad (fuente única de verdad)
04-diseno/        Arquitectura, modelo de datos, diagramas
05-entregas/      Versiones formales del informe, entregadas a la cátedra
src/              Código fuente del sistema
```

## Convención de nombres de archivo

```
AAAAMMDD_TipoDocumento_Equipo_vN.ext
```
Ejemplo: `20260818_AvanceProyecto_Sanchez_v1.pdf`

## Estado actual

Ver `00-gestion/bitacora.md` y `00-gestion/anexo-III.md`.

Referencia normativa: Dictamen Técnico-Pedagógico N.º 03/2026 (18/08/2026).
