# Opis datasetów użytych w EDA

## Dataset 1: GP Practice Population Demographics (Scotland)
**Źródło:** Public Health Scotland (PHS) – “GP Practice Population Demographics”  
**Typ danych:** Tabular (dane tabelaryczne) + Text (etykiety regionów)

### Co zawiera dataset
Liczebności list pacjentów przypisanych do praktyk GP w Szkocji z podziałem na płeć i grupy wieku oraz etykiety geograficzne (HB/HSCP).

### Dlaczego pasuje do tematu pracy
Struktura demograficzna populacji praktyki GP jest naturalnym czynnikiem wpływającym na przepływy pacjentów do opieki szpitalnej.

### Pliki użyte w EDA
- Plik scalony: `gp_practice_population_demographics_23colfiles_merged_wide.xlsx` (29 plików źródłowych, 23 kolumny)

### Zakres czasowy (dla wersji 23-kolumnowej)
2014-01-01 do 2021-07-01 (dane kwartalne)

### Kluczowe kolumny (przykładowo)
- `Date`
- `PracticeCode`
- `HB`
- `HSCP`
- `Sex`
- kolumny z grupami wieku (np. `AllAges`, `Age0to4`, …, `Age85plus`)
- kolumny jakości `*QF` (jeśli występują)

### Uwagi / ograniczenia
W publikacji występują warianty schematu (z różną ilością kolumn). W tej analizie wykorzystuję spójny wariant 23-kolumnowy.
