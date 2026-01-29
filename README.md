# Resolución del Problema del Viajero Frecuente (TSP) mediante Algoritmos Genéticos

Este proyecto implementa una solución al **Problema del Viajero Frecuente (TSP)** utilizando Algoritmos Genéticos (AG) en Python. El objetivo es encontrar la ruta más corta posible que visite un conjunto de 18 ciudades de América y regrese al punto de origen.

## Descripción
El código calcula la ruta óptima minimizando la distancia geodésica entre ciudades. Se utilizan técnicas de computación evolutiva para evitar la explosión combinatoria de los métodos exactos.

El conjunto de datos incluye ciudades como Ciudad de México, Quito, Miami, Buenos Aires, entre otras.

## Características del Algoritmo
Basado en el reporte del proyecto, la implementación incluye:

* **Selección:** Torneo y Ranking.
* **Cruce (Crossover):** PBX (Position-Based) y PMX (Partially Mapped).
* **Mutación:** Scramble e Inversa.
* **Elitismo:** Por árbol genealógico para preservar a los mejores individuos.
* **Criterio de Paro:** Estancamiento por 30 generaciones o máximo 200 iteraciones.

## Requisitos
El proyecto fue desarrollado en Python 3. Las dependencias principales son:
* `pandas` (Manipulación de datos)
* `geopy` (Cálculo de distancias geodésicas)
* `numpy` (Operaciones matriciales)
* `matplotlib` (Visualización)

## Instalación y Uso

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/nombre-del-repo.git](https://github.com/TU_USUARIO/nombre-del-repo.git)
