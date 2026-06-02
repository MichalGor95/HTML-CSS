# Samouczek HTML & CSS - Kwalifikacja INF.03

Praktyczny, interaktywny samouczek stworzony z myślą o uczniach techników informatycznych przygotowujących się do egzaminu zawodowego z kwalifikacji **INF.03** (*Tworzenie i administrowanie stronami i bazami danych oraz aplikacjami internetowymi*).

---

## O Projekcie

Projekt stanowi kompletne kompendium wiedzy z zakresu strukturyzacji dokumentów HTML5 oraz stylowania CSS3. Został przygotowany w oparciu o oficjalną podstawę programową oraz arkusze egzaminacyjne z poprzednich lat. 

Wszystkie podstrony i przykłady kodu zostały napisane w czystym kodzie (Vanilla HTML & CSS), bez użycia zewnętrznych bibliotek czy frameworków, co jest kluczowe z punktu widzenia wymagań Centralnej Komisji Egzaminacyjnej (CKE).

---

## 🛠️ Stos Technologiczny i Live Demo

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![INF.03](https://img.shields.io/badge/Egzamin-INF.03-2f7a67?style=for-the-badge)

### 🔗 Wersja Demonstracyjna (Live Demo)
Aplikacja została wdrożona i jest dostępna publicznie pod adresem:  
**[michalgor95.github.io/HTML-CSS](https://michalgor95.github.io/HTML-CSS/)**

---

## Główne Cechy Samouczka

- **Zgodność z CKE:** Zakres materiału dokładnie odpowiada wymaganiom egzaminu praktycznego INF.03.
- **Podział na sekcje:** Czytelny podział na 20 rozdziałów HTML i 17 rozdziałów CSS.
- **Baza wiedzy:** Tabele dopuszczalnych wartości, definicje atrybutów globalnych oraz przykłady kodu gotowe do skopiowania.
- **Interaktywność:** Praktyczne przykłady wbudowane bezpośrednio w podstrony (np. interaktywna mapa odsyłaczy, animacje, transformacje).
- **Semantyka i Dostępność:** Kod napisany z poszanowaniem struktury semantycznej (HTML5) oraz wytycznych dostępności (WCAG).

---

## Struktura Projektu

Projekt został zorganizowany w przejrzystą strukturę katalogów w celu oddzielenia głównej nawigacji od podstron szczegółowych:

```text
.
├── index.html          # Strona główna samouczka
├── html.html           # Spis treści i nawigacja dla rozdziałów HTML
├── css.html            # Spis treści i nawigacja dla rozdziałów CSS
├── style.css           # Wspólny, zunifikowany arkusz stylów CSS
├── README.md           # Dokumentacja projektu (ten plik)
├── html/               # Podstrony szczegółowe z zakresu HTML (20 rozdziałów)
│   ├── wprowadzenie.html
│   ├── struktura.html
│   ├── naglowki.html
│   └── ... (pozostałe pliki HTML)
└── css/                # Podstrony szczegółowe z zakresu CSS (17 rozdziałów)
    ├── wprowadzeniecss.html
    ├── selektorycss.html
    ├── transformacje.html
    └── ... (pozostałe pliki CSS)
```

---

## Omówione Zagadnienia

### HTML (20 Rozdziałów)
1. Wprowadzenie do języka HTML
2. Podstawowa struktura dokumentu (`!DOCTYPE`, `html`, `head`, `body`)
3. Nagłówki (`h1`-`h6`) i akapity (`p`, `br`, `hr`)
4. Formatowanie tekstu (`strong`, `em`, `mark`, indeksy)
5. Odnośniki i kotwice (`a`, `href`, `target`)
6. Obrazy i mapy odsyłaczy (`img`, `map`, `area`, współrzędne)
7. Listy punktowane i numerowane (`ul`, `ol`, `li`)
8. Tabele (`table`, `tr`, `td`, `th`, scalanie komórek)
9. Kontenery blokowe i liniowe (`div`, `span`)
10. Semantyka HTML5 (`header`, `nav`, `main`, `section`, `footer`)
11. Formularze - podstawy (`form`, `action`, `method`)
12. Formularze - pola tekstowe (`input` text, email, password)
13. Formularze - wybór opcji (`checkbox`, `radio`, `select`, `textarea`)
14. Przyciski formularza (`button`, `submit`, `reset`)
15. Multimedia (`audio`, `video`)
16. Osadzanie treści (`iframe`)
17. Menu i struktura nawigacji strony
18. Integracja HTML z CSS i JS
19. Atrybuty globalne (`id`, `class`, `style`, `title`, `hidden`)
20. Dobre praktyki oraz walidacja kodu

### CSS (17 Rozdziałów)
1. Wprowadzenie do CSS (składnia, komentarze, metody dołączania)
2. Selektory CSS (tagi, klasy, identyfikatory, grupowanie)
3. Kolory i tła (RGB, HEX, HSL, grafiki tła)
4. Typografia i czcionki (`font-family`, `font-size`, `font-weight`)
5. Model pudełkowy (`margin`, `padding`, `border`, `box-sizing`)
6. Jednostki miar (`px`, `%`, `em`, `rem`, `vw`, `vh`)
7. Zachowanie elementów (`display`, `visibility`)
8. Stylizacja list i tabel (`list-style`, obramowania)
9. Pseudoklasy i pseudoelementy (`:hover`, `:focus`, `::before`, `::after`)
10. Stylowanie formularzy i pól formularza
11. Obrazy i media w CSS (`object-fit`, responsywność)
12. Pozycjonowanie elementów (`static`, `relative`, `absolute`, `fixed`, `sticky`, `z-index`)
13. Układ Flexbox (`justify-content`, `align-items`, `gap`)
14. Dwuwymiarowa siatka CSS Grid (`grid-template`, `fr`)
15. Responsywność strony (media queries, Mobile First, płynne siatki)
16. Transformacje i przejścia (`transform`, `translate`, `scale`, `rotate`, `transition`)
17. Animacje CSS (`@keyframes`, `animation-duration`, `animation-iteration-count`)

---

## Jak Uruchomić Projekt Lokalnie

1. Sklonuj to repozytorium na swój dysk:
   ```bash
   git clone https://github.com/michalgor95/HTML-CSS.git
   ```
2. Przejdź do folderu z projektem:
   ```bash
   cd HTML-CSS
   ```
3. Otwórz plik `index.html` bezpośrednio w dowolnej przeglądarce internetowej (np. Chrome, Firefox, Edge). Projekt nie wymaga instalacji żadnych dodatkowych zależności ani uruchamiania lokalnego serwera.

---

## Autor

Projekt opracował: **Michał Goraj**  
*Projekt został przygotowany w celach edukacyjnych, jako pomoc naukowa do egzaminu INF.03.*
