# MONTE_CARLO.ipynb

## Descripción general

Este notebook de Jupyter, `MONTE_CARLO.ipynb`, contiene una simulación de Monte Carlo diseñada. [El modelo que esta descrito en el paper "Síntesis de Poblaciones Estelares en la Vía Láctea mediante Simulación de Monte Carlo"]. La simulación genera diversas poblaciones estelares, calcula sus tiempos de vida y clasifica los remanentes en distintos tipos en función de la masa inicial y otras condiciones físicas.

## Contenido

1. **Importación de Librerías**: Se importan las librerías necesarias, como `numpy` para operaciones numéricas y `matplotlib` para gráficos.
2. **Definición de Constantes**: Configuración de constantes como el tiempo de vida del Sol, rangos de masa estelar y otras constantes físicas.
3. **Definición de Funciones**:
   - **Cálculo de Tiempo en la Secuencia Principal**: Función para calcular el tiempo de vida de una estrella en la secuencia principal en función de su masa.
   - **Clasificación de Remanentes**: Función para clasificar estrellas como Enanas Blancas, Estrellas de Neutrones o Agujeros Negros, basándose en su masa al final de la secuencia principal.
   - **Simulación de Monte Carlo**: Función principal que genera poblaciones estelares aleatorias, calcula tiempos de vida y clasifica los remanentes.
4. **Ejecución de Simulaciones**: Se ejecutan simulaciones para distintos tamaños de población estelar (por ejemplo, 100, 1,000, 10,000, etc.), y se registran los resultados.
5. **Visualización de Resultados**: Se crean histogramas y visualizaciones de las distribuciones de masa de diferentes tipos de remanentes estelares.

## Uso

Para ejecutar el notebook, asegúrate de tener instalados los siguientes paquetes de Python:
- `numpy`
- `matplotlib`
- `collections` 

