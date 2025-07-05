# Exploración bioinformática de genes y enzimas clave en la degradación de plásticos

Este repositorio contiene el código, scripts en R y python para el Trabajo Fin de Máster (TFM) titulado:

**“Exploración bioinformática de genes y enzimas claves en la degradación de PET, PE, PVC y PP por hongos y bacterias de la plastisfera”**, realizado en el marco del Máster Universitario en Bioinformática de la Universidad Internacional de La Rioja.

Autores:  
- Isabella Cañaveral Sánchez  
- Laura Juliana Leal Lugo  
Director: Marcos Lacasa Cascarra  
Año: 2025

---

## Objetivo

Desarrollar un enfoque bioinformático integral para caracterizar genes y enzimas involucrados en la biodegradación de plásticos (PET, PE, PVC y PP) por microorganismos de la plastisfera, mediante:

- Análisis metagenómico y filogenético
- Evaluación funcional y ecológica
- Visualización de redes de co-ocurrencia
- Modelado predictivo de capacidad degradativa

---

## Estructura del repositorio

Cada carpeta contiene scripts, datos de entrada/salida y documentación asociada a diferentes etapas del análisis:

- **`Alga y Beta Diversidad en R/`**: Cálculo de diversidad alfa y beta para las comunidades microbianas asociadas.
- **`Alineamiento/`**: Alineamiento múltiple de secuencias de enzimas y genes degradadores.
- **`Análisis ecológico/`**: Relación entre microorganismos, ambientes de aislamiento y condiciones físico-químicas.
- **`Control de calidad/`**: Scripts para filtrado y evaluación de calidad del dataset metagenómico/genómico.
- **`Filtrado y Clasificación/`**: Limpieza de datos, normalización y clasificación taxonómica/funcional.
- **`Predicción y Análisis de redes funcionales en R/`**: Modelos de machine learning para capacidad degradativa.
- **`Red de Co-ocurrencia/`**: Visualización de redes microbio-enzima-plástico mediante co-ocurrencia.

---

##  Herramientas utilizadas

- **Lenguaje principal**: R  y Python
- **Bibliotecas clave**:
  - `phyloseq`, `vegan` – Análisis de diversidad microbiana
  - `Biostrings`, `DECIPHER` – Alineamientos y análisis de secuencias
  - `ggraph`, `igraph` – Visualización de redes
  - `randomForest`, `caret` – Modelado predictivo
- **Datos**: Bases de datos públicas (Plastic DB)

