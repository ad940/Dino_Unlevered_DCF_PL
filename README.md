# Dino_Unlevered_DCF

To repozytorium zawiera mój model wyceny DCF spółki Dino Polska przygotowany w Excelu.

---

## Opis projektu

Projekt przedstawia wycenę Dino Polska metodą nielewarowanych zdyskontowanych przepływów pieniężnych. Dino Polska to polska spółka z sektora handlu detalicznego artykułami spożywczymi. Model prognozuje wyniki finansowe spółki, oblicza wolne przepływy pieniężne dla przedsiębiorstwa, szacuje WACC oraz wyznacza implikowaną wartość kapitału własnego na akcję.

Głównym celem projektu nie było wyłącznie obliczenie wyceny, ale również zbudowanie przejrzystego i zrozumiałego modelu, który może zostać sprawdzony przez inną osobę. Starałem się zachować praktyczną strukturę: dane historyczne, założenia, prognozowane sprawozdania finansowe, WACC, wynik wyceny DCF, analiza scenariuszowa oraz tabele wrażliwości są rozdzielone na czytelne sekcje.

---

## Zawartość repozytorium

| Plik | Opis |
|---|---|
| `Dino_Polska_DCF_Valuation_EN.xlsx` | Angielska wersja modelu wyceny w Excelu |
| `screenshots/` | Zrzuty ekranu wyników modelu, dashboardu oraz analizy wrażliwości |

---

## Funkcjonalności modelu

Model obejmuje:

- analizę historycznych danych finansowych
- prognozowanie przychodów i marż
- założenia dotyczące amortyzacji, nakładów inwestycyjnych oraz kapitału obrotowego
- kalkulację nielewarowanych wolnych przepływów pieniężnych
- kalkulację WACC
- kalkulację wartości rezydualnej
- implikowaną wartość przedsiębiorstwa oraz wartość kapitału własnego
- implikowaną wartość na akcję
- analizę scenariuszową
- analizę wrażliwości
- podstawowe kontrole poprawności modelu

---

## Metodyka wyceny

Wycena opiera się na podejściu nielewarowanych wolnych przepływów pieniężnych dla przedsiębiorstwa.

Wolne przepływy pieniężne dla przedsiębiorstwa są obliczane jako:

```text
FCFF = EBIT × (1 - Stopa podatkowa) + Amortyzacja - Nakłady inwestycyjne - Zmiana kapitału obrotowego netto
