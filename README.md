# TFM - Exploración bioinformática de genes y enzimas degradadores de plásticos

Este repositorio contiene los scripts y análisis desarrollados para el **Trabajo Fin de Máster (TFM)** titulado:

**“Exploración bioinformática de genes y enzimas claves en la degradación de PET, PE, PVC y PP por hongos y bacterias de la plastisfera”**  
Máster Universitario en Bioinformática – Universidad Internacional de La Rioja (UNIR)  
 Año: 2025  
 Autoras: Isabella Cañaveral Sánchez & Laura Juliana Leal Lugo  
 Director: Marcos Lacasa Cascarra

---

## Objetivo del proyecto

Aplicar herramientas bioinformáticas para:

- Identificar genes y enzimas implicadas en la degradación de plásticos sintéticos (PET, PE, PVC, PP)
- Evaluar la diversidad microbiana y sus condiciones ecológicas
- Analizar redes funcionales y de co-ocurrencia entre microorganismos, enzimas y tipos de plásticos
- Construir modelos predictivos de capacidad degradativa usando aprendizaje automático

---

## Estructura del repositorio

| Carpeta/Archivo                          | Descripción                                                                 |
|------------------------------------------|-----------------------------------------------------------------------------|
| `Alga y Beta Diversidad en R/`           | Cálculo de métricas de diversidad microbiana (Shannon, Simpson, etc.)      |
| `Alineamiento/`                          | Alineamiento múltiple de secuencias de enzimas degradadoras                |
| `Análisis ecológico/`                    | Asociaciones entre microorganismos, enzimas y ambientes de aislamiento     |
| `Control de calidad/`                    | Limpieza y depuración de datasets metagenómicos                            |
| `Filtrado y Clasificación/`              | Clasificación taxonómica y funcional de genes y microorganismos            |
| `Predicción y Análisis de redes funcionales en R/` | Modelado predictivo con Random Forest y redes funcionales                 |
| `Red de Co-ocurrencia/`                  | Visualización de redes microbio-enzima-plástico                            |
| `README.md`                              | Este archivo                                                               |

---

##  Herramientas y tecnologías utilizadas

- **Lenguaje principal**: R
- **Librerías clave**:
  - `phyloseq`, `vegan` – análisis ecológico
  - `Biostrings`, `DECIPHER` – alineamiento y filogenia
  - `randomForest`, `caret`, `e1071` – machine learning
  - `igraph`, `ggraph` – redes de co-ocurrencia

---

## Resultados esperados
- Enzimas claves como PETasas, laccasas y cutinasas detectadas
- Árboles filogenéticos de enzimas y especies degradadoras
- Clusters microbianos por ambiente y tipo de polímero
- Red microbio-plástico-enzima
- Modelo de clasificación de capacidad degradativa (Random Forest)

