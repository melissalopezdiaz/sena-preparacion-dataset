# Preparación de Dataset para Modelos de Inteligencia Artificial

**Programa:** SENA — Procesamiento de Datos para Modelos de IA  
**Aprendiz:** Melissa  
**Periodo:** Mayo – Junio 2026  

## Descripción
Proyecto de preparación de un dataset de clientes para entrenamiento de modelos de IA.
Incluye codificación de variables categóricas, escalamiento numérico y separación train/test.

## Técnicas aplicadas
- One-Hot Encoding (variables nominales)
- OrdinalEncoder (NivelSatisfaccion)
- StandardScaler y RobustScaler
- Train/Test Split con estratificación

## Estructura
- `data/raw/` — dataset original limpio
- `data/processed/` — datasets preparados para entrenamiento y prueba
- `notebooks/` — notebook principal del proyecto
- `reports/` — informe técnico final

## Cómo ejecutar
1. Abrir `notebooks/notebook_preparacion_dataset.ipynb` en VS Code o Jupyter
2. Cargar el dataset desde `data/raw/`
3. Ejecutar celdas en orden
4. Verificar exportación en `data/processed/`
