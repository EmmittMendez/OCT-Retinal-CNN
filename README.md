# Objetivo del Proyecto

El objetivo de este proyecto es diseñar e implementar técnicas de procesamiento digital de imágenes para mejorar la detección de enfermedades de la retina utilizando imágenes OCT (Tomografía de Coherencia Óptica). Estas imágenes permiten a los oftalmólogos observar detalladamente cada capa de la retina, lo que facilita el diagnóstico de diversas patologías. Con este enfoque, es posible utilizar las imágenes OCT para desarrollar modelos predictivos que clasifiquen pacientes en diferentes categorías.

*(Aquí se insertan algunas imágenes OCT)*

---

## Datos del Proyecto

Este proyecto utiliza la base de datos **"Retinal OCT Feature Map and Filters Visualization"**, que contiene los siguientes conjuntos de datos:

- **Train**: 83,484 imágenes distribuidas en 4 clases:
  - CNV: 37,205 imágenes
  - DME: 11,348 imágenes
  - DRUSEN: 8,616 imágenes
  - NORMAL: 26,315 imágenes

- **Test**: 968 imágenes distribuidas uniformemente entre las 4 clases:
  - CNV: 242 imágenes
  - DME: 242 imágenes
  - DRUSEN: 242 imágenes
  - NORMAL: 242 imágenes

- **Val**: 32 imágenes en total, 8 por clase.

Las imágenes están en una resolución no muy alta, tienen dimensiones variables y presentan ruido en forma de puntos y bordes blancos.

*(Insertar 3 imágenes ilustrativas)*

---

## Instrucciones de Uso

1. **Descarga del Dataset:**
   - Para obtener el dataset, visita la página de Kaggle en el siguiente enlace: [Retinal OCT Feature Map and Filters Visualization](https://www.kaggle.com/code/justforgags/retinal-oct-feature-map-and-filters-visualization/input).

2. **Organización del Dataset:**
   - Una vez descargado el dataset, coloca las carpetas **Train**, **Test** y **Val** dentro de la carpeta del repositorio del proyecto.

3. **Configuración del Código:**
   - En el código principal, asegúrate de actualizar las rutas de acceso para que coincidan con la ubicación de las carpetas en tu sistema. Esto evitará problemas al cargar los datos.
