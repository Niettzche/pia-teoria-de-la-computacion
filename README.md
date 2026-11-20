# PIA – Teoría de la Computación y Análisis de Algoritmos

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Niettzche/pia-teoria-de-la-computacion/blob/main/PIA_analisis_experimental.ipynb)

Análisis experimental del **Problema de Programación en Máquinas Paralelas (PMSP, $P_m||C_{max}$)**, Equipo Neumann.

Algoritmos implementados:

- **Graham (List Scheduling)**, según el pseudocódigo del reporte. Orden teórico $O(n^2 + nE)$.
- **LPT (Longest Processing Time)**. Orden teórico $O(n \log n + nm)$.

## Contenido del notebook

1. Generador de instancias del PMSP
2. Implementación de ambos algoritmos
3. Tabla 2: 30 ejecuciones por algoritmo
4. Gráficas de tiempo de ejecución vs. tamaño de instancia
5. Ajuste de curva (regresión log-log y mínimos cuadrados con $n$, $n\log n$, $n^2$, $n^3$)
6. Orden experimental obtenido
7. Extra: calidad de las soluciones contra la cota inferior

El notebook ya está ejecutado en Google Colab: abre el enlace de arriba para ver todas las tablas y gráficas.

## Ejecutar

En Colab: *Entorno de ejecución → Ejecutar todas*.

En local (Python 3.10+):

```bash
pip install numpy pandas matplotlib scipy jupyter
jupyter notebook PIA_analisis_experimental.ipynb
```
