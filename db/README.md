# Análisis de Ventas por Sucursal

Este repositorio contiene un proceso de preprocesamiento de datos para analizar el comportamiento de ventas por sucursal usando Python y pandas.

## Estructura del Proyecto

```
data/
├── raw/                  # Datos crudos originales
│   ├── sucursales.csv
│   └── ventas.csv
├── processed/            # Datos preprocesados y resultados
│   ├── ventas_sucursal_enriquecido.csv
│   ├── ventas_por_sucursal.csv
│   └── scatter_ventas_transacciones.png
notebooks/
└── 01_preprocesamiento.ipynb  # Notebook con el código de limpieza y análisis
```

## Descripción

- Se limpian y enriquecen los datos de ventas cruzándolos con información de sucursales.
- Se generan métricas por sucursal (ventas totales, promedio, número de transacciones).
- Se guarda un dataset preprocesado listo para análisis.
- Se genera una gráfica de dispersión para explorar la relación entre ventas y transacciones.

## Requisitos

- Python 3.8+
- pandas
- matplotlib

## Cómo ejecutar

```bash
pip install pandas matplotlib
jupyter notebook notebooks/01_preprocesamiento.ipynb
```
