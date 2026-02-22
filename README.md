# 🔬 Capital Científico e Identidad Científica
### Revisión Sistemática de Literatura · 2007–2025

> **¿Cómo se ha conceptualizado el capital científico y la identidad científica en la literatura académica entre 2006 y 2025, y qué implicaciones se derivan para la equidad educativa y la innovación social?**

---

## 📌 Descripción del proyecto

Revisión sistemática bibliométrica realizada sobre literatura académica indexada en **OpenAlex**, orientada a mapear la producción global sobre capital científico e identidad científica, identificar tendencias y detectar vacíos temáticos, poblacionales y territoriales — con especial atención al contexto latinoamericano y colombiano.

Este proyecto fue desarrollado como prueba técnica para aspirar al cargo de Investigadora en el **Instituto UNNO – Parque Científico de Innovación Social (UNIMINUTO)** en febrero de 2026.

---

## 🛠️ Herramientas y tecnologías

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C9BE8?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![OpenAlex](https://img.shields.io/badge/Fuente-OpenAlex_API-brightgreen?style=flat)

---

## 📊 Hallazgos principales

| Indicador | Resultado |
|---|---|
| 📄 Artículos analizados | 105 |
| 📅 Período cubierto | 2007 – 2025 |
| 🌍 Países representados | 30+ |
| 🔓 Acceso abierto | 67,6% |
| 📈 Crecimiento último quinquenio | 45,7% de toda la producción en 2021–2025 |
| 🇨🇴 Artículos desde Colombia | 1 |

### 📈 Tendencia temporal
La producción académica muestra **dos momentos de ruptura**: un crecimiento moderado entre 2007 y 2018, y una aceleración notable desde 2019. Los últimos dos años concentran la mayor actividad: **13 artículos en 2024** y **19 en 2025**, lo que indica que el campo está en plena fase de consolidación.

### 🌎 Distribución geográfica
| País | Afiliaciones |
|---|---|
| 🇺🇸 Estados Unidos | 35 |
| 🇪🇸 España | 17 |
| 🇧🇷 Brasil | 16 |
| 🇮🇩 Indonesia | 12 |
| 🇸🇪 Suecia | 13 |
| 🇨🇴 Colombia | 1 |

El predominio norteamericano existe, pero es menos abrumador que en otras áreas del conocimiento. La presencia de España y Brasil señala que el campo **está construyendo voces propias en el mundo hispanohablante y lusófono**.

### 🏷️ Temas dominantes
1. Career Development and Diversity (n=7)
2. Educational Research and Science Teaching (n=5)
3. Science Education and Pedagogy (n=4)
4. Education and Critical Thinking Development (n=4)
5. Science, Technology, and Education in Latin America (n=3)

### 🔍 Vacíos identificados
- **Primera infancia:** solo 2 artículos abordan este nivel educativo, a pesar de que la evidencia señala que las actitudes hacia la ciencia se forman desde edades tempranas.
- **Colombia y América Latina:** subrepresentados estructuralmente en un campo que conceptualmente les concierne de forma directa.
- **Poblaciones vulnerables:** solo 12 artículos abordan género, 4 minorías étnicas y 2 contextos de pobreza.

---

## 📁 Estructura del repositorio

```
📁 capital-cientifico-identidad-cientifica/
├── 📓 analisis_bibliometrico_completo.ipynb   ← análisis y visualizaciones
├── 📊 corpus.csv                              ← corpus limpio (105 artículos)
├── 📄 informe_completo.docx                   ← informe técnico detallado
└── 📝 README.md
```

---

## 🔎 Metodología

La búsqueda se realizó con el enfoque **PICo** (Population, Interest, Context) usando la API de OpenAlex con operadores booleanos en inglés y español:

```
("scientific capital" OR "capital científico") OR
("scientific identity" OR "identidad científica")
AND ("education" OR "educación")
```

**Filtros aplicados:** rango temporal 2006–2025 · tipo de documento: artículo

El análisis computacional incluyó limpieza de datos (deduplicación, tratamiento de nulos, exclusión de registros no pertinentes), análisis exploratorio y ocho visualizaciones interpretadas.

---

## 💡 Reflexión final

La ausencia de Colombia en este corpus no es un dato menor: **es un llamado a la acción**. Para un país con desafíos estructurales en el acceso a la ciencia, y con instituciones comprometidas con la equidad educativa, existe una oportunidad concreta de producir literatura académica situada, contextualizada y con impacto real en las comunidades.

---

*Desarrollado por **Deisy Viviana Hurtado Vega** · Febrero 2026*
*Datos: [OpenAlex](https://openalex.org) · Licencia: MIT*
