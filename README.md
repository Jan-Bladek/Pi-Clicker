# 🥧 Pi Clicker v2.0

**Pi Clicker** to wciągająca gra typu idle/clicker na system Android, w której Twoim celem jest wydobycie jak największej liczby cyfr liczby π (Pi). Klikaj, kupuj matematyczne ulepszenia i używaj potężnych boostów, aby osiągnąć cel!

---

## 🎮 O grze

W Pi Clicker v2.0 wcielasz się w matematycznego górnika. Twoim zadaniem jest zebranie **3 141 592** punktów π (pierwsze 7 cyfr liczby Pi).

### Główne funkcje:
- **Intuicyjne klikanie**: Klikaj w wielki symbol π, aby generować punkty.
- **10 Matematycznych Ulepszeń**: Od prostego dodawania po zaawansowane silnie i logarytmy. Każde ulepszenie zwiększa Twoje CPS (Clicks Per Second) lub siłę kliknięcia.
- **System Edukacyjny**: Każdy operator posiada przycisk "i", który wyjaśnia matematyczne podstawy jego działania.
- **Dynamiczne Boosty**: Aktywuj Boost ×10, aby drastycznie przyspieszyć postęp (dostępny co 2 minuty).
- **Dwa systemy punktów**:
    - `piClicks`: Twoja aktualna waluta na zakupy.
    - `totalPointsEarned`: Całkowity postęp liczony do głównego celu gry.
- **Płynne animacje**: Szybkie, latające cyfry π i efekty wizualne przy każdym kliknięciu.

---

## 📥 Jak pobrać i zainstalować na Android

Ponieważ gra jest w fazie deweloperskiej, najprostszym sposobem na jej uruchomienie jest użycie środowiska **Android Studio**.

### Wymagania:
- Komputer z systemem Windows/macOS/Linux.
- Zainstalowane [Android Studio](https://developer.android.com/studio).
- Urządzenie z Androidem (wersja 12+) lub skonfigurowany emulator.

### KROK 1: Pobranie kodu
Możesz pobrać projekt bezpośrednio z GitHuba:
```bash
git clone https://github.com/twoj-uzytkownik/Pi_Game.git
```
*(Lub pobierz jako plik .ZIP i rozpakuj na dysku).*

### KROK 2: Otwarcie w Android Studio
1. Uruchom **Android Studio**.
2. Wybierz **File -> Open**.
3. Wskaż folder z projektem `Pi_Game`.
4. Poczekaj, aż Gradle pobierze niezbędne biblioteki (może to potrwać kilka minut).

### KROK 3: Instalacja na telefonie/emulatorze
1. Podłącz telefon kablem USB (upewnij się, że masz włączone "Opcje programistyczne" i "Debugowanie USB").
2. W Android Studio, na górnym pasku, wybierz swoje urządzenie.
3. Kliknij zielony przycisk **Run** (trójkąt) lub naciśnij `Shift + F10`.
4. Gra zostanie skompilowana, przesłana na telefon i automatycznie uruchomiona!

---

## 🛠 Technologie
- **Język**: Kotlin
- **UI**: XML / ViewBinding
- **Zarządzanie stanem**: Custom GameStateManager (Singleton)
- **Asynchroniczność**: Kotlin Coroutines (dla systemu CPS)
- **Persystencja**: SharedPreferences (automatyczny zapis gry)
