# Proyecto de Análisis de Datos - ENACOM

Este proyecto de análisis de datos se centra en la evaluación del desempeño y crecimiento de la empresa ENACOM (Ente Nacional de Comunicaciones) en el sector de las telecomunicaciones en Argentina. El objetivo es analizar distintos indicadores clave, como ingresos, clientes y penetración de servicios, para obtener información valiosa sobre el estado actual y las tendencias del mercado.

## Descripción del Repositorio

El repositorio contiene los siguientes archivos y carpetas:

- **README.md**: Este archivo proporciona información general sobre el proyecto y cómo utilizarlo.
- **data**: Esta carpeta contiene los conjuntos de datos utilizados en el análisis. Los datos están en formato CSV y se dividen en diferentes categorías, como ingresos, clientes y servicios.
- **reports**: Esta carpeta contiene informes generados durante el análisis, que incluyen visualizaciones, resultados y conclusiones relevantes obtenidos a partir de los datos.

## Proceso de Análisis

El proceso de análisis se lleva a cabo utilizando el lenguaje de programación Python y diversas librerías populares, como Pandas, NumPy, Matplotlib y Seaborn. Los datos se cargan desde los archivos CSV y se aplican técnicas de limpieza, transformación y visualización para obtener información relevante.

El análisis se divide en varias etapas:

1. **Exploración de datos**: Se realiza una exploración inicial de los conjuntos de datos para comprender su estructura, variables y distribuciones. Se identifican posibles problemas de calidad de datos y se aplican técnicas de limpieza y transformación para preparar los datos para el análisis posterior.
2. **Análisis de ingresos**: Se analizan los ingresos de ENACOM a lo largo del tiempo, identificando tendencias, patrones estacionales y posibles factores que afecten los ingresos.
3. **Análisis de clientes**: Se examina la evolución de la cantidad de clientes de ENACOM en diferentes servicios, como fibra óptica, 4G y telefonía fija. Se buscan relaciones entre el crecimiento de clientes y otros factores.
4. **Análisis de penetración de servicios**: Se evalúa la penetración de servicios de telecomunicaciones en los hogares, como la adopción de fibra óptica, y se identifican las provincias con mayor y menor penetración.
5. **Generación de informes y visualizaciones**: Se generan informes y visualizaciones que resumen los hallazgos del análisis. Estos informes incluyen gráficos, tablas y conclusiones relevantes.


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

