# Planificación de Sprints — Proyecto IA CD

> **Repositorio:** `SorenAcevedo/uao_gestion_proyectos_ia_cd`  
> **Metodología:** Scrum académico · 3 sprints  
> **Idioma:** Español

---

## Sprint 1 — Comprensión y Preparación

### Objetivo
Dejar listo el entorno de trabajo, explorar el dataset y preparar los datos para el modelado.

### Tareas
- [ ] Crear repositorio GitHub
- [ ] Configurar entorno virtual (virtualenv / conda)
- [ ] Explorar el dataset (estadísticas descriptivas, visualizaciones iniciales)
- [ ] Separar conjuntos train / test

### Entregables
- Dataset limpio y particionado
- Notebook inicial de exploración (`01_exploracion.ipynb`)
- Repositorio configurado con estructura base

### Criterio de cierre
El repositorio está funcional, el dataset se encuentra limpio y correctamente particionado, y el notebook inicial documenta los hallazgos de la exploración.

---

## Sprint 2 — Modelado y Evaluación

### Objetivo
Entrenar y comparar modelos de clasificación, evaluando su desempeño con métricas estándar.

### Tareas
- [ ] Entrenar modelo de Logistic Regression
- [ ] Entrenar modelo de Random Forest
- [ ] Evaluar Accuracy y F1-score para ambos modelos
- [ ] Generar matriz de confusión por modelo

### Entregables
- Comparación documentada de modelos
- Notebook con métricas y gráficas (`02_modelado.ipynb`)

### Criterio de cierre
Ambos modelos están entrenados, las métricas (Accuracy, F1) están calculadas y documentadas, y las matrices de confusión se encuentran graficadas en el notebook.

---

## Sprint 3 — Despliegue y Documentación

### Objetivo
Persistir el mejor modelo, documentar el proyecto completo y preparar la entrega final.

### Tareas
- [ ] Guardar el modelo final en formato `.joblib`
- [ ] Documentar el proyecto (README profesional, instrucciones de uso)
- [ ] Preparar presentación del proyecto

### Entregables
- Modelo final serializado (`modelo_final.joblib`)
- `README.md` profesional con descripción, instrucciones y resultados
- Material de presentación (slides / informe)

### Criterio de cierre
El modelo final está guardado y es reproducible, el README cubre instalación, uso y resultados, y el material de presentación está listo para la entrega académica.
