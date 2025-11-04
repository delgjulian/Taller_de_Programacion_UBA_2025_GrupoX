# 📊 Exposición 1 – Análisis Exploratorio de la EMSE 2018

**Curso:** Taller de Programación  
**Carrera:** Maestría en Economía Aplicada – Universidad de Buenos Aires (UBA)  
**Grupo 15:** Julián Delgadillo Marín, Alejandro Alcocer, Christian Campos  
**Fecha:** 5 de noviembre de 2025

---

## 🧭 Descripción general

Esta exposición corresponde a la **Primera Exposición Grupal** del Taller de Programación.  
El trabajo consistió en realizar un **análisis exploratorio de la Encuesta Mundial de Salud Escolar (EMSE 2018)**, enfocándose en los hábitos saludables y conductas de riesgo en adolescentes escolarizados de Argentina.

La presentación se elaboró en formato **Beamer (LaTeX)** e incluyó procesamiento de datos, visualización y generación de hipótesis de investigación para su desarrollo posterior en la **Aplicación Final** del curso.

---

## 🧩 Estructura de la carpeta

Exposicion_1/
│
├── Datos/ # Enlace a la fuente oficial del dataset
│ └── README.md # Explica la fuente y descarga de EMSE 2018
│
├── Graficos/ # Gráficos en formato .png usados en la presentación
│
├── Presentacion/ # Archivos .tex y .pdf (Beamer)
│
├── Codigo/ # Scripts auxiliares de limpieza y visualización (opcional)
│
└── README.md # Este archivo de documentación


---

## 📚 Fuente de datos

- **Encuesta Mundial de Salud Escolar (EMSE 2018)**  
  Fuente: Ministerio de Salud de la Nación (Argentina)  
  Portal de Datos Abiertos:  
  [https://datos.gob.ar/dataset/salud-base-datos-3deg-encuesta-mundial-salud-escolar-emse-con-resultados-nacionales-argentina](https://datos.gob.ar/dataset/salud-base-datos-3deg-encuesta-mundial-salud-escolar-emse-con-resultados-nacionales-argentina)

> El archivo CSV original supera los 100 MB, por lo que no se incluye directamente en el repositorio.  
> Puede descargarse desde el enlace oficial o cargarse mediante pandas en Python:
>
> ```python
> import pandas as pd
> url = "https://datos.salud.gob.ar/.../download/emse_datosabiertos.csv"
> df = pd.read_csv(url)
> df.head()
> ```

---

## 🧮 Contenidos de la exposición

- Descripción general de la base EMSE 2018  
- Distribución por sexo y edad  
- Hábitos saludables (actividad física y alimentación)  
- Conductas de riesgo (tabaco y alcohol)  
- Propuestas de investigación y modelado  
- Proyección hacia la **Aplicación Final**:
  - Uso de modelos de clasificación supervisada (Logit / KNN)
  - Análisis de relaciones entre factores familiares, hábitos y conductas de riesgo

---

## 🧠 Objetivo académico

El trabajo busca integrar las competencias del curso:
1. Limpieza y estructuración de datos.  
2. Construcción de visualizaciones reproducibles.  
3. Generación de hipótesis y diseño de modelos predictivos simples.  
4. Aplicación práctica en una base real de microdatos nacionales.

---

## ⚙️ Herramientas utilizadas

- **Python**: pandas, matplotlib, seaborn  
- **LaTeX Beamer**: presentación académica  
- **GitHub**: control de versiones y documentación del grupo

---

## 🧾 Licencia

El material se comparte con fines educativos bajo licencia **CC BY-NC-SA 4.0**  
(Los datos pertenecen al Ministerio de Salud de la Nación – Argentina).

---

📘 *Repositorio creado como parte del curso Taller de Programación – Maestría en Economía Aplicada (UBA, 2025).*

