# Framework Overview

## Introducción

Los equipos de software generan una gran cantidad de conocimiento durante el ciclo de vida de un producto.

Sin embargo, gran parte de ese conocimiento queda distribuido entre reuniones, chats, tickets, documentos aislados o conversaciones informales.

Esto genera problemas frecuentes:

* Ambigüedad.
* Dependencia de personas específicas.
* Dificultades para estimar.
* Decisiones técnicas sin trazabilidad.
* Pérdida de contexto histórico.
* Baja efectividad al utilizar herramientas de Inteligencia Artificial.

Este framework propone un conjunto de documentos livianos para capturar el contexto necesario en cada etapa del proceso de desarrollo.

---

## Principios

### Documentar solo lo necesario

No todos los cambios requieren todos los documentos.

El objetivo es reducir incertidumbre, no generar burocracia.

---

### Cada documento responde una pregunta distinta

| Documento       | Pregunta principal                                     |
| --------------- | ------------------------------------------------------ |
| PRD             | ¿Qué problema queremos resolver?                       |
| RFC             | ¿Cómo proponemos resolverlo?                           |
| ADR             | ¿Por qué tomamos esta decisión arquitectónica?         |
| Technical Brief | ¿Qué necesitamos saber para implementarlo y estimarlo? |

---

### Los documentos son contexto reutilizable

Los documentos deben poder ser utilizados por:

* Equipos humanos.
* Nuevos integrantes.
* Equipos distribuidos.
* Herramientas de Inteligencia Artificial.

---

## Estrategia de Adopción

### Nivel 1 - Equipos Iniciales

Implementar únicamente:

* PRD
* Technical Brief

Objetivo:

* Mejorar refinamientos.
* Mejorar estimaciones.

---

### Nivel 2 - Equipos en crecimiento

Agregar:

* RFC

Objetivo:

* Alinear decisiones técnicas.
* Reducir retrabajo.

---

### Nivel 3 - Equipos maduros

Agregar:

* ADR
* Diagramas C4

Objetivo:

* Gestionar arquitectura a largo plazo.
* Preservar conocimiento organizacional.

---

## Uso con Inteligencia Artificial

Este framework fue diseñado para que los documentos puedan utilizarse como contexto estructurado para asistentes de IA.

Un modelo de IA puede:

* Generar RFCs a partir de un PRD.
* Generar ADRs a partir de un RFC.
* Generar Technical Briefs.
* Proponer historias de usuario.
* Sugerir casos de prueba.
* Identificar riesgos técnicos.

La calidad de las respuestas dependerá directamente de la calidad del contexto proporcionado.

---

## Visión

El objetivo final no es producir documentos.

El objetivo final es facilitar la toma de decisiones, mejorar la colaboración entre personas y aumentar la efectividad de los equipos apoyados por Inteligencia Artificial.
