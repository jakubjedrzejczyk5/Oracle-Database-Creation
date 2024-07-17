# Oracle-Database-Creation
# Projekt Konfiguracji Oracle 21c XE

## Opis Projektu

W tym projekcie zajmujemy się instalacją i konfiguracją Oracle 21c XE na systemie Windows oraz różnymi aspektami administracji bazą danych. Poniżej znajduje się szczegółowy opis kroków, które zostały wykonane w ramach projektu:

### 1. Instalacja systemu Windows
- Przeprowadziliśmy instalację systemu operacyjnego Windows jako podstawowego środowiska do dalszych działań.

### 2. Instalacja Oracle 21c XE
- Zainstalowaliśmy bazę danych Oracle 21c XE na przygotowanym wcześniej systemie Windows.

### 3. Utworzenie plików parametrów
- Utworzyliśmy pliki parametrów pfile.
- Dodaliśmy odpowiednie parametry do plików.
- Przeprowadziliśmy test uruchomienia z nowo utworzonym plikiem pfile.
- Zmieniliśmy parametry NLS oraz opisaliśmy wykorzystane parametry.
- Przeprowadziliśmy test uruchomienia z nowymi parametrami NLS.

### 4. Utworzenie nowych listenerów
- Utworzyliśmy nowe listenery i przetestowaliśmy ich działanie.
- Utworzyliśmy aliasy i przetestowaliśmy ich działanie.

### 5. Utworzenie kontenerów
- Utworzyliśmy pliki manifestu z danymi lokalizacyjnymi (PL, EN, USA).
- Sporządziliśmy listę kontenerów oraz utworzyliśmy katalogi i pliki dla kontenerów.

### 6. Tworzenie przestrzeni tabel
- Utworzyliśmy przestrzenie tabel i odpowiednie pliki w katalogu.

### 7. Tworzenie użytkowników
- Utworzyliśmy użytkowników w bazie danych.

### 8. Tworzenie użytkowników wspólnych
- Utworzyliśmy wspólnych użytkowników i sprawdziliśmy, czy znajdują się oni w bazie użytkowników.

### 9. Przydzielenie listenerów i aliasów kontenerom
- Przydzieliliśmy listenery i aliasy do odpowiednich kontenerów.
- Dokonaliśmy zmian dla aliasów w pliku `tsnames`.

### 10. Tworzenie i testowanie połączeń w SQL Developerze
- Utworzyliśmy i przetestowaliśmy połączenia w SQL Developerze dla każdego użytkownika i kontenera.
- Przetestowaliśmy połączenia dla niepoprawnego portu.
- Nadaliśmy uprawnienia użytkownikom i przetestowaliśmy ich połączenia.
- Ustawiliśmy ścieżkę do `tsnames`, aby SQL Developer mógł korzystać z aliasów, oraz przetestowaliśmy połączenia przy użyciu aliasów.

### 11. Instalacja schematów bazy i import danych
- Wykonaliśmy instalację schematów bazy i import danych dla różnych kontenerów.
- Przenieśliśmy tabele do odpowiednich przestrzeni tabel i przetestowaliśmy dane.
- Nadaliśmy uprawnienia użytkownikom i zweryfikowaliśmy ich dostęp do danych.

### 12. Nadanie uprawnień użytkownikom wspólnym
- Nadaliśmy uprawnienia wspólnym użytkownikom oraz dodaliśmy połączenia w Oracle SQL Developer.
- Przetestowaliśmy uprawnienia dla wspólnych użytkowników na różnych tabelach w bazie danych.

### 13. Odłączenie kontenera i podłączenie go ponownie
- Wyłączyliśmy kontener, odłączyliśmy go, a następnie podłączyliśmy ponownie.

### 14. Symulacja usunięcia danych oraz ich przywrócenie
- Przeprowadziliśmy symulację usunięcia danych oraz ich przywrócenia przy użyciu narzędzia RMAN.

### 15. Zaszyfrowanie przestrzeni tabel
- Utworzyliśmy portfel Oracle, skonfigurowaliśmy klucz i zaszyfrowaliśmy przestrzeń tabel.
- Przetestowaliśmy zabezpieczenia oraz sprawdziliśmy wygląd tabel przed i po szyfrowaniu w edytorze heksadecymalnym.
