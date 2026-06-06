# MIA_C3_AANS_Corte_01_Bitacora_03

## Información general

| Campo | Detalle |
|---|---|
| **Alumno** | Víctor Manuel Santos Martínez |
| **Materia** | Aprendizaje Automático No Supervisado |
| **Actividad** | Asignación 3 — Ingeniería de Características |

## Descripción

A partir de un dataset de hábitos de entretenimiento de 150 estudiantes (formato largo, 600 registros), se construyen dos nuevas características:

- **`total_entertainment`**: suma de las horas semanales de todos los tipos de entretenimiento (videojuegos, series, películas y libros) por estudiante.
- **`pct_screen`**: porcentaje de las horas totales correspondiente a entretenimiento en pantalla (videojuegos, series y películas), excluyendo libros.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `feature_engineering.ipynb` | Notebook principal con todo el pipeline ejecutado |
| `entertainment.xlsx` | Dataset original |
| `entertainment_features.csv` | Dataset enriquecido con las nuevas columnas |
| `fig_total_entertainment.png` | Distribución de horas totales de entretenimiento |
| `fig_pct_screen.png` | Distribución del % de entretenimiento en pantallas |
| `fig_avg_by_type.png` | Horas promedio semanales por tipo |
| `fig_scatter.png` | Relación entre total de entretenimiento y % pantallas |

## Entorno

```bash
conda activate science
jupyter notebook feature_engineering.ipynb
```
