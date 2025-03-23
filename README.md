# Projekt analizy danych - Przewidywanie typu kawy

## Autorzy

- **Patrycja Mazur**
- **Weronika Poniedziałek**

## Opis projektu

Projekt realizowany w ramach przedmiotu XYZ na uczelni ABC. Polega na analizie danych sprzedaży kawy w celu opracowania modeli predykcyjnych do przewidywania typu kawy na podstawie cech takich jak wielkość opakowania, typ palenia, cena za jednostkę itp.

## Zbiór danych

Analizujemy zbiór *CoffeeOrdersData* pochodzący z Kaggle:

- [Link do zbioru danych](https://www.kaggle.com/datasets/rashid7274/data-analysis-on-coffee-sales-data)

Zbiór składa się z trzech głównych arkuszy:

1. **Orders Data** – zawiera szczegóły zamówień (ID produktu, data zamówienia, wartość sprzedaży itp.)
2. **Customers Data** – informacje o klientach (imię, miasto, karta lojalnościowa itp.)
3. **Products Data** – dane o produktach (typ kawy, typ palenia, rozmiar kawy, marża zysku itp.)

## Cel projektu

- Identyfikacja kluczowych cech wpływających na wybór kawy przez klientów.
- Opracowanie modeli klasyfikacyjnych w celu przewidywania typu kawy.
- Sprawdzenie wpływu różnych technik analizy (np. redukcji wymiarów, normalizacji danych) na jakość modeli.

## Wykorzystane technologie

- **Język programowania**: Python (testowany na wersji 3.9+)
- **Biblioteki**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `pycaret` (wykorzystywany do automatycznego strojenia modeli)
- **Techniki analizy**: Statystyki opisowe, wykrywanie brakujących wartości i outlierów, PCA, ICA, normalizacja i standaryzacja danych.

## Struktura projektu

1. **Eksploracyjna analiza danych (EDA)**: Statystyki opisowe, wizualizacje danych, analiza brakujących wartości.
2. **Przetwarzanie danych**: Czyszczenie, usuwanie kolumn o niskiej wariancji, redukcja wymiarów.
3. **Modelowanie**: Implementacja modeli klasyfikacyjnych (*Gradient Boosting, Decision Tree, Random Forest, Extra Trees*).
4. **Optymalizacja**: Testowanie różnych metod redukcji wymiarowości (*PCA, ICA*) oraz normalizacji danych.
5. **Ocena modeli**: Porównanie skuteczności modeli za pomocą metryk, takich jak dokładność (*accuracy*), F1-score i AUC.
6. **Raport końcowy**: Podsumowanie wyników i wniosków.

## Wyniki i wnioski

- Zastosowanie redukcji wymiarów (PCA, ICA) miało istotny wpływ na skuteczność modeli.
- Random Forest okazał się najskuteczniejszym modelem predykcyjnym.
- Oczyszczone i znormalizowane dane pozwoliły osiągnąć lepsze wyniki klasyfikacji.
