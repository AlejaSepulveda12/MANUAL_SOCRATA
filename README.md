# Tutorial completo: Uso de la API de Socrata en Jupyter (Python y R)

Este repositorio contiene un manual/tutorial detallado para estudiantes sobre cómo descargar, consultar y analizar datos abiertos desde la API de Socrata (SODA API) usando **Python** y **R** en Jupyter Notebooks.

---

## Contenido

- Instalación de paquetes en Python y R
- Introducción a SoQL (SQL para Socrata)
- Conexión a la API de Socrata
- Consultas avanzadas con SoQL
- Descarga masiva de datos por lotes
- Manipulación y visualización de datos
- Uso de Jupyter Notebooks
- Buenas prácticas en proyectos de datos abiertos
- Publicación en GitHub
- Recursos adicionales

---

## Requisitos

### Python
```bash
pip install sodapy pandas requests matplotlib seaborn
```

### R
```r
install.packages("RSocrata")
install.packages("dplyr")
install.packages("httr")
install.packages("ggplot2")
```

---

## Ejecución

1. Ejecutar los notebooks dentro de la carpeta `notebooks/`:
- `socrata_python.ipynb`
- `socrata_r.ipynb`

---

## Contenido de los Notebooks

### Python
- Conexión básica a Socrata
- Consultas SoQL
- Descarga masiva por lotes
- Visualización de datos con Matplotlib y Seaborn

### R
- Conexión básica a Socrata
- Consultas SoQL
- Descarga masiva por lotes
- Visualización de datos con ggplot2

---

## Buenas prácticas

- Usar `limit` y `offset` para descargas grandes
- Convertir variables a numéricas o fechas
- Guardar datasets descargados como CSV
- Documentar el código y usar comentarios
- Versionar y subir proyectos a GitHub

---

## 🔗 Recursos adicionales

- [Socrata Developers](https://dev.socrata.com/)
- [SoQL Queries](https://dev.socrata.com/docs/queries/)
- [NYC Open Data](https://opendata.cityofnewyork.us/)

---

## ✍ Autor
Creado por **Laura Alejandra Sepulveda**
