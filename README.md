# 📊 Analiza EDA oraz Wykrywanie Anomalii Rynkowych: Airbnb NYC 2019 (Python & SQL)

## 📌 O projekcie
Projekt stanowi kompleksową analizę eksploracyjną (EDA) oraz proces czyszczenia danych dotyczących aktywności ofert Airbnb w Nowym Jorku w 2019 roku. Głównym celem aplikacji/skryptu jest identyfikacja wzorców zachowań rynkowych, segmentacja ofert pod kątem lokalizacji i typu zakwaterowania, a także wykrywanie oraz izolowanie anomalii cenowych (outlierów), które mogą negatywnie wpływać na późniejsze modele predykcyjne.

Projekt łączy w sobie elastyczność bibliotek data science w języku **Python** z precyzją zapytań **SQL**, tworząc spójny rurociąg (pipeline) przetwarzania i walidacji danych rynkowych.

---

## 🚀 Główne funkcje i zakres analizy

* **Zaawansowane czyszczenie danych (Data Cleaning):** Automatyczna obsługa brakujących wartości (m.in. w kolumnach `last_review` oraz `reviews_per_month`) oraz przygotowanie spójnego zbioru docelowego `airbnb_clean`.
* **Hybrydowe przetwarzanie Python + SQL:** Wykorzystanie zapytań SQL do agregacji danych rynkowych, filtrowania rekordów oraz szybkiej segmentacji ofert bezpośrednio w środowisku analitycznym.
* **Analiza asymetrii i rozkładu cen:** Identyfikacja silnej asymetrii cenowej na rynku nowojorskim wraz z wyodrębnieniem "długiego ogona" tworzonego przez oferty o ekstremalnych wartościach.
* **Wykrywanie anomalii rynkowych (Outliers Detection):** Detekcja nietypowych ofert (np. bardzo wysoka cena przy zerowej liczbie recenzji lub rygorystycznych wymogach dotyczących minimalnej liczby nocy `minimum_nights`), które mogą wskazywać na błędy systemowe, spam lub blokowanie kalendarza.
* **Segmentacja geograficzna i strukturalna:** Szczegółowa analiza wpływu głównych dzielnic (Manhattan, Brooklyn, Queens, Bronx, Staten Island) oraz typów pokojów (`Entire home/apt`, `Private room`) na wahania i zmienność cenową.
* **Walidacja ETL:** Sformułowanie rekomendacji i reguł walidacyjnych dla procesów inżynierii danych w celu automatycznego odrzucania lub oznaczania podejrzanych rekordów.