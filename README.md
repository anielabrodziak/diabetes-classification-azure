# Klasyfikacja diabetyków – projekt w Azure ML

## Opis projektu
Projekt wykonany w ramach zajęć z uczenia maszynowego.  
Celem było stworzenie modelu przewidującego występowanie cukrzycy na podstawie danych medycznych pacjentów.

Dane: [Diabetes Dataset – Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)  
Oryginalne źródło: National Institute of Diabetes and Digestive and Kidney Diseases.

---

## Zastosowane metody
- Wstępna analiza danych (statystyki opisowe, rozkłady, korelacje, outliery)  
- Obsługa braków danych (`NaN` → KNN Imputer)  
- Normalizacja danych (MinMaxScaler)  
- Zrównoważenie klas (SMOTE)  
- Trening i testy modeli klasyfikacyjnych  
- Najlepsze wyniki uzyskano dla **Two-Class Decision Forest**  

---

## Wyniki końcowego modelu
- **Accuracy:** 79,2%  
- **Recall (czułość):** 85,2%  
- **Precision (precyzja):** 65,7%  
- **F1-score:** 0.742  
- **ROC AUC:** 0.885  

Interpretacja: Model dobrze identyfikuje osoby chore (wysoka czułość), co jest kluczowe w zastosowaniach medycznych.

---
## Pełne sprawozdanie
 [(PDF)](diabetes_classification.pdf)

---
