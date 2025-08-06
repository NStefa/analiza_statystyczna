# Projekt zaliczeniowy – Statystyka nieparametryczna

## Opis projektu

Projekt został zrealizowany w ramach zaliczenia przedmiotu \*Statystyka nieparametryczna\*. Analizie poddano dane dotyczące \*dwóch rodzajów sera topionego (typ A i typ B)\*, dla których wykonano pomiary zawartości wody w \*trzech punktach czasowych\*: w tygodniu 0, tygodniu 3 oraz tygodniu 5.

Celem projektu było zweryfikowanie następujących hipotez:

- Czy przechowywanie sera A wpływa istotnie na zmniejszenie się w nim zawartości wody? 
- Czy przechowywanie sera B wpływa istotnie na zmniejszenie się w nim zawartości wody?
- Czy różnica w zawartości wody w terminach tydzien 0 i tydzien 3 jest istotna statystycznie?
- Czy różnica w zawartości wody w terminach tydzien 3 i tydzien 5 jest istotna statystycznie
- Jakiego średniego procentu utraty wody można się spodziewać w terminach tydzien 3 i tydzien 5? 

## Metody analizy

W projekcie wykorzystano następujące nieparametryczne testy statystyczne:
- Test Friedmana 
- Test Wilcoxona (zarówno dla prób zależnych, jak i niezależnych)
- Test mediany 
- Testy parowe przy użyciu metody Andersona–Darlinga

## Narzędzia i biblioteki

Analizy przeprowadzono w języku \*R\*, z wykorzystaniem następujących bibliotek:
- `stats` 
- `DescTools` 
- `ggplot2` – wizualizacja danych i trendów
