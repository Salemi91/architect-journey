# Architect Journey

Framework de documentación para apoyar la toma de decisiones arquitectónicas, alineación de equipos y adopción de herramientas de Inteligencia Artificial en proyectos de software.

---

## Objetivo

Este repositorio proporciona templates, ejemplos y guías para documentar decisiones técnicas y de negocio de forma estructurada.

Los documentos generados pueden ser utilizados por:

- Arquitectos de Software
- Tech Leads
- Engineering Managers
- Product Managers
- Analistas
- Desarrolladores
- Equipos de IA Generativa

---

## Beneficios

- Alinear equipos humanos.
- Reducir ambigüedad.
- Mejorar estimaciones.
- Servir como contexto estructurado para asistentes de IA.

---

## Flujo de Documentación

```mermaid
flowchart TD

A[Idea / Problema] --> B[PRD]

B --> C{Requiere diseño técnico?}

C -->|No| D[Historias de Usuario]

C -->|Sí| E[RFC]

E --> F{Hay decisión arquitectónica?}

F -->|No| G[Technical Brief]

F -->|Sí| H[ADR]

H --> G

G --> I[Estimación]

I --> J[Historias de Usuario]

J --> K[Implementación]

K --> L[Testing]

L --> M[Deploy]
```
