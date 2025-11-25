# Systemy-wbudowane-5

Opis projektu – Systemy Wbudowane 5 (Arduino)
1. Cel projektu

Celem projektu jest zaprojektowanie oraz implementacja układu wbudowanego opartego na platformie Arduino, który realizuje określoną funkcjonalność (np. pomiar parametrów środowiskowych, sterowanie urządzeniem, system alarmowy, robot mobilny itp.). Projekt ma na celu rozwinięcie praktycznych umiejętności programowania mikrokontrolerów, obsługi peryferiów oraz integracji komponentów sprzętowych.

2. Wykorzystane komponenty

W projekcie zastosowano następujące elementy (przykład – możesz podać swoje, a ja заменю):

Mikrokontroler: Arduino Uno / Nano / Mega

Czujniki: np. DHT11/DHT22, HC-SR04, MQ-2, LDR, itp.

Elementy wykonawcze: diody LED, buzzer, silnik DC/serwo, przekaźnik

Moduły komunikacyjne: LCD 16×2, OLED, Bluetooth HC-05, itd.

Zasilanie: USB lub zewnętrzne 5V–12V

3. Opis działania systemu

Układ wykonuje serię zadań w sposób automatyczny:

Odczytuje dane z podłączonych czujników.

Przetwarza dane w mikrokontrolerze (np. filtracja, porównanie z progami).

Na podstawie warunków steruje podłączonymi elementami wykonawczymi.

Wyświetla aktualne dane na ekranie lub przesyła je do komputera / aplikacji.

Reaguje na interakcje użytkownika (przyciski, komunikacja UART).

Przykład działania:
„System mierzy temperaturę i wilgotność, wyświetla je na LCD. Gdy temperatura przekracza wartość graniczną, włącza wentylator oraz wysyła komunikat przez port szeregowy.”

4. Schemat połączeń

Projekt obejmuje połączenie Arduino z czujnikami oraz modułami. Schemat typowo zawiera:

Podłączenie czujników do pinów analogowych/digital

Zasilanie 5V/GND

Wyprowadzenia do wyświetlacza lub modułów komunikacyjnych

Odpowiednie rezystory lub tranzystory sterujące

(Если хочешь, сделаю точный schemat под твой проект.)

5. Oprogramowanie

Program został napisany w języku C/C++ w środowisku Arduino IDE i zawiera:

konfigurację pinów i modułów,

obsługę czujników za pomocą odpowiednich bibliotek,

funkcje sterujące wykonawcami,

logikę główną w pętli loop(),

komunikację szeregową (opcjonalnie).

Kod jest modularny, wykorzystuje funkcje i ewentualnie klasy (if required).

6. Testy i wyniki

W ramach testów sprawdzono poprawność:

odczytów z czujników,

reakcji systemu na przekroczenie progów,

stabilności i powtarzalności działania,

poprawnej pracy elementów wykonawczych.

System działa zgodnie z założeniami projektu.

7. Wnioski

Projekt pozwolił na praktyczne zrozumienie działania systemów wbudowanych, integracji komponentów oraz programowania mikrokontrolerów. Zrealizowane zadanie potwierdza, że platforma Arduino jest efektywnym narzędziem do tworzenia prototypów oraz nauki systemów embedded.
