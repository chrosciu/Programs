# Tytuł szkolenia

Programowanie reaktywne w Javie z wykorzystaniem frameworka Spring

# Czas trwania szkolenia

3 dni

# Opis szkolenia

Szkolenie przeznaczone jest głównie dla dwóch kategorii uczestników:

- osób mających doświadczenie w programowaniu w Javie oraz Springu a chcących się nauczyć się w sposób praktyczny programowania reaktywnego z użyciem ww. narzędzi
- osób, które mają już praktyczne doświadczenie w programowaniu reaktywnym, ale odczuwają potrzebę lepszego zapoznania się z teorią (lub jej ugruntowania)

W pierwszych dwóch dniach szkolenia przeważają zadania praktyczne (60%), niemniej jednak na samym początku duży nacisk jest kładziony na teorię; z doświadczenia wiem, że to procentuje w dalszej części zajęć. Trzeci dzień jest dniem w całości warsztatowym - wykorzystujemy tu wiedzę zdobytą w trakcie poprzednich dni szkolenia.

# Program szkolenia

1. Wstęp do programowania reaktywnego
    - Definicja tego czym jest programowanie reaktywne
    - Powody wprowadzenia podejścia reaktywnego
        - marnowanie zasobów
        - problemy ze skalowalnością
    - Demo - porównanie działania aplikacji napisanej w sposób zwykły i reaktywny
    - Kiedy **nie** stosować podejścia reaktywnego
2. Reactive Streams jako specyfikacja programowania reaktywnego
    - Składowe specyfikacji (kod, testy, specyfikacja tekstowa)
    - Interfejsy
        - `Publisher` - nadawca elementów
        - `Subscriber` - odbiorca elementów
        - `Subscription` - połączenie między nadawcą i odbiorcą
    - Przebieg subskrypcji (rozpoczęcie, żądanie elementów, zakończenie)
    - Backpressure i nieograniczona subskrypcja
    - Przegląd zaawansowanych reguł dotyczących subskrypcji
3. Podstawy frameworka Reactor
    - Ogólne cechy frameworka
    - `Mono` i `Flux` jako podstawowe klasy
    - Marble diagrams
    - `Flux` - strumień wielu elementów
        - Tworzenie z gotowych elementów
        - Tworzenie programowe
    - `Mono` - strumień jednoelementowy
    - Subskrypcja do strumieni
        - Poprzez callbacki
        - Poprzez `BaseSubscriber`
    - Anulowanie subskrypcji
4. Operatory
    - Ogólne działanie operatora
        - wpięcie w łańcuch subskrypcji
        - upstream, downstream
    - Mapowanie
        - synchroniczne (`map()`)
        - asynchroniczne (`flatMap()`, `concatMap()`)
    - Filtrowanie (`filter()`, `take()`, `skip()`)
    - Redukowanie (`reduce()`)
    - Łączenie strumieni
        - tych samych typów (`merge()`, `concat()`)
        - różnych typów (`zip()`)
    - Zależności czasowe
        - opóźnianie elementów (`delayElements()`)
        - uruchamianie strumienia po zakończeniu poprzedniego (`then()`)
    - Tworzenie własnych operatorów (`transform()`)
    - Jak wybrać potrzebny operator - porady praktyczne
5. Obsługa błędów
    - Sygnał błędu zamiast rzucania wyjątku
    - Błąd podczas subskrypcji
    - Zastąpienie sygnału błędu
        - Za pomocą elementu
        - Za pomocą sekwencji
    - Przemapowanie błędu
    - Dodatkowa akcja przy wystąpieniu błędu
    - Resubskrypcja do strumienia
6. Testowanie
    - Przedstawienie testowych klas pomocniczych oferowanych przez Reactor
    - `StepVerifier` - weryfikacja emisji danych przez strumień
        - Tworzenie
        - Nakładanie asercji
        - Uruchamianie testu
        - Użycie wirtualnego czasu
    - `TestPublisher` - możliwość manipulacji emisją danych do strumienia
        - Tworzenie
        - Emitowanie danych
7. Debugowanie
    - Analiza callstacka rzucanego przez Reactor
    - Włączanie trybu debugowania
        - Jako globalny hook
        - Jako Java Agent
    - Checkpointy
    - Logowanie zachowania strumienia za pomocą operatora `log()`
8. Reactor a wielowątkowość
    - `Scheduler` jako abstrakcja wyboru wątku
    - Predefiniowane i customowe schedulery
    - Zmiana wątku emisji elementów - operator `publishOn()`
    - Zmiana wątku tworzenia elementów - operator `subscribeOn()`
    - Równoległe przetwarzanie danych w strumieniu
9. Typowe pułapki programowania reaktywnego
    - Brak subskrypcji
    - Operacje wykonane przed subskrypcją
    - Blokujące operacje w operatorach
    - Nadmiar operatorów
    - Ręczne tworzenie strumieni
10. Framework Spring - podejście reaktywne
    - Ogólny opis stosu reaktywnego w Springu
    - Reaktywny serwer HTTP - WebFlux
        - Podejście adnotacyjne
        - Podejście funkcyjne
        - Technika SSE (Server-Sent-Events)
        - WebSockets
    - Reaktywny klient HTTP - WebClient
        - Tworzenie i użycie
        - Łączenie kilku operacji
11. Warsztat - implementacja gry MasterMind w podejściu reaktywnym z wykorzystaniem Springa
    - Przedstawienie wymagań, ogólnego zarysu architektury i dostarczonych narzędzi
    - Implementacja części serwerowej
    - Implementacja części klienckiej

**Program szkolenia jest programem ramowym i może zostać zmodyfikowany na życzenie klienta**