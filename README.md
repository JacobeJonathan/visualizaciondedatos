# VisualizacionDeDatos
- [Que es la visualizacion de datos](#Que-es-la-visualizacion-de-datos)
- [Salvar vida con datos](#Salvar-vidas-con-datos)
- [La carga cognitiva](#la-carga-cognitiva)
- [Herramientas para visualizar datos](#herramientas-para-visualizar-datos)
### Que es la visualizacion de datos
- ¿Qué es la visualización de datos?

- El input: que es donde se encuentran los datos ya sea que estén organizados o no.
- Output: es la presentación de los datos de una manera visual para ayudar a retener la información.

### Salvar vidas con datos
- ![Inicio](/src/visualizacionData.webp)

### La carga cognitiva
- Importancia de la visualización de datos: disminuye la carga cognitiva

- La carga cognitiva es el esfuerzo que se tiene que hacer para retener la información:

- Mayor carga cognitiva → Mayor esfuerzo para retener la información

- Menor carga cognitiva → Menor esfuerzo para retener la información

### herramientas-para-visualizar-datos
- Tableu
- python
- matplotlib
- Pandas
- powerbi
- ![Visualizacio ](/src/visualizaciones.jpg)

### ver diferente tipos de graficos
- Nos muestra las descripciones de como utilizar los graficos entrar al enlace para saber mas 
- ![Visualizacio ](/src/tipodegrafico.png)
- https://datavizcatalogue.com/ES/
## grafica de pie
- ![Visualizacio ](/src/PIE.webp)
- QUE SI HACER
- Los gráficos circulares son una buena forma de mostrar gráficamente una distribución de frecuencias. En un gráfico circular, la frecuencia o el porcentaje se representa tanto visual como numéricamente, por lo que suele ser rápida de entender para los lectores.

- Usa una gráfica de pastel o circular si tu audiencia tiene una idea general de la relación de las partes y el todo de los datos y no es tan importante comparar los tamaños de las rebanadas.

- También puedes usar una gráfica circular para transmitir que un segmento del total es relativamente pequeño o grande.
- QUE NO HACER
- No uses gráficos de pie cuando:
- Tengas más de 5 categorías
- Tengas categorías con valores muy similares por ejemplo si tienes una categoría con porcentaje 35,36,37 es mejor pensar en otro
tipo de gráfico como el de barras porque se llevara más tiempo entenderlo y al ojo humano se le dificulta encontrar esas pequeñas diferencias.
### grafica de burbujas
- Esta grafica es una variación del Scatter plot, pero muestra una dimensión adicional a las correlaciones entre los ejes X y Y, sino que además muestra el tamaño de la populación.
- Que hacer?
- No necesariamente hay que hacer correlaciones con ejes, sino también podemos mantener un gráfico único teniendo cuidado de las anotaciones de las burbujas pequeñas; el uso de los colores para cada categoría es fundamental.
- Que no hacer?
- No utilizar gráficos 3D y tener cuidado con las anotaciones que no se crucen entre sí o no puedan leer.
```py
from google.colab import files 
uploaded = files.upload()

import pandas as pd
df = pd.read_csv('iris.csv')

print(df)

```