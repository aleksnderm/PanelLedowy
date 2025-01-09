# LED Panel Controller

## Opis projektu
LED Panel Controller to aplikacja napisana w C++ służąca do sterowania panelem LED za pomocą enkodera obrotowego. Projekt został stworzony z myślą o symulacji różnych efektów świetlnych, takich jak radiowóz policyjny, ogień, fajerwerki, telewizor, błyski paparazzi czy tryb disco. Interfejs użytkownika został zaimplementowany na wyświetlaczu OLED SSD1306.

## Funkcje projektu
- **Tryby świecenia**:
  - **Temperatura barwowa**: Ustawienie ciepła barwowego (2900K-5600K).
  - **Kolor (Hue)**: Ustawienie koloru w przestrzeni barw HSV.
  - **Moc (Power)**: Regulacja jasności diod.
  - **Efekty (Effects)**: Możliwość wyboru spośród różnych animacji świetlnych.
- **Efekty świetlne**:
  - Radiowóz policyjny (Police Car).
  - Symulacja światła telewizora (TV).
  - Błyski paparazzi (Paparazzi).
  - Symulacja ognia (Fire).
  - Tryb disco (Disco).
  - Symulacja fajerwerków (Firework).
- **Interfejs użytkownika**:
  - Wyświetlanie aktualnego trybu i jego wartości na wyświetlaczu OLED.
  - Obsługa enkodera obrotowego do zmiany wartości i trybów.

## Technologie
- **C++**: Język użyty do implementacji projektu.
- **Adafruit NeoPixel**: Biblioteka do sterowania paskiem LED.
- **Adafruit SSD1306**: Biblioteka do obsługi wyświetlacza OLED.
- **Arduino**: Platforma mikrokontrolerowa używana do uruchomienia projektu.

## Struktura projektu
LED-Panel-Controller/
  ├── src/
    ├── Mode.h 
    ├── Mode.cpp
    ├── Effect.h
    ├── Effect.cpp
    ├── EffectMode.h
    ├── EffectMode.cpp
  ├── Panel_ledowy.ino
  ├── README.md
## Wymagania sprzętowe
- Mikrokontroler kompatybilny z Arduino (np. Arduino Uno, Mega).
- Pasek LED zgodny z Adafruit NeoPixel (WS2812B lub podobny).
- Wyświetlacz OLED SSD1306.
- Enkoder obrotowy z przyciskiem.

## Instalacja
1. Pobierz repozytorium projektu:
   ```bash
   git clone https://github.com/TwojeKonto/LED-Panel-Controller.git
   cd LED-Panel-Controller
