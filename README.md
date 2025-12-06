# 🛒 Predicción de Categoría de Producto - Tienda Aurelion

## Resumen Rápido

Sistema de **clasificación automática** que predice si un producto pertenece a la categoría **Alimentos** o **Limpieza** utilizando un modelo de Machine Learning.

## ¿Qué Hace?

Analiza características del producto (nombre, precio, cantidad, medio de pago) y clasifica automáticamente su categoría sin intervención manual.

```
✅ Automatización de catalogación
✅ Validación de clasificación
✅ Optimización de procesos
```

## Tecnología Usada

**Algoritmo:** Random Forest Classifier  
**Features:** 6 características simples extraídas automáticamente  
**Dataset:** 343 transacciones de Tienda Aurelion

## 📈 Rendimiento del Modelo

| Métrica | Valor |
|---------|-------|
| **Accuracy** | **94.2%** |
| **Precision** | 94.4% |
| **Recall** | 94.4% |
| **ROC-AUC** | **0.9554** |

> ✨ **Excelente desempeño, listo para producción**

## 🎯 Certeza del Modelo

- 🎖️ **Confiabilidad:** 94.2% de precisión general
- 🎖️ **Discriminación:** ROC-AUC > 0.95 (excepcional)
- 🎖️ **Estabilidad:** Error rate bajo y balanceado en ambas clases
- 🎖️ **Validación:** Testeado en datos independientes (20% del dataset)

**Conclusión:** El modelo es **altamente confiable** para usar en producción.

## 📁 Estructura del Proyecto

```
demo3/
├── programa_act.ipynb              # Código y análisis completo
├── documentacion_act.md            # Documentación detallada
├── modelo_categoria_producto.pkl   # Modelo entrenado
├── base_final.csv                  # Dataset original
└── img/                            # Visualizaciones
    ├── modelo_metricas.png
    └── distribucion_predicciones.png
```

## 🚀 Quick Start

1. **Ver el análisis:** Abre `programa_act.ipynb` en Jupyter
2. **Leer documentación:** Consulta `documentacion_act.md` para detalles técnicos
3. **Usar el modelo:** Carga `modelo_categoria_producto.pkl` en Python

```python
import pickle
with open('modelo_categoria_producto.pkl', 'rb') as f:
    modelo = pickle.load(f)
# Usar modelo.predict(X) para clasificar nuevos productos
```

## 📚 Documentación Completa

Para análisis detallado del proceso, métricas y conclusiones → **[Ver `documentacion_act.md`](documentacion_act.md)**

---

**Proyecto:** Tienda Aurelion Demo 3 | **Modelo:** Random Forest | **Precisión:** 94.2%
