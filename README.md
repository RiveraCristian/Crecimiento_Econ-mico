# 📊 Análisis del Crecimiento Económico Regional - Maule

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Estado-Completado-green?style=for-the-badge" alt="Estado">
</div>

## 🎯 Descripción del Proyecto

Análisis completo del crecimiento económico de la **Región del Maule** basado en datos del Producto Interno Bruto (PIB) trimestral, comparando su desempeño con el nivel nacional y generando proyecciones futuras usando modelos avanzados de series de tiempo.

## 📁 Estructura del Proyecto

```
📂 Crecimiento Economico Regional/
├── 📊 Crecimiento_economico_PIB.ipynb    # Notebook principal con análisis completo
├── 📊 Crecimiento_economico_.ipynb       # Notebook adicional
├── 📁 data/
│   └── 📋 Cuadro_03072025235920.xlsx     # Datos PIB regional trimestral
└── 📄 README.md                          # Este archivo
```

## 🔍 Análisis Realizado

### 📈 Análisis Descriptivo
- **Estadísticas descriptivas** del PIB regional vs nacional
- **Tasas de crecimiento** trimestral y anual
- **Análisis de volatilidad** y correlaciones
- **Identificación de períodos** de mayor y menor crecimiento

### 📊 Visualizaciones
- Evolución temporal del PIB (Índice Base 2013=100)
- Comparación del crecimiento anual Maule vs Nacional
- PIB relativo (Maule/Nacional)
- Distribución del crecimiento anual

### 🔬 Análisis Avanzado
- **Análisis de estacionalidad** (Test Kruskal-Wallis)
- **Descomposición estacional** de las series
- **Modelos predictivos avanzados**:
  - Holt-Winters (Triple Exponential Smoothing)
  - SARIMA (Autoregresivo Integrado de Medias Móviles Estacional)
  - STL + Trend (Decomposición Estacional con Tendencia)

### 🔮 Proyecciones
- **Proyecciones a 8 trimestres** (2 años)
- **Intervalos de confianza** para las proyecciones
- **Comparación de modelos** (RMSE, MAE, MAPE)
- **Análisis de incertidumbre**

## 📊 Principales Hallazgos

### 🏆 Desempeño Económico
- **Maule**: Crecimiento promedio **3.27%** anual (mayor volatilidad)
- **Nacional**: Crecimiento promedio **2.07%** anual (menor volatilidad)
- El Maule supera al promedio nacional en **1.2 puntos porcentuales**

### 🌍 Estacionalidad
- **Patrón estacional significativo** en la región del Maule
- **Q3 (Jul-Sep)** es consistentemente el trimestre más débil
- **Q4 (Oct-Dic)** tiende a ser el trimestre más fuerte

### 🎯 Modelos Predictivos
- **SARIMA** y **STL+Trend** muestran mejor desempeño
- **Holt-Winters** es especialmente útil para capturar estacionalidad
- Proyecciones con intervalos de confianza apropiados

## 🛠️ Tecnologías Utilizadas

### 📚 Librerías Principales
- **pandas** & **numpy**: Manipulación y análisis de datos
- **matplotlib** & **seaborn**: Visualizaciones
- **statsmodels**: Modelos de series de tiempo
- **scikit-learn**: Métricas de evaluación
- **scipy**: Análisis estadístico

### 🔧 Modelos Implementados
- **Holt-Winters**: Para tendencia y estacionalidad
- **SARIMA**: Para autocorrelación temporal
- **STL**: Para descomposición estacional robusta




### 🎯 Recomendaciones
1. **Planificar inversión pública** considerando ciclos estacionales
2. **Políticas anticíclicas** para Q3 (trimestre más débil)
3. **Diversificación económica** para reducir estacionalidad
4. **Monitoreo continuo** y actualización de modelos

---

<div align="center">
  <b>🔬 Análisis Económico Regional | 📈 Series de Tiempo | 🎯 Proyecciones</b>
</div>

---

*Desarrollado Por Colabi*
