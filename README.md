# Procesador de Encuestas

Proyecto académico en Python para generar y analizar datos de encuestas de hábitos.

## ¿Qué hace?

**Programa 1 – Generador:** crea un archivo CSV con datos sintéticos de encuesta (sexo, edad, respuesta).

**Programa 2 – Procesador:** menú interactivo para analizar el CSV con las siguientes opciones:
- Estadísticas generales (media y mediana de edad, conteo de respuestas)
- Filtro por sexo
- Filtro por rango de edad
- Exportar resultados a archivo de texto

**Visualizaciones:** gráficos con `matplotlib` que muestran la distribución de respuestas, edades y diferencias por sexo.

## Requisitos

```bash
pip install matplotlib
```

## Uso

1. Abrir `Encuestas.ipynb` en Jupyter Notebook o VS Code
2. Ejecutar el **Programa 1** para generar el archivo `Encuesta_habitos.csv`
3. Ejecutar el **Programa 2** e interactuar con el menú
4. Ejecutar la celda de **visualizaciones** para ver los gráficos

## Tecnologías

- Python 3
- matplotlib
- CSV / manejo de archivos

---
Autor: Bastian Contreras
