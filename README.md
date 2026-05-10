# SASE — Sistema de Atención a Estudiantes

> Proyecto integrador — Ingeniería de Software (SIS021) | IX Ciclo | Plan 2025 | Semestre 2026-I  
> Universidad Andina del Cusco — Escuela Profesional de Ingeniería de Sistemas  
> Docente: Dr. Lornel Antonio Rivas Mago

---

## Descripción del sistema

El **Sistema de Atención a Estudiantes (SASE)** centraliza el registro, priorización y canalización de solicitudes de apoyo académico, administrativo y de otra índole de la Escuela Profesional de Ingeniería de Sistemas. Permite al estudiante hacer seguimiento en tiempo real del estado de su solicitud, reduciendo los tiempos de respuesta y mejorando la calidad del servicio de atención.

---

## Equipo — Equipo Delta

| Código | Integrante | Rol Scrum | Responsabilidad principal |
|--------|-----------|-----------|--------------------------|
| AM | Ana Mamani Quispe | Product Owner | Define y prioriza el backlog. Representa las necesidades de los usuarios. |
| CR | Carlos Ríos Huanca | Scrum Master | Facilita eventos Scrum. Revisa y aprueba Pull Requests a develop. |
| LT | Lucía Ttito Ccari | Desarrollador | Análisis de requisitos y diseño. Épicas 1 y 2. |
| JP | Jorge Palomino Vargas | Desarrollador | Diseño de interfaces y gestión del repositorio. Épicas 3 y 4. |

---

## Estructura del repositorio

```
SASE-SIS021-2026/
├── docs/                          # Entregables de las actividades
│   ├── Act1-1_Caracterizacion.pdf
│   ├── Act1-2_ProcesoDeSarrollo.pdf
│   ├── Act1-3_Backlog.pdf
│   ├── Act2-1_EspecificacionRequisitos.pdf
│   ├── Act2-2_ModelosUML.pdf
│   ├── Act2-3_DisenoArquitectonico.pdf
│   ├── Act3-1_PlanDeProyecto.pdf
│   └── Act3-2_PlanDeCalidad.pdf
├── modelos/                       # Archivos fuente de diagramas UML
│   ├── diagrama_contexto.drawio
│   ├── diagrama_casos_uso.drawio
│   ├── diagrama_clases.drawio
│   └── diagrama_estados.drawio
├── planificacion/                 # Plan de proyecto y calidad
│   ├── plan_proyecto.pdf
│   └── plan_calidad.pdf
└── README.md
```

---

## Estrategia de ramas

| Rama | Propósito |
|------|-----------|
| `main` | Versiones estables entregadas al docente |
| `develop` | Integración del trabajo antes de pasar a main |
| `feature/HU##-nombre` | Trabajo en progreso por historia de usuario o actividad |

**Flujo:** `feature/...` → Pull Request → `develop` → merge a `main` al entregar

**Convención de commits:**
```
HU01: descripción corta del cambio
Act2-2: versión final modelos UML
docs: agrega plan de proyecto v1
```

---

## Backlog del producto

10 historias de usuario organizadas en 4 épicas | 35 story points

| Épica | Historias |
|-------|-----------|
| 1 — Gestión de Solicitudes | HU01, HU02, HU03 |
| 2 — Clasificación y Enrutamiento | HU04, HU05 |
| 3 — Atención por Unidades | HU06, HU07, HU08 |
| 4 — Administración y Reportes | HU09, HU10 |

Backlog completo gestionado en Jira.

---

## Actores del sistema

| Actor | Tipo | Función principal |
|-------|------|------------------|
| Estudiante | Primario | Registra solicitudes y consulta su estado |
| Operador Administrativo | Primario | Clasifica y deriva solicitudes |
| Personal de Unidad | Primario | Atiende y resuelve solicitudes |
| Director de Escuela | Secundario | Consulta reportes |
| Administrador del Sistema | Secundario | Gestiona usuarios y roles |

---

## Metodología

Marco de desarrollo: **Scrum**  
Herramientas: Jira (backlog y tablero), Miro (modelado colaborativo), GitHub (control de versiones), draw.io (diagramas UML)

---

## Historial de entregas

| Actividad | Descripción | Fecha entrega | Estado |
|-----------|-------------|---------------|--------|
| Act 1.1 | Caracterización del software | 15-16 sep 2026 | ✓ Entregado |
| Act 1.2 | Proceso de desarrollo | 15-16 sep 2026 | ✓ Entregado |
| Act 1.3 | Backlog de producto | 15-16 sep 2026 | ✓ Entregado |
| Act 2.1 | Especificación de requisitos | 03-04 nov 2026 | ✓ Entregado |
| Act 2.2 | Modelos UML | 03-04 nov 2026 | ✓ Entregado |
| Act 2.3 | Diseño arquitectónico | 03-04 nov 2026 | ✓ Entregado |
| Act 3.1 | Plan de proyecto | 20-21 dic 2026 | ⏳ Pendiente |
| Act 3.2 | Plan de calidad | 20-21 dic 2026 | ⏳ Pendiente |
| Act 3.3 | Análisis sociotécnico | 20-21 dic 2026 | ⏳ Pendiente |

---

*SIS021 — Ingeniería de Software | Universidad Andina del Cusco | 2026-I*
