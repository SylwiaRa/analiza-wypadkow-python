# Analiza bezpieczeństwa ruchu drogowego (Ujęcie Kwartalne)

Projekt przedstawia wstępną analizę statystyk wypadków drogowych oraz liczby poszkodowanych z wykorzystaniem języka Python oraz bibliotek analitycznych.

## Cel projektu
Głównym celem było zbadanie trendów oraz zależności pomiędzy liczbą wypadków, liczbą rannych a liczbą ofiar śmiertelnych w poszczególnych kwartałach (na podstawie zbioru `city_7_4_data.csv`).

## Wykorzystane technologie
* **Python 3**
* **Pandas** (wczytywanie, czyszczenie i transformacja danych)
* **Matplotlib** (wizualizacja danych i generowanie wykresów słupkowych)
* **Jupyter Notebook**

## Kluczowe wnioski z analizy
* Dane zostały poprawnie wczytane i zweryfikowane za pomocą funkcji `df.info()` oraz `df.describe()`.
* Wykres typu `kind="bar"` pozwolił zestawić liczbę zdarzeń drogowych z podziałem na osi czasu (kolumna `quarter`).
* Wizualizacja ułatwia szybką identyfikację kwartałów, w których dochodziło do największej liczby niebezpiecznych wypadków.

---
**Autor:** [Sylwia Ratyńska / SylwiaRa]

## Wizualizacja danych
<img width="606" height="362" alt="wykres" src="https://github.com/user-attachments/assets/8ef60952-f7cf-4a6f-8fe5-a65b71636fb3" />
