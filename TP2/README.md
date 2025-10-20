# 📊 Taller de Programación – Trabajo Práctico N°2  
**Universidad de Buenos Aires – Facultad de Ciencias Económicas (FCE-UBA)**  
**Maestría en Economía Aplicada**  
**Año:** 2025  
**Tema:** Histogramas, Kernels y Métodos No Supervisados con la EPH  

---

## 🧩 Descripción General

Este segundo trabajo práctico tiene como propósito **continuar el análisis de la Encuesta Permanente de Hogares (EPH)**, extendiendo la base limpia del TP1 para incluir nuevos indicadores y aplicar **técnicas exploratorias y no supervisadas**.  

Los objetivos principales son:
- Consolidar una base homogénea para los trimestres 2005T1 y 2025T1.  
- Crear variables derivadas (edad², años de educación, horas trabajadas, etc.).  
- Analizar distribuciones mediante histogramas y densidades kernel.  
- Aplicar **PCA** (Análisis de Componentes Principales) y **clustering** (k-means y jerárquico).  

---

## 📁 Estructura del repositorio

TP2/
├── Datos/ # Bases de datos limpias y auxiliares
│ ├── eph_2005T1_limpia.csv
│ └── eph_2025T1_limpia.csv
│
├── Docs/ # Documentación e informe final
│ └── Program_TP2_GrupoX.pdf
│
├── Figuras/ # Salidas gráficas generadas
│ ├── hist_edades.png
│ ├── kernel_ingresos.png
│ ├── pca_scores.png
│ ├── elbow_kmeans.png
│ └── dendrograma.png
│
├── Scripts/ # Código fuente y notebooks
│ └── Program_TP2_GrupoX.ipynb
│
└── README.md # Descripción del trabajo (este archivo)


---

## ⚙️ Dependencias y entorno

Este proyecto fue desarrollado en **Python 3.10+** y requiere las siguientes librerías:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kmodes
