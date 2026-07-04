# 🎬 Netflix Churn Prediction Model

Predictor de cancelación de clientes Netflix usando Machine Learning.

## 📊 Modelo

- **Algoritmo**: Random Forest Optimizado
- **Recall**: 95.6%
- **F1-Score**: 0.924
- **ROC-AUC**: 0.989
- **Precision**: 0.895

## 📁 Archivos

- `app.py` - Aplicación Streamlit
- `modelo_netflix_churn.pkl` - Modelo entrenado
- `requirements.txt` - Dependencias

## 🛠️ Ejecutar Localmente

```bash
git clone https://github.com/tu_usuario/netflix-churn-predictor.git
cd netflix-churn-predictor
pip install -r requirements.txt
streamlit run app.py
```

Luego abre: http://localhost:8501

## ¿Cómo Usar?

1. Ingresa los datos del cliente
2. Haz click en "Predecir Riesgo de Churn"
3. La app muestra:
   - Probabilidad de cancelación
   - Nivel de riesgo (Bajo, Medio, Alto)
   - Recomendaciones

## 📈 Resultados

- **Riesgo Bajo** (< 0.33): Cliente probablemente permanecerá
- **Riesgo Medio** (0.33 - 0.66): Requiere atención
- **Riesgo Alto** (> 0.66): Acción inmediata

## 📚 Tecnologías

- Python 3.9+
- Streamlit
- Scikit-learn
- Pandas
- Joblib

## 👥 Grupo 3

Proyecto académico de Machine Learning

---

Última actualización: Julio 2026
