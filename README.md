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

- Mejor entendimiento del contexto
- Estimaciones más precisas
- Menor dependencia de conocimiento tribal
- Mejor onboarding
- Base documental para IA
- Trazabilidad de decisiones

---

## Flujo de Documentación

```mermaid
flowchart TD

A[Idea o Necesidad] --> B[RFC]

B --> C[ADR]

C --> D[C4]

D --> E[Technical Brief]

E --> F[Estimación]

F --> G[Implementación]

G --> H[Operación]

H --> I[Postmortem]
```

## Roles Participantes

```mermaid
flowchart LR

PM[Product Manager]
BA[Analista]
TL[Tech Lead]
ARCH[Arquitecto]
DEV[Developer]
QA[QA]

PM --> RFC

BA --> RFC

ARCH --> ADR

TL --> ADR

ARCH --> C4

TL --> C4

DEV --> TechnicalBrief

TL --> TechnicalBrief

QA --> Estimación

DEV --> Estimación
```
