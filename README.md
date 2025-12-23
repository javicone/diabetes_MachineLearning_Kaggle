
# README - Práctica PR2

## Descripción
Esta práctica contiene ejercicios para aprender conceptos fundamentales de programación en Python. Los ejercicios se ejecutan en un entorno Jupyter Notebook.

## Resumen de la Práctica

- **Objetivo:** Clasificar la presencia de diabetes en pacientes usando el conjunto de datos [diabetes.csv](diabetes.csv). Se plantea un problema de clasificación binaria (clase 1 = diabetes, clase 0 = sano).
- **Archivos principales:** Notebook con el desarrollo: [practica2_JavierCR.ipynb](practica2_JavierCR.ipynb) y el dataset [diabetes.csv](diabetes.csv).
- **Modelos evaluados:** Regresión Logística y Random Forest (entre otros experimentos). Se incluye tratamiento de desbalance con técnicas como SMOTE-ENN en algunos experimentos.
- **Métricas usadas:** Accuracy, Precision, Recall (Sensibilidad), F1-Score — con atención especial a Recall para tareas médicas (cribado).
- **Conclusión práctica:** Se analizan trade-offs entre maximizar la detección de enfermos (alto Recall) y minimizar falsos positivos (Precisión). Algunos modelos (p. ej. Random Forest con SMOTE-ENN) ofrecen muy alto Recall útil para screening, pero requieren pruebas confirmatorias debido a su mayor tasa de falsos positivos.

## Requisitos
- Python 3.8+
- Jupyter Notebook
- Virtual Environment (venv)

## Instalación

### 1. Crear el entorno virtual
```bash
python -m venv venv
```

### 2. Activar el entorno virtual

**Windows:**
```bash
venv\Scripts\activate
```

**Linux/macOS:**
```bash
source venv/bin/activate
```

### 3. Instalar dependencias
```bash
pip install jupyter notebook
pip install -r requirements.txt
```

## Ejecución

1. Asegúrate de que el venv esté activado
2. Inicia Jupyter Notebook:
```bash
jupyter notebook
```

3. Abre el archivo `practica.ipynb` en tu navegador
4. Ejecuta las celdas con `Shift + Enter`

## Contenido
- Ejercicio 1: [Descripción]
- Ejercicio 2: [Descripción]
- Ejercicio 3: [Descripción]

## Notas
Modifica el contenido según tus necesidades específicas.
