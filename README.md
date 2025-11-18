# Práctica de Examen - Estadística Descriptiva

## Descripción
Este proyecto contiene un análisis práctico y exhaustivo para preparación de examen en Estadística Descriptiva. Consiste en la resolución de items de examen basados en datos reales de matrículas de educación superior en la región de Valparaíso durante 2021.

El material busca consolidar conceptos fundamentales de estadística descriptiva mediante el análisis de datos reales, incluyendo medidas de asociación, probabilidades condicionales, distribuciones, correlación lineal y visualización de datos.

## Información del Curso
- **Ramo**: Estadística Descriptiva
- **Profesor**: Andrés Millán

## Integrantes del Grupo
- Lucas Moncada
- César Rojas
- Alex Leal
- Cristian Lizama

## Temática y Objetivos

### Dataset
El análisis se desarrolla sobre **datos de matrículas de educación superior en Valparaíso 2021**, que incluye información sobre:
- Valores de matrícula y arancel de programas académicos
- Modalidades de estudio (presencial, semipresencial, no presencial)
- Tipo de institución (universidades, institutos profesionales, centros de formación técnica)
- Duración de carreras
- Área de conocimiento
- Nivel de estudio (pregrado, postgrado, postítulo)
- Información demográfica (género)

### Items de Análisis

#### **Ítem 1: Relaciones entre valores económicos y duración**
Explora correlaciones entre:
- Matrícula vs Arancel: análisis de correlación Pearson, modelos lineales simples y comparación por área de conocimiento
- Arancel vs Duración: evaluación de si carreras más largas son más costosas y si esta relación se mantiene en todas las áreas

#### **Ítem 2: Modalidades y probabilidades**
Analiza:
- Distribución de modalidades de estudio y prevalencia de presencialidad
- Asociación entre tipo de institución y adopción de modalidades no exclusivamente presenciales
- Probabilidades condicionales: relación entre nivel de estudio, género y distribución de estudiantes

#### **Ítem 3: Distribución del valor de arancel**
Examina propiedades estadísticas:
- Medidas de tendencia central y dispersión (media, desviación estándar)
- Asimetría y curtosis para evaluar desviación de normalidad
- Aproximación mediante distribución Normal para cálculos de probabilidad

## Contenido

| Archivo | Descripción |
|---------|-------------|
| `preguntas_items_examen.ipynb` | Notebook interactivo con resolución completa de los 3 items de examen, incluyendo análisis numéricos, visualizaciones e interpretaciones |
| `06_MATRICULAS_ED_SUPERIOR_VALPARAISO_2021.xlsx` | Dataset fuente con datos de matrículas (debe estar en la misma carpeta) |

## Instalación y Ejecución

### Requisitos previos
- Python 3.7 o superior
- pip (gestor de paquetes de Python)

### Pasos para instalar y ejecutar

1. **Clonar o descargar el repositorio**
   ```bash
   git clone https://github.com/Cesitar16/Estadistica_ExamPractice.git
   cd Estadistica_ExamPractice
   ```

2. **Crear un entorno virtual (recomendado)**
   ```bash
   python -m venv venv
   ```
   
   - En Windows (PowerShell):
     ```powershell
     .\venv\Scripts\Activate.ps1
     ```
   - En macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

3. **Instalar las dependencias**
   ```bash
   pip install -r requirements.txt
   ```

4. **Asegurar que el archivo de datos está disponible**
   - Coloca el archivo `06_MATRICULAS_ED_SUPERIOR_VALPARAISO_2021.xlsx` en la misma carpeta del proyecto

5. **Ejecutar el notebook**
   
   **Opción A: Jupyter Notebook**
   ```bash
   jupyter notebook preguntas_items_examen.ipynb
   ```
   
   **Opción B: JupyterLab**
   ```bash
   jupyter lab preguntas_items_examen.ipynb
   ```
   
   **Opción C: VS Code**
   - Abre VS Code en la carpeta del proyecto
   - Instala la extensión "Jupyter" de Microsoft
   - Abre el archivo `preguntas_items_examen.ipynb`
   - Ejecuta las celdas en orden presionando Shift + Enter

6. **Ejecutar todas las celdas**
   - En Jupyter/JupyterLab: Click en `Kernel` → `Restart & Run All`
   - En VS Code: Click en `Run All` o ejecuta celda por celda

## Metodología

El proyecto utiliza:
- **Análisis explorador de datos (EDA)**: inspección de distribuciones y relaciones
- **Análisis de correlación**: coeficientes de Pearson y modelos lineales simples
- **Probabilidad e inferencia**: tablas de contingencia, probabilidades condicionales, distribuciones teóricas
- **Visualización**: gráficos de dispersión, histogramas, gráficos de barras con interpretaciones detalladas

Cada sección incluye justificación de métodos, interpretación visual y comentarios estadísticos.
