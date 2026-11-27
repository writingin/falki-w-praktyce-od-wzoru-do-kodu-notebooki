# Falki w praktyce. Od wzoru do kodu – notatniki

**Arkadiusz Liber**

Notatniki Jupyter do książki *Falki w praktyce. Od wzoru do kodu* (2026, ISBN 978-83-981200-0-5). Każdemu rozdziałowi odpowiada jeden notatnik, który zawiera:

- wszystkie programy z tekstu rozdziału, w kolejności i z numerami takimi jak w książce,
- ćwiczenia z rozwiązaniami (wraz z funkcjami pomocniczymi, z których rozwiązania korzystają).

Notatniki są zapisane razem z wynikami, więc można je czytać bezpośrednio na stronie repozytorium, bez uruchamiania.

## Rozdziały

| Nr | Notatnik | Google Colab |
|---:|---|---|
| 1 | [Wprowadzenie](rozdzial-01.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-01.ipynb) |
| 2 | [Sygnały i falki jako wektory](rozdzial-02.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-02.ipynb) |
| 3 | [Przestrzenie Hilberta, rzuty i przybliżenia](rozdzial-03.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-03.ipynb) |
| 4 | [Analiza spektralna](rozdzial-04.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-04.ipynb) |
| 5 | [Analiza spektralna z wykorzystaniem rozwinięć falkowych](rozdzial-05.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-05.ipynb) |
| 6 | [Analiza falkowa jako proces filtracji](rozdzial-06.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-06.ipynb) |
| 7 | [Podstawy analizy falkowej](rozdzial-07.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-07.ipynb) |
| 8 | [Wielorozdzielcza analiza falkowa](rozdzial-08.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-08.ipynb) |
| 9 | [Falki](rozdzial-09.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-09.ipynb) |
| 10 | [Aproksymacja i transformaty dwuwymiarowe](rozdzial-10.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-10.ipynb) |
| 11 | [Wybór i łączenie falek w praktyce](rozdzial-11.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-11.ipynb) |
| 12 | [Przygotowanie danych do analizy spektralnej](rozdzial-12.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-12.ipynb) |
| 13 | [Ostrzejszy obraz czas–częstotliwość](rozdzial-13.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-13.ipynb) |
| 14 | [Falki na grafach, na sferze i w dowolnym kierunku](rozdzial-14.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-14.ipynb) |
| 15 | [Falki, sieci neuronowe i modele językowe (LLM)](rozdzial-15.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki/blob/main/rozdzial-15.ipynb) |

## Uruchamianie

**Google Colab.** Wystarczy wybrać przycisk *Open in Colab* przy rozdziale i uruchomić komórki po kolei (*Uruchom wszystko*). Pierwsza komórka doinstalowuje bibliotekę PyWavelets, a potrzebne pliki danych pobiera z tego repozytorium.

**Lokalnie.** Potrzebny jest Python 3 (notatniki sprawdzono w wersji 3.13).

```
git clone https://github.com/writingin/falki-w-praktyce-od-wzoru-do-kodu-notatniki.git
cd falki-w-praktyce-od-wzoru-do-kodu-notatniki
pip install -r requirements.txt
jupyter lab
```

Notatniki należy uruchamiać z katalogu głównego repozytorium, ponieważ dane są wczytywane ze ścieżki względnej `dane/`.

Przykłady korzystają wyłącznie z bibliotek NumPy, SciPy, SymPy, Matplotlib i PyWavelets.

## Dane

| Plik | Rozdziały | Zawartość |
|---|---|---|
| `dane/sdo-20240115.npz` | 10, 11, 14, 15 | Wycinki obrazów Słońca z obserwatorium Solar Dynamics Observatory (instrumenty AIA i HMI) z 15 stycznia 2024 r. Courtesy of NASA/SDO and the AIA, EVE, and HMI science teams. |
| `dane/darwin.txt` | 15 | Fragment dzieła: Charles Darwin, *On the Origin of Species by Means of Natural Selection*, Londyn: John Murray, 1859 (wstęp i rozdziały I–IV; domena publiczna; transkrypcja egzemplarza Smithsonian Libraries, Internet Archive). Tekst sprowadzono do małych liter i 29 znaków: liter a–z, spacji, przecinka i kropki. |

Dane wykorzystano wyłącznie w celach edukacyjnych.

## Licencja

- **Kod** w komórkach kodu notatników: licencja MIT (plik `LICENSE`).
- **Opisy** (komórki tekstowe, treść ćwiczeń, ten plik): wszelkie prawa zastrzeżone.
- Szczegóły, w tym informacje o danych: plik `ZASTRZEZENIA.md`.

## Wersja

1.0.0 – zgodna z pierwszym wydaniem książki (2026).

© 2026 Arkadiusz Liber
