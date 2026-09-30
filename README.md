# TRABAJO-DE-ANALISIS-DE-SOFT# 🌊 Plataforma Educativa sobre Conservación Marina (Ocean Literacy)

Repositorio oficial del proyecto de software desarrollado para la comunidad universitaria de la **Universidad Continental (Campus Huancayo)**. Esta plataforma web interactiva y responsiva tiene como objetivo promover la cultura oceánica (*Ocean Literacy*), difundir eventos ambientales y evaluar conocimientos mediante cuestionarios gamificados con tablas de clasificación[cite: 3].

---

## 🎯 Alineación con los Objetivos de Desarrollo Sostenible (ODS)
El proyecto se fundamenta en el **ODS 14: Vida Submarina**, abordando de forma didáctica e interactiva[cite: 3]:
* **Meta 14.1:** Prevención y reducción de la contaminación marina de origen terrestre[cite: 3].
* **Meta 14.2:** Protección y gestión sostenible de los ecosistemas marinos y costeros[cite: 3].
* **Meta 14.3:** Sensibilización sobre los impactos de la acidificación de los océanos[cite: 3].

---

## 👥 Integrantes del Equipo y Asignación de Módulos

El proyecto sigue una distribución modular de punta a punta para asegurar la trazabilidad del trabajo y la contribución técnica individual:

| Integrante | Rol / Módulo Asignado | Alcance Funcional | Artefactos y Diagramas a Cargo |
| :--- | :--- | :--- | :--- |
| **James Jeyson Quispe Sulca** | **Módulo 3: Quizzes y Ranking** | RF-08 al RF-12 (Prácticas, cuestionario evaluativo y tabla de clasificación)[cite: 3] | Diagrama de Casos de Uso (Quizzes), Diagrama de Actividad / Procesos (Evaluación y ranking) y Modelo E-R (Entidades asociadas)[cite: 1, 3, 4]. |
| **[Nombre Integrante 2]** | **Módulo 1: Boletines y Divulgación** | RF-01 al RF-03 (Búsqueda, lectura y gestión editorial)[cite: 3] | Diagrama de Casos de Uso (Boletines), Diagrama de Procesos (Validación científica RD-01) y Modelo E-R (Entidades asociadas)[cite: 1, 3, 4]. |
| **[Nombre Integrante 3]** | **Módulo 2: Agenda y Autenticación** | RF-04 al RF-07 (Calendario de eventos, inicio de sesión y control de roles)[cite: 3] | Diagrama de Casos de Uso (Auth/Agenda), Diagrama de Secuencia (Login y control de acceso) y Modelo E-R (Entidades asociadas)[cite: 1, 3, 4]. |

---

## 🛠️ Metodología y Gestión del Proyecto

* **Marco de Trabajo:** Scrum combinado con desarrollo incremental[cite: 1, 3].
* **Gestión de Tareas:** Tablero Scrum en **Jira Software** con seguimiento de historias de usuario, sprints y gráficos burndown.
  * 🔗 *[Pega aquí el enlace público o institucional a tu tablero de Jira]*
* **Herramientas de Modelado:** Visual Paradigm (UML 2.5 y Modelo Entidad-Relación en notación Crow's Foot)[cite: 1].
* **Control de Versiones:** Git y GitHub con flujo de trabajo basado en ramas temáticas (`feature/...`) e integración mediante *Pull Requests*.

---

## 📂 Estructura del Repositorio

```text
├── README.md                           # Documentación principal del repositorio
├── docs/                               # Entregables formales de ingeniería
│   ├── informe/                        # Informe técnico del avance (EV02)
│   ├── capturas-jira/                  # Evidencias del sprint, backlog y burndown chart
│   │   ├── sprint_activo.png
│   │   └── burndown_chart.png
│   └── diagramas/                      # Diagramas UML y Modelo E-R (PNG y fuentes .vpp)
│       ├── modelo_er_general.png
│       ├── casos_uso_general.png
│       └── modelado_procesos_evaluacion.png
└── src/                                # Código fuente de la plataforma web
    ├── assets/                         # Estilos (CSS), componentes gráficos e imágenes
    ├── components/                     # Componentes modulares de interfaz
    └── index.html                      # Punto de entrada de la aplicación
