# Análisis de la posesión en La Liga
## Presentación
La posesión de balón en el fútbol se relaciona con el dominio del partido, se presupone que si tienes mas posesión de balón, tendrás mas oportunidad de poder ganar el partido. Esta variable está relacionada con muchas otras como el porcentaje de acierto en el pase, las llegadas con peligro a portería rival, etc... La influencia que tiene la posesión es importante para muchos equipos, para otros no tanto, por lo que en este trabajo vammos a tratar de analizar su influencia, además de su relacion con otras variables, por lo que nuestra hipótesis principal será ¿Es la posesión de balón una variable  importante para ganar un partido o campeonato?
## Columnas y descripciones
* **Clasificación**: Corresponde a la posición de cada equipo al final de la temporada.
* **Equipo**: Nombre del club.
* **GF**: Goles a favor por equipo.
* **GC**: Goles en contral del equipo.
* **Pts***: Puntos al finalizar la temporada.
* **xG**: Expected goals o goles esperados, es una métrica que calcula la probabilidad de que un tiro a puerta sea gol y se calcula entre 0 y 1.
* **xGA**: Expected goals against o goles esperados en contra, probabilidad de que un tiro en contra sea gol y se calcula entre 0 y 1.
* **Posesión**: La posesión de balón del equipo al finalizar la temporada.
* **Tiros a puerta**: Tiros totales del equipo al finaliar la temporada.
* **% Acierto pase**: Porcentaje de acierto en el pase del equipo.
* **ACG**: Acciones para la creación de goles por equipo.
* **PV**: Valor de la posesión o posesion value, esta métrica tiene que ver con la cantidad de veces que el equipo llega a último tercio o área rival.
* **Diferencia posesion**: Esta variable se crea restando el PV menos la posesion (la creé sobre lamarcha y fue reveladora).
* ## EDA
* **El análisis incluye los siguientes pasos.**

 1. Importación de los datos y su visualización.
 2. Cambios de nombres y eliminación de columnas innecesarias.
 3. Chequeo de valores nulos o duplicados.
 4. Creación de nuevas columnas.
 5. Concatenación de tablas para conseguir los dataset finales.
 7. Información y descripción de los dataframe.
 8. Análisis de media, media, percentiles y rangos.
 9. Visualización gráfica de las variables numéricas mas importantes.
 10. Visualización gráfica de la combinación de variables mas importantes.
 11. Gráficos de densidad.
 12. Correlación de variables numéricas.
 13. Coeficiente de correlación de Pearson.
 14. Gráficos de dispersión.
 15. Matriz de correlación (heatmap y pairplot).
 16. Gráficos de dispersión multivariante.
 17. Gráficos de barras.
## Conclusión
En este archivo se puede encontrar como es la distribución y organización del proyecto, comenzando por visualizar los datos obtenidos mediante web scraping en la web fbref.com. Se podrán encontrar diferentes visualizaciones y gráficos de los dataframe de la liga de las temporadas 20-21, 21-22 y 22-23. Estas visualizaciones nos darán información valiosa y nos podrán dar una mejor visión de lo que este proyecto busca, que no es otra cosa que saber de que modo influencia la posesión de balón al fútbol español.
