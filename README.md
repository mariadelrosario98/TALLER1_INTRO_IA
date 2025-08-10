# Taller 1 – Introducción a la Inteligencia Artificial  
**Autores:** Santiago González Granada & María del Rosario Castro Mantilla  
**Tema:** Aplicación de Algoritmos de Búsqueda  

## 📌 Descripción  
Este taller aborda la implementación y análisis de diversos algoritmos de búsqueda aplicados a problemas de logística, transporte, biología y economía.  
El trabajo combina el modelado de grafos con medidas de distancia, evaluación de desempeño y reflexiones críticas sobre la escalabilidad y adaptabilidad de cada enfoque.

## 📂 Contenido del Repositorio  
- **`README.md`** – Descripción de los ejercicios y guía de uso.  
- **`taller_busqueda.ipynb`** – Implementación en Python de los algoritmos y ejercicios.  
- **`taller.pdf`** – Documento con enunciados, análisis y reflexiones.

## 🧠 Ejercicios Incluidos  

### 1. Optimización de rutas rurales (Logística) – **Búsqueda A\***
- Modelado de grafo ponderado con distancias.  
- Uso de distancia euclidiana y propuesta de distancia geodésica.  
- Análisis de complejidad y efecto de la heurística.  
- Reflexión sobre escalabilidad con incremento de nodos.

### 2. Red de metro (Transporte) – **BFS vs IDS**
- Comparación de coste temporal y consumo de memoria.  
- Modelado de grafo no ponderado y versión ponderada por tiempos de viaje.  
- Regla práctica para elección de algoritmo según presupuesto de memoria.  

### 3. Filogenia (Biología) – **Búsqueda de Profundidad Limitada en DAG**
- Construcción de grafos acíclicos dirigidos (DAG).  
- Cálculo del Antepasado Común Más Reciente (MRCA).  
- Discusión sobre impacto del límite de profundidad y escalabilidad a cientos de especies.

### 4. Decisiones de inversión (Economía) – **Búsqueda Voraz**
- Implementación de árbol de decisiones con utilidad esperada.  
- Discusión sobre limitaciones en entornos volátiles.  
- Incorporación de riesgo, aprendizaje y adaptabilidad.

## ⚙️ Requerimientos  
- Python 3.x  
- [NetworkX](https://networkx.org/)  
- Matplotlib  
- Jupyter Notebook  
