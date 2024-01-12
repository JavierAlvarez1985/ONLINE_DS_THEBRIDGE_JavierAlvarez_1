{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "8160da9b-7c31-4d04-aa71-5e67a37f9dae",
   "metadata": {},
   "source": [
    "# Análisis de la posesión en La Liga"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8caa35dd-7437-4275-b066-8b45e15ef51e",
   "metadata": {},
   "source": [
    "## Presentación"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b695fd8e-4d01-4d16-8713-cca27182f3f4",
   "metadata": {},
   "source": [
    "La posesión de balón en el fútbol se relaciona con el dominio del partido, se presupone que si tienes mas posesión de balón, tendrás mas oportunidad de poder ganar el partido. Esta variable está relacionada con muchas otras como el porcentaje de acierto en el pase, las llegadas con peligro a portería rival, etc... La influencia que tiene la posesión es importante para muchos equipos, para otros no tanto, por lo que en este trabajo vammos a tratar de analizar su influencia, además de su relacion con otras variables, por lo que nuestra hipótesis principal será ¿Es la posesión de balón una variable  importante para ganar un partido o campeonato?"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b980c730-5bb8-41c7-aa43-2e1f4282e67f",
   "metadata": {},
   "source": [
    "## Columnas y descripciones"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "3b16dc88-4673-4e5e-a02f-f1b08c28ef19",
   "metadata": {},
   "source": [
    "* **Clasificación**: Corresponde a la posición de cada equipo al final de la temporada.\n",
    "* **Equipo**: Nombre del club.\n",
    "* **GF**: Goles a favor por equipo.\n",
    "* **GC**: Goles en contral del equipo.\n",
    "* **Pts***: Puntos al finalizar la temporada.\n",
    "* **xG**: Expected goals o goles esperados, es una métrica que calcula la probabilidad de que un tiro a puerta sea gol y se calcula entre 0 y 1.\n",
    "* **xGA**: Expected goals against o goles esperados en contra, probabilidad de que un tiro en contra sea gol y se calcula entre 0 y 1.\n",
    "* **Posesión**: La posesión de balón del equipo al finalizar la temporada.\n",
    "* **Tiros a puerta**: Tiros totales del equipo al finaliar la temporada.\n",
    "* **% Acierto pase**: Porcentaje de acierto en el pase del equipo.\n",
    "* **ACG**: Acciones para la creación de goles por equipo.\n",
    "* **PV**: Valor de la posesión o posesion value, esta métrica tiene que ver con la cantidad de veces que el equipo llega a último tercio o área rival.\n",
    "* **Diferencia posesion**: Esta variable se crea restando el PV menos la posesion (la creé sobre lamarcha y fue reveladora)."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "328bb1ab-2c72-4443-aa70-e9cfa3eff115",
   "metadata": {},
   "source": [
    "## EDA"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "76072ba5-75d5-4556-a971-916827095c5d",
   "metadata": {},
   "source": [
    "**El análisis incluye los siguientes pasos.**\n",
    "\n",
    " 1. Importación de los datos y su visualización.\n",
    " 2. Cambios de nombres y eliminación de columnas innecesarias.\n",
    " 3. Chequeo de valores nulos o duplicados.\n",
    " 4. Creación de nuevas columnas.\n",
    " 5. Concatenación de tablas para conseguir los dataset finales.\n",
    " 7. Información y descripción de los dataframe.\n",
    " 8. Análisis de media, media, percentiles y rangos.\n",
    " 9. Visualización gráfica de las variables numéricas mas importantes.\n",
    " 10. Visualización gráfica de la combinación de variables mas importantes.\n",
    " 11. Gráficos de densidad.\n",
    " 12. Correlación de variables numéricas.\n",
    " 13. Coeficiente de correlación de Pearson.\n",
    " 14. Gráficos de dispersión.\n",
    " 15. Matriz de correlación (heatmap y pairplot).\n",
    " 16. Gráficos de dispersión multivariante.\n",
    " 17. Gráficos de barras."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "b5176b50-509d-4d6b-8a30-7dcb1662f283",
   "metadata": {},
   "source": [
    "## Conclusión"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "2cacd499-b700-4141-9fe5-935c999c4f63",
   "metadata": {},
   "source": [
    "En este archivo se puede encontrar como es la distribución y organización del proyecto, comenzando por visualizar los datos obtenidos mediante web scraping en la web fbref.com. Se podrán encontrar diferentes visualizaciones y gráficos de los dataframe de la liga de las temporadas 20-21, 21-22 y 22-23. Estas visualizaciones nos darán información valiosa y nos podrán dar una mejor visión de lo que este proyecto busca, que no es otra cosa que saber de que modo influencia la posesión de balón al fútbol español."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.6"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
