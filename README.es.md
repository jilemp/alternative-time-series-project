# 📈 Análisis de Series Temporales – Explore.ipynb

Este notebook realiza un análisis exploratorio de una serie temporal. Se construye la estructura adecuada de datos, se analizan tendencias, estacionariedad y otras propiedades estadísticas. Está orientado a propósitos académicos o de análisis técnico, e incluye visualizaciones y diagnósticos básicos.

---

## 📁 Contenido del Archivo

- `explore.ipynb` — Notebook de Jupyter con:
  - Preparación de datos
  - Construcción de la serie temporal
  - Análisis de tendencia
  - Prueba de estacionariedad (ADF test)
  - Análisis de residuos
  - Gráficos y métricas

---

## 🔍 Resumen del Análisis

- **Tensor (unidad de tiempo)**: Diario  
- **Tendencia**: Positiva  
- **Estacionariedad**: No estacionaria (valor p ADF = 0.98)  
- **Variabilidad**: Baja — Residuos relativamente constantes  
- **Autocorrelación**: Alta, disminuyendo con el tiempo  

---

## 🛠 Cómo Ejecutar

1. Clona o descarga el repositorio  
2. Instala las dependencias

```bash
pip install -r requirements.txt
```

3. Ejecuta el notebook

```bash
jupyter notebook "explore.ipynb"
```

---

## 📬 Contacto

¡No dudes en abrir un *issue* o contribuir si quieres expandir el análisis!
