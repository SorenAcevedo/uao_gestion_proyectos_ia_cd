# 🫘 Clasificación de Variedades de Frijol Seco
### Machine Learning con CRISP-DM + TDSP + Scrum ML

Este repositorio contiene el desarrollo del laboratorio práctico de clasificación de granos de frijol seco utilizando el **Dry Bean Dataset**. El proyecto simula un escenario profesional donde una empresa agrícola busca automatizar su control de calidad mediante visión por computadora y modelos predictivos.

---

## 👥 Organización del Equipo (Scrum ML)
El equipo de trabajo está estructurado bajo roles específicos para asegurar la agilidad y el valor del producto:

| Rol | Responsable | Responsabilidades | Entregables Clave |
| :--- | :--- | :--- | :--- |
| **Product Owner** | Juan José Bonilla Pinzón | Define objetivos y prioriza el valor del modelo. | Historias de usuario y validación final. |
| **Scrum Master** | Soren Fabricius Acevedo Azuero | Coordina el flujo de trabajo y facilita el proceso. | Seguimiento del Sprint y tablero Scrum. |
| **Data Engineer / Analyst** | Ricardo Muñoz Bocanegra | Exploración, limpieza y preparación de datos. | Dataset procesado y análisis exploratorio (EDA). |
| **ML Engineer** | Nicolas Lozano | Entrenamiento, evaluación y optimización de modelos. | Modelos entrenados y reporte de métricas. |

---

## 📁 Estructura del Proyecto (TDSP)
Siguiendo el estándar **Team Data Science Process**, el repositorio se organiza para garantizar la reproducibilidad y el versionado:

```text
laboratorio_drybean_ml/
├── data/
│   ├── raw/          # Datos originales sin modificar.
│   └── processed/    # Datos limpios y transformados.
├── notebooks/        # Notebooks de exploración y experimentación.
├── outputs/          # Artefactos generados.
│   ├── models/       # Modelos entrenados (.joblib).
│   └── reports/      # Métricas, gráficas y reportes técnicos.
├── src/              # Código fuente y scripts reutilizables.
├── requirements.txt  # Dependencias del proyecto.
├── README.md         # Instrucciones y documentación.
└── .gitignore        # Archivos excluidos del control de versiones.
```

## 📅 Planeación de Sprints
El proyecto se ejecuta en tres ciclos cortos orientados a resultados:

### Sprint 1: Comprensión y Preparación
**Tareas:** Crear repositorio, configurar entorno virtual, explorar dataset y separar Train/Test.
**Entregables:** Dataset limpio, Notebook inicial y repositorio configurado.

### Sprint 2: Modelado y Evaluación
**Tareas:** Entrenar Baseline (Regresión Logística), entrenar Random Forest y evaluar métricas (Accuracy, F1, Matriz de Confusión).
**Entregables:** Comparación de modelos y gráficas de rendimiento

### Sprint 3: Despliegue y Documentación
**Tareas:** Exportar modelo final (`.joblib`), documentar resultados y preparar presentación final.
**Entregables:** Modelo productivo y README profesional.

El tablero de planeación y ejecución de las tareas se puede consultar en el siguiente enlace: https://github.com/users/SorenAcevedo/projects/2/views/3

## 💻 Flujo de Trabajo (Git & GitHub)
Para mantener la integridad del código, se sigue este flujo colaborativo basado en buenas prácticas de ingeniería de datos:

1. **Inicialización:** Un integrante crea el repositorio en GitHub e inicializa la estructura TDSP base.
2. **Ramas (Branches):** Cada integrante trabaja en ramas `feature/` específicas para mantener el código organizado y trazable.
3. **Pull Requests (PR):** Los cambios se suben a GitHub y se solicita una revisión técnica antes de integrarlos al proyecto principal.
4. **Merge:** Tras la revisión y aprobación, el código se integra a la rama `main` cumpliendo con la *Definition of Done*.
