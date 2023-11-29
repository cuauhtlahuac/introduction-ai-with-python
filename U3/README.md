# U3: your first models

## Tipos de Machiene Learning

### Supervisado * (Veremos como hacer este)

Se le da una serie de datos al modelo para que después de relacionar los datos, pueda hacer predicciones
También aquí entran los modelos de clasificación, por ejemplo si un correo es spam o no.

Es decir, aquí necesitamos una serie de datos etiquetados para entrenar al modelo

### No supervisado

Aquí no hay datos etiquetados, simplemente datos y el modelo tiene que encontrar los patrones. Un ejemplo es darle datos de muchos clientes para que haga una "clusterización" ó agrupamiento.


### Por refuerzo

Aquí ponemos un agente y por cada acción le decimos si está correcto o incorrecto, el algoritmo que el agente buscará, será el que le genere más puntos.

Porn ejemplo al enseñarle ajedrez, le premiamos si hace un buen movimiento.

## Data: the basis of any model

Lo primero son los datos, deben de se rde calidad, igual que u cocinero necesita buenos ingredientes para poder cocinar.

Estos datos se llamarán conjunto de entrenamiento y se usarán para entrenar al modelo en un 80%. El otro 20% será el grupo de pruebas, para evaluar que tan bien entrenada quedó.

## Python libraries

### [Pandas](https://pandas.pydata.org/)

Librería para tratar datos: pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
built on top of the Python programming language.

### [NumPy](https://numpy.org/)

Puedes trabajar con matrices de diferentes dimensiones

### [scikit-learn](https://scikit-learn.org/stable/)

Scikit-learn provides dozens of built-in machine learning algorithms and models, called estimators. Each estimator can be fitted to some data using its fit method.

### MATPLOTLIB and SEABORN

For data visualization.

Matplotlib is a library in Python that enables users to generate visualizations like histograms, scatter plots, bar charts, pie charts and much more.
Seaborn is a visualization library that is built on top of Matplotlib. It provides data visualizations that are typically more aesthetic and statistically sophisticated.

### Tensor Flow

Junto con Pytorch son utilizados para entrenar modelos.

## [Your first model](./your_first_model/): linear regression

Vamos a generar un archivo csv con grados Celsius y Fahrenheit y así crear el primer modelo.

**CSV**: A CSV is a comma-separated values file, which allows data to be saved in a tabular format. CSVs look like a garden-variety spreadsheet but with a . csv extension. CSV files can be used with most any spreadsheet program, such as Microsoft Excel or Google Spreadsheets.

## Linear regression in detail

- Variable dependiente (Y axis): Por ejemplo el peso
- Variable independiente (x axis): Estas serían la altura y la edad para calcular el peso

Cada variable es una eje nuevo, por ejemplo el peso es el eje y, pero la altura sería x y edad z.

Entre más variables metamos, mayor será el número de ejes en la gráfica. No lo veamos como dimensiones, pero si como vectores, y el vector principal sería el de los resultados de la predicción.

y=mx+b

Y = variable dependiente o dato a predecir
m = pendiente
x= es la variable independiente
b=Punto de corte, o donde el eje x corta

Para más información Cuadrados mínimos OLS

