# ProyectoDeforestacion

---

# Proyecto Deforestacion para Análisis Topológico de Datos

Este proyecto aplica herramientas de **Topological Data Analysis (TDA)** para estudiar patrones de deforestación en distintos países. Su objetivo principal es comparar la estructura espacial de puntos asociados a pérdida de bosques utilizando métodos como:

* **Diagramas de Persistencia (H₀, H₁)**
* **Distancias Topológicas:**

  * *Bottleneck distance*
  * *1-Wasserstein distance*
* **Euler Characteristic Curve (ECC)**
* **Triangulaciones de Delaunay y Diagramas de Voronoi** para representar la topología

Todo el análisis fue implementado en **Google Colab**, aprovechando Python, GUDHI, Scikit-Learn y herramientas avanzadas de visualización.

---

## 📌 ¿Qué busca este proyecto?

El objetivo es encontrar **similitudes y diferencias topológicas** entre las distribuciones espaciales de puntos que representan deforestación en distintos países.

Esto permite:

* Detectar países con patrones similares de deforestación.
* Comparar estabilidad topológica entre regiones.
* Visualizar cómo evoluciona la estructura geométrica de los datos.
* Estudiar la relación entre medidas topológicas como la ECC y distancias de persistencia.

---

## 🧠 ¿Qué significa todo esto en términos simples?

* **Tomamos puntos geoespaciales de deforestación** y los convertimos en representaciones matemáticas de su forma.
* Usamos **topología** para estudiar "huecos", conectividad y forma general del conjunto.
* Calculamos **qué tan parecidos son dos países**, basándonos no solo en distancia geográfica, sino en la estructura completa del patrón de deforestación.
* Esto permite análisis más profundos que un mapa tradicional.

En resumen:

> **El proyecto compara la forma, estructura y complejidad de la deforestación entre países usando matemáticas avanzadas.**

---

## 🛠️ Principales herramientas utilizadas

* **Google Colab**
* Python 3
* **GUDHI** para TDA
* **NumPy**, **Pandas**
* **Scikit-Learn** para PCA
* **Scipy** para distancias y Delaunay
* **Matplotlib** para gráficos
* **persim** para distancias bottleneck

---

## 📊 Resultados principales

* Generación de ECC por país
* Matrices de similitud topológica
* Gráficos de triangulación y Voronoi
* Cálculo de distancias Bottleneck y Wasserstein
* Comparación topológica entre los primeros 10 países del dataset

---

## 📁 Organización del código

* **Carga y preprocesamiento de datos**
* **Reducción de dimensión (PCA)**
* **Cálculo de diagramas de persistencia**
* **Distancias Bottleneck y Wasserstein**
* **Curvas de característica de Euler (ECC)**
* **Visualizaciones topológicas**
* **Comparación entre países**

---

## 🌱 Motivación

La deforestación es un fenómeno complejo que no siempre puede analizarse con estadísticas clásicas.
La topología permite entender **la forma** de los datos y extraer patrones globales difíciles de detectar de otra manera.

---
