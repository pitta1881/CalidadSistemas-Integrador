# Proyecto Integrador - Calidad de los Sistemas de Información

Este repositorio contiene dos proyectos de análisis de calidad aplicando herramientas estadísticas y de mejora continua.

## 📋 Estructura del Repositorio

```
.
├── wines/
│   ├── data/
│   │   └── raw/
│   │       ├── redwine.csv
│   │       └── whitewine.csv
│   └── src/
│       └── wines.ipynb
│
├── electricComponents/
│   ├── data/
│   │   └── raw/
│   │       └── electricErrors.csv
│   └── src/
│       └── electricComponents.ipynb
│
├── requirements.txt
└── README.md
```

## 🎯 Objetivos del Repositorio

### Proyecto 1: Análisis de Calidad de Vinos

**Contexto:** El área de marketing busca alcanzar puntuaciones específicas de calidad: 8 puntos para vinos blancos y 7 puntos para vinos tintos.

**Objetivo:** Analizar el proceso de fabricación de vinos mediante técnicas de control de calidad para:

- Identificar las posibles causas que afectan la calidad de los vinos
- Determinar los valores óptimos de las variables de proceso
- Proponer un proyecto de mejora para alcanzar los objetivos de marketing

**Herramientas de Calidad Aplicables:**

- Lista de Verificación
- Histograma
- Diagrama de Pareto
- Diagrama de Flujo
- Diagrama de Causa-Efecto
- Diagrama de Control
- Diagrama de Dispersión

### Proyecto 2: Optimización del Proceso de Inspección de Componentes Eléctricos

**Contexto:** Proceso de inspección actual con muestreo cada 15 minutos y costo de U$S 1.5 por inspección. Se clasifican defectos en Mayores (funcionales) y Menores (estéticos).

**Objetivo:** Evaluar y optimizar el proceso de inspección para:

- Explorar la eficiencia del proceso actual
- Reducir los costos de inspección
- Minimizar la ocurrencia de defectos menores
- Recomendar acciones de mejora a la gerencia

**Herramientas de Calidad Aplicables:**

- Lista de Verificación
- Histograma
- Diagrama de Pareto
- Diagrama de Flujo
- Diagrama de Causa-Efecto
- Diagrama de Control
- Diagrama de Dispersión

## 🚀 Instalación y Uso

### Requisitos Previos

- Python 3.8 o superior
- pip

### Instalación de Dependencias

```bash
# Crear entorno virtual (opcional pero recomendado)
python -m venv .venv

# Activar entorno virtual
# En Windows PowerShell:
.\.venv\Scripts\Activate.ps1
# En Windows CMD:
.\.venv\Scripts\activate.bat
# En Linux/Mac:
source .venv/bin/activate

# Instalar dependencias
pip install -r requirements.txt
```

### Ejecutar los Notebooks

```bash
# Iniciar Jupyter Notebook
jupyter notebook

# Navegar a:
# - wines/src/wines.ipynb para el análisis de vinos
# - electricComponents/src/electricComponents.ipynb para el análisis de componentes eléctricos
```

## 📊 Datasets

### Wines Dataset

- **redwine.csv**: Datos de vinos tintos con variables fisicoquímicas y calidad sensorial
- **whitewine.csv**: Datos de vinos blancos con variables fisicoquímicas y calidad sensorial

**Variables incluidas:** Acidez fija, acidez volátil, ácido cítrico, azúcar residual, cloruro, dióxido de azufre libre/total, densidad, pH, sulfatos, alcohol, y calidad.

### Electric Components Dataset

- **electricErrors.csv**: Registro de inspecciones con defectos menores detectados por día y hora

**Variables incluidas:** ID del componente, hora de inspección, y defectos menores por día (10 días).

## 📈 Metodología

Ambos proyectos aplican metodologías de control y mejora de calidad basadas en:

- Análisis exploratorio de datos
- Visualización de variables y patrones
- Aplicación de herramientas estadísticas de calidad
- Identificación de causas raíz
- Propuestas de mejora basadas en evidencia
