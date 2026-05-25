# Introducción a la Librería Pandas en Python

Este trabajo consiste en una investigación sobre la librería **Pandas** de Python, una de las herramientas más utilizadas en el mundo del análisis de datos y la inteligencia artificial.

El trabajo se divide en dos partes:

- **Parte teórica:** Investigación sobre los conceptos de Pandas, sus características, utilidad e importancia en el campo de la ciencia de datos.

- **Parte práctica:** Desarrollo de cuatro ejercicios en un notebook de Google Colab donde se aplican las funciones de la librería, incluyendo la creación de DataFrames, operaciones entre columnas, lectura de archivos CSV y manipulación de datos sintéticos.

---

## Objetivo

Comprender y aplicar los fundamentos de la librería Pandas para la manipulación y el análisis de datos tabulares en Python, estableciendo una base sólida que permita su utilización en proyectos futuros relacionados con inteligencia artificial y ciencia de datos.

---

## Temas Investigados

La investigación documental abordó los siguientes temas:

| Tema | Descripción |
|:-----|:------------|
| **¿Qué es Pandas?** | Librería de código abierto para manipulación y análisis de datos. Creada por Wes McKinney en 2008. Su nombre proviene de "Panel Data". |
| **¿Para qué sirve?** | Permite cargar, limpiar, transformar, analizar y visualizar datos de manera eficiente. |
| **Objetivo principal** | Proporcionar estructuras de datos potentes y flexibles (especialmente el DataFrame) para trabajar con datos etiquetados y relacionales. |
| **Estructuras fundamentales** | **Series** (unidimensional) y **DataFrame** (bidimensional, similar a una hoja de cálculo). |
| **Funciones principales** | `read_csv()`, `head()`, `info()`, `describe()`, `groupby()`, `apply()`, `fillna()`, `dropna()`, entre otras. |
| **Importancia en IA** | Pandas automatiza el proceso de limpieza y preparación de datos (data wrangling), que consume aproximadamente el 80% del tiempo en proyectos de inteligencia artificial. |

---

## Explicación de los Ejercicios Realizados

### Ejercicio 1: Creación de un DataFrame desde un diccionario

**Descripción:**  
Se construyó un DataFrame manualmente a partir de un diccionario de Python. El diccionario contenía información de cinco videojuegos, incluyendo título, género, año de lanzamiento, puntuación y precio.

## Aprendizaje:

Las claves del diccionario se convierten automáticamente en nombres de columnas, y cada lista representa los valores de una columna.

### Ejercicio 2: Operaciones entre columnas

**Descripción:**
Se crearon dos nuevas columnas a partir de operaciones matemáticas con columnas existentes:

- **Precio_por_Punto:** división del precio entre la puntuación (indica la relación calidad-precio).

- **Precio_Oferta:** precio original con un descuento del 20%.

### Ejercicio 3: Lectura de un archivo CSV

**Descripción:**
Se creó un archivo CSV de ejemplo en el entorno de trabajo y posteriormente se cargó utilizando la función pd.read_csv().

**Aprendizaje:**
Los archivos CSV son el formato estándar para el intercambio de datos. Pandas facilita enormemente su ingesta con una sola línea de código.

### Ejercicio 4: Trabajo con datos sintéticos, filtrado y agrupación

**Descripción:**
Se generó un conjunto de datos aleatorio que simula 200 ventas de productos tecnológicos (Laptop, Mouse, Teclado, Monitor). Sobre estos datos se aplicaron tres operaciones fundamentales:

- **Filtrado:** Selección de ventas de laptops con importe superior a 1000 euros.

- **Agrupación:** Cálculo del ingreso total por cada tipo de producto.

**Aplicación de función:** Cálculo del IVA (21%) para cada venta.

**Aprendizaje:**
La generación de datos sintéticos es útil para prototipar y probar código sin necesidad de fuentes externas. Las operaciones de filtrado, agrupación y aplicación de funciones constituyen el núcleo del análisis de datos con Pandas.

## Conclusiones
La realización de este trabajo ha permitido extraer las siguientes conclusiones:

- Pandas es una herramienta fundamental para cualquier persona que trabaje con datos en Python. Su estructura DataFrame resulta intuitiva y poderosa, combinando la familiaridad de las hojas de cálculo con la potencia de un lenguaje de programación.

- La sintaxis de Pandas es accesible. Operaciones esenciales como filtrar filas, agrupar datos o crear nuevas columnas se expresan de manera clara y concisa, lo que acelera el proceso de aprendizaje y aplicación.

- La integración con NumPy es una ventaja significativa. Como se demostró en el Ejercicio 4, la combinación de ambas librerías facilita la generación de datos sintéticos y operaciones numéricas complejas, algo muy común en etapas de prototipado.

- Pandas resuelve el problema del "data wrangling". Antes de construir modelos de inteligencia artificial, los datos deben estar limpios y estructurados. Pandas proporciona todas las herramientas necesarias para afrontar esta tarea, que suele ser la más demandante en términos de tiempo en proyectos reales.

- Dominar Pandas es un requisito indispensable para iniciarse en el análisis de datos y la inteligencia artificial con Python. Esta actividad ha establecido una base sólida que permitirá abordar temas más avanzados en el futuro, como la combinación de DataFrames, el manejo de valores nulos o la creación de tablas dinámicas.
