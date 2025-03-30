# Analiza Zależności Między Bezrobociem a Samobójstwami

## Wprowadzenie
Projekt bada zależność między stopą bezrobocia a odsetkiem samobójstw w poszczególnych województwach Polski w latach 1999–2024. Analiza opiera się na danych statystycznych GUS dotyczących:
- Bezrobocia rejestrowanego (z podziałem na płeć)
- Liczby zgonów z powodu samobójstw

Celem było sprawdzenie, czy istnieje istotna korelacja między bezrobociem a zdrowiem psychicznym społeczeństwa oraz identyfikacja czynników wpływających na to zjawisko.

## Dane
Zbiory danych użyte w analizie:
- **Stopa bezrobocia** – dane z GUS, uwzględniające województwa i płeć
- **Samobójstwa** – dane GUS o liczbie samobójstw w podziale na województwa

Analiza obejmuje lata 1999–2024, pozwalając na identyfikację długoterminowych trendów i wpływu kluczowych wydarzeń, np. pandemii COVID-19.

## Metodologia
- **Przetwarzanie danych**: Dane zostały załadowane i oczyszczone w Jupyter Notebook.
- **Analiza statystyczna**: Obliczono współczynniki korelacji między stopą bezrobocia a liczbą samobójstw.
- **Wizualizacja danych**: Wykresy i mapy w Tableau oraz wykresy generowane w Pythonie.

## Wykorzystane technologie
- **Python** (pandas, matplotlib, seaborn, numpy)
- **Jupyter Notebook**
- **Tableau** (do wizualizacji danych)

## Wyniki
- Znaleziono pewne korelacje między wzrostem bezrobocia a wzrostem liczby samobójstw w niektórych okresach.
- Pandemia COVID-19 miała zauważalny wpływ na wzrost samobójstw.
- Istnieją różnice w zależności od płci oraz regionu.

## Uruchomienie
1. Pobierz repozytorium.
2. Upewnij się, że masz zainstalowane wymagane biblioteki:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Uruchom Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Otwórz plik `analysis.ipynb` i wykonaj kolejne komórki.
