## Opis projektu

### Cel:

Projekt "Movie Guide App" ma na celu dostarczenie użytkownikom narzędzia do wyszukiwania i sprawdzania informacji na temat filmów, które aktualnie są wyświetlane w kinach. Aplikacja umożliwia użytkownikom przeglądanie recenzji filmów, informacji o aktorach oraz innych szczegółów związanych z filmami.

### Opis funkcji:

- **Wyszukiwanie filmów:** Użytkownicy mogą wyszukiwać filmy według tytułu, gatunku, daty premiery itp.
- **Informacje o filmach:** Dostęp do szczegółowych informacji o filmach, takich jak recenzje, obsada, reżyseria, czas trwania, gatunek.
- **Recenzje:** Wyświetlanie recenzji filmów zarówno od krytyków, jak i od użytkowników.
- **Obsada:** Informacje o aktorach grających w filmie, w tym ich biografie i filmografie.
- **Repertuar kin:** Informacje o aktualnych seansach w pobliskich kinach, w tym godziny seansów i lokalizacje kin.

## Analiza wymagań:

### Wymagania funkcjonalne:

- **Wyszukiwanie filmów:** Użytkownik może wyszukiwać filmy według różnych kryteriów, takich jak tytuł, gatunek, data premiery.
- **Szczegóły filmu:** Wyświetlanie szczegółowych informacji o wybranym filmie, w tym opisu, recenzji, obsady, reżyserii.
- **Recenzje filmów:** Wyświetlanie recenzji z różnych źródeł oraz możliwość dodawania własnych recenzji przez użytkowników.
- **Informacje o aktorach:** Wyświetlanie informacji o aktorach, takich jak ich biografie i wcześniejsze role filmowe.
- **Repertuar kin:** Wyświetlanie aktualnych seansów filmowych w kinach w pobliżu użytkownika.

### Wymagania niefunkcjonalne:

- **Intuicyjny interfejs użytkownika:** Przyjazny i łatwy w obsłudze interfejs.
- **Szybkość wyszukiwania:** Efektywne algorytmy wyszukiwania zapewniające szybkie wyniki.
- **Aktualność danych:** Regularna aktualizacja danych o filmach i repertuarze kin.
- **Skalowalność:** Możliwość obsługi dużej liczby użytkowników jednocześnie.

## Projekt interfejsu:

### Szkice/wizualizacje interfejsu:

- _Strona główna:_ Pasek wyszukiwania, lista polecanych filmów, dostęp do recenzji i repertuaru kin.
- _Okno szczegółów filmu:_ Wyświetlanie pełnych informacji o filmie, recenzji, obsady.
- _Strona aktora:_ Wyświetlanie biografii aktora, jego zdjęć i filmografii.
- _Repertuar kin:_ Lista kin i aktualne seanse filmowe.

### Mapa strony:

- _Strona główna_
  - Pasek wyszukiwania
  - Lista polecanych filmów
  - Repertuar kin
- _Okno szczegółów filmu_
  - Opis filmu
  - Recenzje
  - Obsada
- _Strona aktora_
  - Biografia
  - Filmografia
- _Repertuar kin_
  - Lista kin
  - Godziny seansów

## Architektura systemu:

### Opis struktury danych:

Aplikacja przechowuje dane o filmach, recenzjach, aktorach i repertuarze kin:

- **Filmy:** Informacje o tytule, gatunku, dacie premiery, opisie, reżyserii, obsadzie.
- **Recenzje:** Oceny i opinie krytyków oraz użytkowników.
- **Aktorzy:** Biografie, filmografie, zdjęcia.
- **Repertuar kin:** Informacje o kinach i ich aktualnym repertuarze.

### Diagramy architektury:

Architektura oparta jest na strukturze opakowanej, gdzie:

- **Model:** Odpowiada za logikę wyszukiwania i zarządzanie danymi o filmach, recenzjach, aktorach i repertuarze kin.
- **Widok (View):** Prezentuje interfejs użytkownika.
- **Kontroler (Controller):** Zarządza komunikacją między modelem a widokiem.

## Implementacja:

### Opis technologii:

- **Frontend:** HTML, CSS, JavaScript (React.js).
- **Backend:** Node.js (Express), MongoDB (przechowywanie danych o filmach).
- **API:** Integracja z zewnętrznymi API do pobierania aktualnych danych o filmach i repertuarze kin.

### Struktura kodu:

- _Katalogi/pliki_: Oddzielne pliki dla logiki wyszukiwania, interfejsu, zarządzania danymi.
- _Style pisania kodu_: Zastosowanie modularności, czytelności i komentarzy w kodzie.

## Testowanie:

### Plan testów:

- **Testy jednostkowe:** Sprawdzenie poprawności funkcji wyszukiwania, wyświetlania szczegółów filmu i recenzji.
- **Testy integracyjne:** Upewnienie się, że komponenty współpracują ze sobą poprawnie.
- **Testy interfejsu użytkownika:** Sprawdzenie interakcji z użytkownikiem na różnych urządzeniach.
- **Testy wydajnościowe:** Ocena wydajności wyszukiwania filmów i ładowania danych.

### Procedury testowania:

- Opracowanie zestawu przypadków testowych dla każdej funkcji aplikacji.
- Ustalenie procedur raportowania i naprawiania znalezionych błędów.

## Wdrożenie i konserwacja:

### Plan wdrożenia:

- **Etapy wdrażania:** Testowanie, poprawki, publikacja na platformach dostępnych dla użytkowników.
- **Terminy:** Określenie dat planowanych etapów.

### Procedury konserwacji:

- **Wsparcie techniczne:** Ustanowienie kanałów komunikacji z użytkownikami w celu zgłaszania problemów.
- **Aktualizacje:** Planowanie regularnych aktualizacji w zależności od potrzeb i feedbacku użytkowników.

## Harmonogram:

### Plan projektu:

- **Etapy realizacji:** Podział prac na konkretne zadania (np. implementacja wyszukiwania, interfejsu, testowanie).
- **Terminy:** Określenie czasu potrzebnego na każdy etap.

## Kosztorys:

### Szacunkowe koszty:

- **Rozwój aplikacji:** Wg godzin pracy lub zespołu programistów.
- **Koszty utrzymania:** Serwery, ewentualne opłaty za usługi zewnętrzne, wsparcie techniczne.

---

[English](/README.md)
