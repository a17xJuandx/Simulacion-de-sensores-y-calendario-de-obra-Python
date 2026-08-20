# Programación de Computadores en Python
## Proyecto Final: Simulación de Sensores y Calendario de Obra
#### Universidad Nacional de Colombia[cite: 9]

---

Este repositorio contiene la resolución del **Proyecto Final**, enfocado en la integración de procesamiento de datos, simulación estocástica de variables físicas y gestión cronológica de proyectos. El programa procesa múltiples archivos estructurados (`.csv`)[cite: 9], implementa control de excepciones, evalúa anomalías operativas mediante umbrales críticos y genera representaciones visuales avanzadas de series temporales y diagramas de Gantt[cite: 9].

---

## Contenido del Proyecto

El desarrollo incluye soluciones estructuradas mediante funciones y librerías científicas para los siguientes módulos:

* **Carga y Validación de Datos:** Importación automatizada de archivos de configuración y parámetros (`precios.csv`, `civil_output.csv`, `parametros.csv`)[cite: 9] utilizando la librería `pandas`[cite: 9], con manejo de excepciones `FileNotFoundError` para asegurar la robustez inicial[cite: 9].
* **Simulación de Sensores:** Módulo basado en distribuciones normales (`numpy.random.normal`) para generar lecturas diarias de variables operativas como energía, vibración y temperatura, garantizando valores físicos reales no negativos[cite: 9].
* **Evaluación de Anomalías:** Algoritmo lógico que compara las lecturas frente a límites operativas preestablecidos[cite: 9], clasificando los eventos en estados normales, alertas preventivas o fallos críticos que generan retrasos en el cronograma[cite: 9].
* **Gestión de Cronograma y Retrasos:** Motor de cálculo temporal que ajusta dinámicamente las fechas de inicio y fin de las actividades de ingeniería civil a partir de los retrasos acumulados por anomalías durante la simulación anual[cite: 9].
* **Generación de Reportes y Visualización:** Módulos dedicados al procesamiento de registros diarios para la exportación de resultados a nuevos archivos estructurados, despliegue de reportes detallados en consola y trazado de gráficos analíticos mediante `matplotlib` (series temporales de parámetros y diagrama de Gantt con indicadores de retraso)[cite: 9].

---

## Especificaciones de Ejecución

* **Entorno:** Los códigos han sido desarrollados y validados para su ejecución en **Google Colab**[cite: 9] y entornos locales de Python.
* **Requerimientos:** Este desarrollo hace uso extensivo de librerías especializadas para análisis de datos y graficación, requiriendo `pandas`, `numpy` y `matplotlib`[cite: 9].
* **Convención de nomenclatura:** El archivo de entrega final sigue el formato requerido según las pautas metodológicas y de integración del curso[cite: 9].
