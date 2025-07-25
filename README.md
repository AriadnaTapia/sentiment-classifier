# sentiment-classifier

# 🎬 Film Review Sentiment Classifier

Este proyecto entrena un modelo de machine learning para clasificar reseñas de películas de IMDB como positivas o negativas. El objetivo es ayudar a la comunidad **Film Junky Union** a identificar automáticamente críticas negativas, con un **F1-score mínimo de 0.85**.

---

## 🧠 Modelos probados

- **Model 1**: NLTK + TF-IDF + Logistic Regression  
- **Model 3**: spaCy + TF-IDF + Logistic Regression  
- **Model 4**: spaCy + TF-IDF + LGBMClassifier

### Resultados:
- Los modelos 1 y 3 identifican bien el tono negativo.
- El modelo 4 tiende a confundirse con reseñas ambiguas.
- Todos los modelos detectan bien las reseñas positivas.

---

## ⚙️ Tecnologías

- Python, Jupyter Notebook  
- NLTK, spaCy, TF-IDF  
- Scikit-learn, LightGBM

---

## ✨ Conclusión

El modelo con **Logistic Regression + spaCy** ofrece mejor rendimiento y estabilidad, superando el objetivo de F1 ≥ 0.85.

---

## 👩‍💻 Autora

Ariadna Tapia
