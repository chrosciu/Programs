# Tytuł szkolenia

Clean Code, dobre praktyki programowania obiektowego i wzorce projektowe

# Czas trwania szkolenia

3 dni

# Opis szkolenia

Szkolenie przeznaczone jest dla programistów, chcących wyrobić w sobie nawyk pisania czytelnego i zrozumiałego dla innych kodu. 

Skupiamy się nie tylko na czystym kodzie jako takim, ale pokazujemy również, jak dobrze pisać programy przy zastosowaniu paradygmatu programowania obiektowego. 

Następnie w warunkach warsztatowych pokazujemy jak zastosować wybrane wzorce projektowe w realnych przypadkach i kiedy dla danego problemu można zastosować więcej niż jeden wzorzec.

Do uczestnictwa w szkoleniu wymagana jest podstawowa znajomość języka Java i biblioteki JUnit.

# Program szkolenia

1. Dobry kod a zły kod
    - Jak zdefiniować i zmierzyć jakość kodu
    - Kliniczne objawy złego kodu
    - Powody degradacji kodu
    - Obrona przed pogarszaniem się jakości kodu
        - Code review
        - Analiza statyczna (SonarQube)
        - Codzienna refaktoryzacja
2. Podstawowe zasady w codziennej pracy developera
    - Zasada skautów
    - DRY (nie powtarzaj się)
    - Zasada najmniejszego zaskoczenia
    - KISS / YAGNI (rób tyle ile trzeba)
    - Używanie zewnętrznych bibliotek / frameworków
    - Iteracyjne tworzenie kodu
3. Jak tworzyć dobry kod
    - Nazewnictwo zmiennych, metod, klas
    - Formatowanie
    - Tworzenie czytelnych metod
    - Tworzenie zrozumiałych klas
    - Obsługa sytuacji błędnych; wyjątki
    - Komentarze
4. Warsztat - poprawa jakości istniejącego kodu
    - Stworzenie testów
    - Refaktoryzacja krok po kroku
5. Dobre praktyki w programowaniu obiektowym
    - Wysoka spójność
    - Luźne powiązanie
    - Polimorfizm zamiast sprawdzania typu
6. Zasady SOLID
    - Odwrócenie zależności
    - Segregacja interfejsów
    - Pojedyncza odpowiedzialność
    - Zamknięcie na modyfikację przy otwarciu na rozszerzanie
    - Zasada podstawienia Liskov
        - Zaskakujące efekty przy dziedziczeniu
        - Zastąpienie dziedziczenia kompozycją
7. Ogólnie o wzorcach projektowych
    - Czym jest wzorzec projektowy
    - Zalety stosowania wzorców
    - Klasyfikacja wzorców:
        - kreacyjne
        - strukturalne
        - behawioralne
8. Dostosowywanie istniejących rozwiązań
    - adapter
        - radzenie sobie z niekompatybilnym interfejsem
    - fasada
        - uproszczenie i redukcja interfejsu
        - redukcja tzw. białego szumu przy integracji
9. Drzewiaste struktury danych
    - kompozyt
        - proste zebranie wyniku operacji na całym drzewie
    - odwiedzający (visitor)
        - zebranie wyniku operacji na całym drzewie
        - nie wymaga modyfikacji kodu elementów drzewa
10. Tworzenie obiektów w ramach hierarchii
     - prototyp
         - kopiowanie elementów bez konieczności znania ich konkretnego typu
     - fabryka
         - ekstrakcja logiki tworzenia obiektu do oddzielnego bytu
11. Ortogonalne hierarchie obiektów
     - most
         - redukcja ilości klas niezbędnej do zamodelowania hierarchii (suma zamiast iloczynu)
     - budowniczy
         - zapobieganie możliwości tworzenia niekompletnych obiektów
         - wygodne i elastyczne API
     - fabryka abstrakcyjna
         - ekstrakcja logiki tworzenia grup obiektów do oddzielnego bytu
12. Wielostronna komunikacja
     - mediator
         - redukcja (z kombinatorycznej do liniowej) ilości możliwych interakcji pomiędzy obiektami
     - obserwujący
         - całkowite przecięcie bezpośrednich powiązań między obiektami przy w pełni zachowanej komunikacji
         - możliwość podejścia reaktywnego (akcje wykonują się tylko wtedy gdy są niezbędne - brak pustych przebiegów)
13. Zarządzanie scenariuszami działań
     - strategia
         - potraktowanie algorytmu jak czarnej skrzynki i możliwość jego podmiany w zależności od zapotrzebowania
     - metoda szablonowa
         - redukcja ilości kodu w przypadku kilku algorytmów z dużym udziałem części wspólnej
     - stan
         - prostsze modelowanie systemu zachowującego się znacząco różnie w zależności od warunków wewnętrznych
14. Upraszczanie algorytmów - dziel i zwyciężaj
     - polecenie
         - zamknięcie kilku działań w jednym obiekcie
         - możliwość kolejkowania, planowania i cofania zadań
     - łańcuch zobowiązań
         - specjalizacja obsługi konkretnych żądań w konkretnym miejscu
         - elastyczność - obsługujący nie muszą nic o sobie wiedzieć
     - interpreter
         - łatwość ewaluacji skomplikowanych wyrażeń
15. Utrwalanie danych
     - memento
         - bezpieczne zapisywanie i odtwarzanie stanu obiektu z zachowaniem integralności
     - pyłek (flyweight)
         - optymalizacja pamięciowa przy przechowywaniu dużej ilości małych obiektów


**Program szkolenia jest programem ramowym i może zostać zmodyfikowany na życzenie klienta**