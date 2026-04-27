# Predicción de Calidad del Agua — India
**2do Examen Parcial · Procesamiento de Alto Volumen de Datos**  
Pontificia Universidad Javeriana · Juan Santiago Méndez · 2026

---

## Descripción

Pipeline completo de análisis y predicción del Índice de Calidad del Agua (WQI) sobre datos de ríos de la India, usando PySpark para el procesamiento distribuido y dos modelos de Machine Learning: Regresión Lineal (MLlib) y Red Neuronal Densa (Keras).

## Estructura del repositorio

```
├── TallerCalidadAgua_Mendez.ipynb   # Notebook principal
├── waterquality.csv                  # Dataset (534 estaciones de monitoreo)
└── Indian_States/                    # Shapefiles para visualización geográfica
    ├── Indian_States.shp
    ├── Indian_States.shx
    ├── Indian_States.dbf
    └── Indian_States.prj
```

## Ejecución en Google Colab

1. Abre el notebook en Colab
2. Ejecuta la celda de instalación y **reinicia el runtime**
3. Ejecuta todas las celdas en orden

O clona el repo directamente desde Colab:
```python
!git clone https://github.com/tu-usuario/parcial2-calidad-agua.git
import os; os.chdir('parcial2-calidad-agua')
```

## Tecnologías

`PySpark` · `MLlib` · `Keras/TensorFlow` · `GeoPandas` · `Matplotlib` · `Scikit-learn`

## Referencia

Sutadian et al. (2016). Development of a Water Quality Index. [IntechOpen Cap. 69568](https://www.intechopen.com/chapters/69568)
