# resport-searchengine-test-plan
Example of the test plan

Test Plan wyszukiwarki resport.eu

1. Wstęp
Głównym celem działań testowych jest dostarczenie klientom informacji o jakości testowanego produktu.
W przygotowanym dokumencie zostały zebrane kluczowe informacje na temat działań testowych. Zostały wyszczególnione wszystkie komponenty oprogramowania, które zostana poddane weryfikacji, typt testów jakie zostaną przeprowadzone.

2. Zakres testów
- Realizowane typy testów:
 - funkcjonalne
 - wydajnościowe

- Typy testów, które nie będą przeprowadzone:
 - testy automatyczne - brak wystarczającego budżetu
 
3. Przedmioty testów
Komponentem poddawanym testom jest wyszukiwarka ze strony głównej resport.eu, z uwzglednieniem całej logiki filtrowania po odpowiednich polach.

4. Kryteria zaliczenia/niezaliczenia testów
 - wykonanie zaprojektowanych przypadków testowych
 - czas odpowiedzi serwera nie przekracza 700ms
 
5. Kryteria wejścia/wyjścia
- 5.1. Kryteria wejścia:
 - zakończona faza implementacji wyszukiwarki
 - działające i skonfigurowane środowisko testowe
 - dostęp do działąjące i skonfigujowanej maszyny wirtualnej
- 5.2. Kryteria wyjścia:
 - wszystkie przypadki zostały pomyślnie zakończone
 - komponent spełnia wszystkie ustalone założenia z załączonej dokumentacji
 
6. Lista wymagań funkcjonalności do przetestowania
Załączenie wszystkich dokumnetacji, user story, scenariuszy itp.

7. Środowisko testowe:
 - testowy serwer (Development)
 - system Windows 10 Pro 64 bit
 - przeglądarki biorące udział w testach: Firefox, Chrome, Edge, Opera, Safari
 
8. Harmonogram testów
- 8.1. Przeprowadzenie testów funkcjonalnych:
 - weryfikacja funkcjonalności oparta o user story - 5h
 - wykonanie zaprojektowanych wcześniej przypadków testowych - 2h
 - weryfikacja warstwy backendowej - 2h
- 8.2. Przeprowadzenie testów wydajnościowych:
 - weryfikacja ile wynosi średni czas odpowiedzi
 - weryfikacja jaka jest maksymalna ilość requestów, przy jakiej wyszukiwarka działa stabilnie.
 
9. Raport z testów:
 - lista zrealizowanych przypadków testowych wraz ze statusami
 - pomiary z testów wydajnościowych
 - inne raporty z testów
 
10. Lista narzędzi:
 - Jmeter
 - TestLink
 - Jira
 - BrowserStack
 
11. Zarządzanie incydentami, błędami
W procesie testowym każdy wykryty błąd powinien byc odpowiednio zaraportowany do sytemu Jira.
Uwzględniając przy tym priorytet błędu, osobę przypisaną (developer), komponent, któego dotyczy problem.
Zgodnie z przyjętym flow, taki problem powinien zostać naprawiony przez dewelopera i trafic do retestów.

12. Role i odpowiedzialność
- Marzena Chaczko, R.S. - przygotowanie przypadków testowych
- Marzena Chaczko - wykonywanie przypadków testowych
- R.S. - weryfikacja user story









