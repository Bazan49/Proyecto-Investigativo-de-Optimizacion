# Proyecto de Optimización: Comparación de Algoritmos de Minimización

Este proyecto implementa y compara dos métodos de optimización (Máximo Descenso y Quasi-Newton BFGS) para minimizar la función:

\[ f(x,y) = \frac{\arctan(x^2 + y^2)}{e^x} \]

### Requisitos de Instalación

Para correr este proyecto, necesitas tener instalado:

```bash
Python 3.7+
NumPy
Matplotlib
SciPy
Jupyter Notebook
```

### Estructura del Proyecto
- Implementación Métodos.ipynb - Notebook principal con la implementación de los algoritmos
- Informe.pdf - Análisis teórico de la función objetivo y de los resultados obtenidos
- Archivos JSON de configuración - Para definir experimentos

### Cómo Realizar Nuevos Experimentos

1. Crear Archivo de Configuración JSON con la siguiente estructura

```json
[
    {
        "learning_rate": ,
        "tol": ,
        "max_iter": ,
        "x0": 
    },

]
```

2. Ejecutar el Experimento

# Nombre del archivo JSON que creaste
experiment_name = "mi_experimento.json"

# Ejecutar el experimento
Experiment(experiment_name)

3. Resultados Obtenidos

La función Experiment genera un archivo results_mi_experimento.json con los resultados obtenidos dada la entrada