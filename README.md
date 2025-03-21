# YouTube-Case-study
Análisis Exploratorio YouTube Case "Análisis de datos"

---

## 📚 Tabla de Contenidos

- [🧠 ¿Qué incluye este proyecto?](#-qué-incluye-este-proyecto)
- [🔍 Análisis realizado](#-análisis-realizado)
  - [1. Carga y Limpieza de Datos](#1-carga-y-limpieza-de-datos)
  - [2. Análisis de Sentimiento](#2-análisis-de-sentimiento)
  - [3. Nubes de Palabras](#3-nubes-de-palabras)
  - [4. Análisis de Emojis](#4-análisis-de-emojis)
  - [5. Análisis de Categorías de Videos](#5-análisis-de-categorías-de-videos)
  - [6. Correlaciones](#6-correlaciones)
  - [7. Análisis de Canales Populares](#7-análisis-de-canales-populares)
  - [8. Análisis de Puntuación en Títulos](#8-análisis-de-puntuación-en-títulos)
- [💻 Tecnologías y librerías utilizadas](#-tecnologías-y-librerías-utilizadas)
- [🚀 Resultado](#-resultado)
- [⚙️ Cómo ejecutar este proyecto](#️-cómo-ejecutar-este-proyecto)

---

## 🧠 ¿Qué incluye este proyecto?

- ✅ Limpieza y procesamiento de más de **690,000 comentarios**.
- ✅ Análisis de sentimiento utilizando **TextBlob**.
- ✅ Nubes de palabras para comentarios **positivos** y **negativos**.
- ✅ Extracción y análisis de **emojis** más utilizados.
- ✅ Mapeo de categorías (`category_id`) con nombres reales.
- ✅ Cálculo de tasas de interacción (**likes, dislikes, comentarios vs. vistas**).
- ✅ Análisis de correlación entre métricas de engagement.
- ✅ Evaluación de los títulos mediante el conteo de signos de puntuación.
- ✅ Identificación de los canales más activos en la plataforma.

---

## 🔍 Análisis realizado

### 1. Carga y Limpieza de Datos

- Cargué un dataset de comentarios de YouTube desde Google Drive.
- Verifiqué y eliminé valores nulos en los comentarios.
- Trabajé con un dataset de **691,374 comentarios** después de la limpieza.

### 2. Análisis de Sentimiento

- Utilicé la librería **TextBlob** para calcular la polaridad del sentimiento.
- Clasifiqué los comentarios como **positivos** (1) o **negativos** (-1).
- Creé subconjuntos para cada tipo de comentario.

### 3. Nubes de Palabras

- Generé nubes de palabras para comentarios positivos y negativos.
- Excluí palabras comunes (stopwords) para obtener resultados más relevantes.

### 4. Análisis de Emojis

- Extraje los emojis de los comentarios usando la librería **emoji**.
- Conté su frecuencia y visualicé los 10 más comunes con **Plotly**.

### 5. Análisis de Categorías de Videos

- Mapeé los `category_id` a nombres de categorías.
- Analicé cómo varían los likes entre categorías mediante boxplots.

### 6. Correlaciones

- Calculé correlaciones entre vistas, likes y dislikes.
- Encontré una relación fuerte entre vistas y likes (0.78) y una moderada entre likes y dislikes (0.45).

### 7. Análisis de Canales Populares

- Identifiqué los canales con más videos en el dataset.
- Algunos canales destacados: *The Late Show with Stephen Colbert*, *WWE*, *Late Night with Seth Meyers*.

### 8. Análisis de Puntuación en Títulos

- Conté signos de puntuación en títulos para ver si influían en el engagement.
- Esta métrica puede ayudar a identificar títulos más llamativos.

---

## 💻 Tecnologías y librerías utilizadas

- Python
- Pandas
- TextBlob
- WordCloud
- Seaborn
- Matplotlib
- Plotly
- emoji
- Jupyter Notebook / Google Colab

---

## 🚀 Resultado

Este proyecto ofrece una visión profunda de cómo interactúan los usuarios con los videos de YouTube. Desde el lenguaje y los emojis usados en los comentarios, hasta la influencia del tipo de contenido y los títulos en el engagement, el análisis brinda una base sólida para comprender el comportamiento del usuario en plataformas sociales.

