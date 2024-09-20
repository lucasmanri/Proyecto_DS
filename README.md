Análisis Exploratorio de Datos
Se realizó un análisis exploratorio del conjunto de datos de Pokémon, incluyendo
visualizaciones para comprender las relaciones entre diferentes variables:
 La evolución de las estadísticas a lo largo de las generaciones se examinó
mediante un gráfico de líneas, revelando tendencias en el poder de los
Pokémon a lo largo del tiempo.
 Un mapa de calor ilustró la frecuencia de las combinaciones de tipos,
destacando las más y menos comunes.
 Un gráfico de barras comparó las estadísticas promedio de Pokémon
legendarios y no legendarios, mostrando diferencias claras en su poder.
 La popularidad de cada tipo se visualizó en otro gráfico de barras, permitiendo
identificar los tipos más frecuentes.
 Finalmente, un boxplot mostró la distribución de los Z-Scores para las
estadísticas de los Pokémon, proporcionando información sobre su
variabilidad.
Modelado Predictivo
Se implementaron dos modelos de clasificación para predecir el estatus legendario de
un Pokémon:
 Random Forest: Utilizando las estadísticas básicas, logró una precisión del 96%.
 XGBoost: Incorporando características adicionales como la combinación de
tipos y la generación, alcanzó una precisión del 97.5%.
Ambos modelos mostraron un buen rendimiento general, pero tuvieron dificultades
para predecir con precisión los Pokémon legendarios, lo que sugiere la posible
influencia de otros factores no considerados en el análisis.
Conclusión
Este análisis exploratorio proporcionó información valiosa sobre las características y
relaciones presentes en el conjunto de datos de Pokémon. Los modelos de clasificación
implementados demostraron ser efectivos para predecir el estatus legendario, aunque
hay margen de mejora, especialmente en la identificación de Pokémon legendarios.
En futuras investigaciones se podría explorar la inclusión de características adicionales,
el ajuste de hiperparámetros y la experimentación con otros algoritmos para mejorar
aún más la precisión de los modelos.
