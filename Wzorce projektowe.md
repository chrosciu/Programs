# Tytuł szkolenia

Wzorce projektowe

# Czas trwania szkolenia

2 dni

# Opis szkolenia

Szkolenie przeznaczone jest dla programistów, chcących zapoznać się z wzorcami projektowymi. 

Nie skupiamy się na suchym przejściu przez wzorce - zamiast tego w warunkach warsztatowych pokazujemy jak zastosować je w realnych przypadkach. 

Dodatkowym atutem szkolenia jest ukazanie jak wybrane problemy można rozwiązać za pomocą więcej niż jednego wzorca.

Do uczestnictwa w szkoleniu wymagana jest podstawowa znajomość języka Java i biblioteki JUnit.

# Program szkolenia

1. Ogólnie o wzorcach projektowych
    - Czym jest wzorzec projektowy
    - Zalety stosowania wzorców
    - Klasyfikacja wzorców:
        - kreacyjne
        - strukturalne
        - behawioralne
2. Dostosowywanie istniejących rozwiązań
   - adapter 
       - radzenie sobie z niekompatybilnym interfejsem
   - fasada
       - uproszczenie i redukcja interfejsu
       - redukcja tzw. białego szumu przy integracji
3. Drzewiaste struktury danych
   - kompozyt
        - proste zebranie wyniku operacji na całym drzewie 
   - odwiedzający (visitor)
        - zebranie wyniku operacji na całym drzewie 
        - nie wymaga modyfikacji kodu elementów drzewa
4. Tworzenie obiektów w ramach hierarchii
   - prototyp
        - kopiowanie elementów bez konieczności znania ich konkretnego typu
   - fabryka
        - ekstrakcja logiki tworzenia obiektu do oddzielnego bytu      
5. Ortogonalne hierarchie obiektów
   - most
        - redukcja ilości klas niezbędnej do zamodelowania hierarchii (suma zamiast iloczynu)   
   - budowniczy
        - zapobieganie możliwości tworzenia niekompletnych obiektów
        - wygodne i elastyczne API
   - fabryka abstrakcyjna
        - ekstrakcja logiki tworzenia grup obiektów do oddzielnego bytu 
6. Wielostronna komunikacja
   - mediator
        - redukcja (z kombinatorycznej do liniowej) ilości możliwych interakcji pomiędzy obiektami 
   - obserwujący
        - całkowite przecięcie bezpośrednich powiązań między obiektami przy w pełni zachowanej komunikacji
        - możliwość podejścia reaktywnego (akcje wykonują się tylko wtedy gdy są niezbędne - brak pustych przebiegów)
7. Zarządzanie scenariuszami działań
   - strategia
        - potraktowanie algorytmu jak czarnej skrzynki i możliwość jego podmiany w zależności od zapotrzebowania 
   - metoda szablonowa
        - redukcja ilości kodu w przypadku kilku algorytmów z dużym udziałem części wspólnej 
   - stan 
        - prostsze modelowanie systemu zachowującego się znacząco różnie w zależności od warunków wewnętrznych 
8. Upraszczanie algorytmów - dziel i zwyciężaj
   - polecenie
       - zamknięcie kilku działań w jednym obiekcie
       - możliwość kolejkowania, planowania i cofania zadań
   - łańcuch zobowiązań
       - specjalizacja obsługi konkretnych żądań w konkretnym miejscu
       - elastyczność - obsługujący nie muszą nic o sobie wiedzieć 
   - interpreter
       - łatwość ewaluacji skomplikowanych wyrażeń  
9. Utrwalanie danych
   - memento
       - bezpieczne zapisywanie i odtwarzanie stanu obiektu z zachowaniem integralności 
   - pyłek (flyweight)
       - optymalizacja pamięciowa przy przechowywaniu dużej ilości małych obiektów 

**Program szkolenia jest programem ramowym i może zostać zmodyfikowany na życzenie klienta**