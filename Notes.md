### One-Hot Encoding
One-Hot Encoding zamienia każdą kategorię na osobną kolumnę zawierającą wartości 0 lub 1. Nie wprowadza żadnej sztucznej kolejności między kategoriami.

Najczęściej używaj One-Hot Encoding dla:
- Logistic Regression
- Linear Regression / Ridge / Lasso
- SVM
- KNN
- Neural Networks
- modeli, które liczą odległości lub operacje liniowe

### Label Encoding
Label Encoding przypisuje każdej kategorii konkretną wartość liczbową, np. Bike = 0, Car = 1, Scooter = 2. Jest prostszy i nie zwiększa liczby kolumn, ale może sugerować nieistniejącą kolejność między kategoriami.

Najczęściej używaj Label Encoding dla:
- Decision Tree
- Random Forest
- XGBoost
- LightGBM
- CatBoost (choć CatBoost ma własną obsługę kategorii i najlepiej przekazać mu kategorie bez ręcznego label encodingu)