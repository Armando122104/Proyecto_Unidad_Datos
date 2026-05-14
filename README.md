# Proyecto de Ing de Datos aplicado a la competición de Kaggle

📌 Resumen del Proyecto <br>
Este estudio académico se centra en el desarrollo de un modelo de aprendizaje supervisado para predecir los resultados del torneo de baloncesto universitario de la NCAA. El objetivo principal es transformar datos históricos y estadísticas de temporada en probabilidades de victoria, superando la volatilidad inherente del torneo mediante un enfoque estrictamente cuantitativo.

🛠️ Ecosistema Tecnológico<br>
Entorno de Desarrollo: Google Colab (Notebooks en la nube para computación acelerada).
Lenguaje de Programación: Python 3.x.
Manipulación y Análisis: Pandas y NumPy para la limpieza y estructuración de grandes volúmenes de datos.
Machine Learning: Scikit-learn y XGBoost para el entrenamiento y validación de modelos.
Visualización de Datos y BI: Power BI para la creación de tableros (dashboards) interactivos que analizan métricas de rendimiento y comparativas de equipos.

📈 Inteligencia de Negocios (Power BI)<br>
A diferencia de un análisis puramente técnico, se integró Power BI para traducir las predicciones en información accionable mediante:
Visualización de probabilidades de avance por ronda.
Análisis histórico de "Upsets" (victorias de no favoritos).
Monitoreo comparativo: Salud de la temporada regular vs. desempeño en eliminatorias.

<br>
📚 Herramienta para la gestion de trabajo: <br>
Para una gestion y distribucion optima de la carga de trabajo se implemento el uso de la siguiente herramienta para la gestion de tareas en el equipo de trabajo: <br>
https://queretaro-team-sm6fizxi.atlassian.net/jira/software/projects/KAN/list?jql=project%20%3D%20KAN%20ORDER%20BY%20cf%5B10019%5D%20ASC
<br>
📊 Conclusiones del Estudio<br>
Eficacia Predictiva: El modelo alcanzó una precisión (Accuracy) del 73.51%, demostrando que la arquitectura de datos y el sistema de Rating Elo capturan con éxito la fuerza real de los equipos por encima del azar.
<br><br>
Optimización de Riesgo: Con un Log Loss de 0.5171, se validó que las probabilidades están bien calibradas. El modelo no solo identifica ganadores, sino que cuantifica correctamente la incertidumbre de cada encuentro.
<br><br>
Integración de Datos (U3): El éxito de las métricas confirma que la normalización de tablas (Coaches, Conferencias y Regiones) y su unión con datos históricos de Kaggle fue técnicamente sólida y libre de errores de integridad.
