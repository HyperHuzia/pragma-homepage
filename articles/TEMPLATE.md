# TEMPLATE ARTYKUŁU — Pragma.AI

Ten plik to instrukcja dla agenta (Kamila) tworzącego nowe artykuły.
NIE PUBLIKUJ tego pliku — służy tylko jako wzorzec.

---

## Nazwa pliku

`YYYY-MM-DD-tytul-artykulu-kebab-case.md`

Przykład: `2026-04-15-dlaczego-twoj-crm-jest-martwy.md`

---

## Struktura artykułu

```markdown
# [Tytuł — krótki, konkretny, bez clickbaitu]

*[Data] | Pragma.AI*

---

[Lead — 2-3 zdania. Haczyk, który tłumaczy dlaczego czytelnik powinien czytać dalej.
Musi nawiązywać do realnego problemu biznesowego.]

## [Sekcja 1 — Problem / kontekst]

[Opis problemu z konkretnymi przykładami. Dane, nazwiska, daty.]

## [Sekcja 2 — Dlaczego to ważne]

[Pogłębienie problemu. Mechanizmy, konsekwencje dla biznesu.]

## [Sekcja 3 — Jak to wygląda w praktyce]

[Konkretne scenariusze, porównania, case studies.]

## [Sekcja 4 — Co z tego wynika / Wnioski]

[Podsumowanie, call to action, pytanie do czytelnika.]

---

*[Źródło / inspiracja z linkiem]*
```

---

## Wymagania

### Długość
- **600–900 słów** (polski tekst)
- **4–6 sekcji** z nagłówkami H2
- **57–125 linii** markdown

### Język i styl
- Pisz po polsku, naturalnie, jak kolumna w branżowym magazynie
- **Zero** sztucznego entuzjazmu, zero wykrzykników, zero "rewolucja AI!"
- Ton: konkretny, trochę cyniczny, merytoryczny
- Zdania krótkie i średnie. Bez akademickiego żargonu
- Dopuszczalne: potoczne zwroty ("worek bez dna", "ani rusz")
- Niedopuszczalne: "w dzisiejszych czasach", "jak wszyscy wiemy", "nie da się ukryć"
- Pisz jakby to pisał doświadczony konsultant, nie marketer
- **Bold** na kluczowych tezach, nie na ozdobnikach

### Źródła (OBOWIĄZKOWE)
- Każdy artykuł MUSI mieć co najmniej **1 źródło z linkiem**
- Preferowane: natesnewsletter.substack.com, raporty branżowe, artykuły techniczne
- Źródło podawane na końcu artykułu w formacie:
  `*Artykuł powstał na podstawie [opis źródła] ([link])*`
- Jeśli bazujesz na kilku źródłach — wymień wszystkie
- **Nigdy** nie wymyślaj źródeł. Jeśli nie masz źródła, nie pisz artykułu

### Tematyka
- AI w biznesie — praktyczne zastosowania, ryzyka, architektura
- Perspektywa właściciela firmy / dyrektora, nie programisty
- Nawiązuj do strategii Pragma (self-hosting, system plików, agenty, niezależność)
- Unikaj: porównań "my vs konkurencja", bezpośredniej reklamy Pragma

### Wersja angielska
- Tłumaczenie umieszcza się w articles.html i index.html (karty)
- Plik .md zawiera TYLKO wersję polską
- Tłumaczenie dodajesz bezpośrednio do HTML przy publikacji

---

## Checklist przed publikacją

- [ ] Tytuł jest konkretny i intrygujący (bez clickbaitu)
- [ ] Lead wyjaśnia "dlaczego to ważne" w 2-3 zdaniach
- [ ] 600-900 słów, 4-6 sekcji
- [ ] Co najmniej 1 źródło z linkiem
- [ ] Nie brzmi jak tekst AI (przeczytaj na głos!)
- [ ] Brak wykrzykników i pustych frazesów
- [ ] Plik nazwany wg wzorca YYYY-MM-DD-tytul.md
- [ ] Dodano kartę na index.html (PL + EN)
- [ ] Dodano pełny artykuł do articles.html (PL + EN)
- [ ] Artykuł przeszedł approval zespołu na Telegram
