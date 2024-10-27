## Autores:
- Lucía De Ancos Villa (100451066)
- Rodrigo Florencio Rivas Arévalo (100540706)
- Camino Rodríguez Pérez-Carral (100445091)
- Paula Samper López (100541809)
- Lucía Yan Wu (100451764)

# **Predicción de Cáncer de Pulmón - Computación Evolutiva**
# **Predicción de Cáncer de Pulmón - Computación Evolutiva**

Para la tarea de clasificación binaria presentada en la asignatura, hemos desarrollado 3 tipos de soluciones/clasificadores diferentes para predecir si un paciente tiene cáncer de pulmón o no. Para ello, hemos utilizado el dataset `LungCancer.csv`, formado por 16 columnas y 284 instancias. 

Las 3 soluciones propuestas basadas en algoritmos genéticos son las siguientes:
- Solución 1: Codificación de cromosomas en base 3 ([0, 1, 2]). Código: `Solucion1.ipynb`
- Solución 2: Subconjunto de variables y sus correspondientes pesos. Código: `Solucion2.ipynb`
- Solución 3: Población de árboles de decisión. Código: `Solucion3.ipynb`

# Resultados

Los mejores resultados obtenidos para cada solución son los siguientes:

Solución | Accuracy
--- | --- 
1 | **92.98%**
1 | **92.98%**
2 | 86.96%
3 | 91.23% 

Podemos observar que las 3 soluciones propuestas consiguen el objetivo, clasificar si un paciente tiene cáncer de pulmón o no, con alta precisión.

Además, existe un trade-off entre la precisión y la velocidad de convergencia. Por ejemplo, la solución 1 devuelve la mejor precisión entre las tres soluciones pero es la más lenta en converger, mientras que para la solución 2 es el caso contrario (menor precisión, mayor convergencia).

Por último, mencionar que la realización de     esta tarea puede ayudar a la enfermedad de cáncer de pulmón y su investigación.

La presentación de la defensa se puede encontrar en: [CancerPulmon-CE.pdf](CancerPulmon-CE.pdf)

*NOTA: el orden de lectura de los documentos sigue la nomenclatura de las soluciones (`Solucion1.ipynb`, `Solucion2.ipynb`, `Solucion3.ipynb`)*