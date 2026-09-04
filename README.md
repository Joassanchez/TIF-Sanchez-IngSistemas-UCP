# Plataforma local de configuración efectiva y procedencia

Repositorio del Proyecto Integrador Final de la carrera de Ingeniería en Sistemas de Información.

**Autor:** Sánchez, Joaquín Sebastián
**Universidad:** Universidad de la Cuenca del Plata — Facultad de Ingeniería, Tecnología y Arquitectura
**Cátedra:** Proyecto Final de Grado · Comisión A · Sede Posadas
**Docente titular:** PosDr. Darío Ezequiel Díaz
**Ciclo:** 2026

---

## De qué se trata

Las herramientas de agentes de programación arman la configuración que rige sobre el entorno a partir de ocho orígenes con precedencia entre sí, y ninguna informa de cuál de ellos sale cada valor vigente. Un archivo escrito con toda corrección puede quedar descartado en silencio, y hay permisos activos sobre un agente que ninguna declaración del usuario origina.

**Rige** es una plataforma de escritorio, local y de usuario único, que lee los archivos nativos sin sustituirlos y responde tres preguntas que hoy no tienen dónde consultarse:

- qué valor rige sobre cada elemento del ecosistema —agentes, skills, comandos, complementos y servidores de contexto—;
- qué archivo lo determina;
- qué quedó descartado.

Verifica además que cada elemento esté bien formado y que sus referencias resuelvan, y permite modificar un valor informando de antemano el archivo de destino y el efecto previsto.

**Herramienta de referencia:** OpenCode v1.18.25, congelada durante todo el desarrollo. Todo el conocimiento específico del producto se concentra en un adaptador único.

---

## Estructura del repositorio

```
00-gestion/          Bitácora, Anexo III y documentos de gestión del proyecto
01-relevamiento/     Evidencia cruda del relevamiento: instrumentos, registros y capturas
02-analisis/         Cálculo de indicadores y herramientas de análisis del entorno
03-requisitos/       Objetivos, criterio de éxito, requisitos y exclusiones declaradas
04-diseno/           Prototipo v0 y arquitectura de la solución
05-entregas/         Entregables presentados a la cátedra, en PDF
src/                 Código fuente de la plataforma
```

### 00-gestion

| Archivo | Contenido |
|---|---|
| `anexo-III.md` | Bitácora de decisiones por materia: alternativas evaluadas y criterio de descarte |
| `bitacora-individual.pdf` | Bitácora Individual de Proceso y Decisiones, por jornada |
| `acta-constitucion.pdf` | Acta de constitución del equipo |
| `tablero.md` | Enlace al tablero de gestión |

### 01-relevamiento

| Subcarpeta | Contenido |
|---|---|
| `instrumentos/` | Instrumento de casos forma A, protocolo de aplicación, planilla de registro y cláusula de consentimiento |
| `entorno-virtual/` | Configuración plantada del entorno controlado, de composición conocida |
| `medicion/` | Registro de las 64 observaciones sobre 8 sujetos y transcripciones de las respuestas |
| `entrevista/` | Guion aplicado y notas de la entrevista al referente |
| `documentacion/` | Copias locales del esquema publicado y de las tres páginas de documentación |
| `relevamiento-tecnico/` | Capturas numeradas de comandos y salidas, `manifiesto.csv` y `analizar-config.ps1` |
| `estado-del-arte/` | Registro de la búsqueda y capturas de los seis productos relevados |

### 02-analisis

Cálculo de los indicadores IB-1, IB-2 e IB-3, con el tratamiento de la censura por la derecha. Plantillas de análisis del entorno: PESTEL, cinco fuerzas, cadena de valor y FODA.

### 03-requisitos

Objetivos específicos OE-1 a OE-4 con su indicador de verificación, criterio de éxito derivado de la línea de base, requisitos funcionales y no funcionales, y exclusiones declaradas EX-1 a EX-6.

### 04-diseno

Prototipo v0 como maqueta navegable de baja fidelidad, constancia de su validación con el referente, y descripción de los siete componentes funcionales.

### 05-entregas

Entregables presentados a la cátedra. Nomenclatura: `AAAAMMDD_Concepto_Apellido_vN.ext`.

| Archivo | Instancia |
|---|---|
| `20260818_AvanceProyecto_Sanchez_v1.pdf` | Avance de proyecto |
| `20260903_AE1_Sanchez_v1.pdf` | Actividad de Evaluación N.º 1 — Resumen y Capítulos I y II |

### src

Código fuente de la plataforma. El desarrollo comienza después de la AE2; la versión funcional está prevista para noviembre de 2026.

---

## Estado

| Instancia | Contenido | Estado |
|---|---|---|
| AE1 | Resumen, Capítulo I y Capítulo II | Entregada |
| AE2 | Capítulos III y IV | En curso |
| AE3 | — | Pendiente |
| AE4 | — | Pendiente |
| Versión funcional | Adaptador completo sobre OpenCode | Noviembre de 2026 |

---

## Línea de base

Medición propia sobre ocho desarrolladores, entre el 24 y el 31 de agosto de 2026, con un instrumento de ocho casos de composición conocida y un límite de observación de 300 segundos por caso.

| Indicador | Valor |
|---|---|
| IB-1 · Tiempo de resolución (mediana) | 109 s · RIC 48–223 |
| IB-2 · Respuestas incorrectas | 45,1 % sobre casos resueltos |
| IB-3 · Archivos abiertos por consulta (mediana) | 3 |

Observaciones: 64. El costo se reparte de manera despareja: un valor declarado en un único origen se resuelve en 26 s, mientras que un valor vigente sin declaración del usuario supera el límite de observación en 10 de 16 intentos y no registra un solo acierto.

---

## Licencia

Trabajo académico. Todos los derechos reservados por el autor.
