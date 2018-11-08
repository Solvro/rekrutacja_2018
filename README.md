<div align="center">
<img src="./logo_solvro.png" height="200">
</div>

# Rekrutacja 2018

W ramach rekrutacji stworzyliśmy pięć zadań z pięciu różnych kategorii, żeby każdy znalazł coś dla siebie. Wybierz **jedno** zadanie, a rozwiązanie udostępnij w publicznym repozytorium kodu (np. GitHub). Zadania powinny być rozwiązywane indywidualnie. Masz na nie 2 tygodnie (**22.11.2018**). Link do repozutorium należy umieścić w odpowiednim miejscu w [formularzu rekrutacyjnym](https://goo.gl/forms/azpljosFkwykhiEq1).

**Powodzenia!**

## Kategorie:
* [Frontend](#Frontend)
* [Design](#Design)
* [Mobile](#Mobile)
* [Backend](#Backend)
* [DevOps](#DevOps)

<a name="Frontend"></a>

## Frontend
### Panel logowania

W [tym repozytorium](https://github.com/Solvro/demoBackend) znajduje się prosty backend dla logowania i rejestracji. Twoim zadaniem jest stworzenie aplikacji webowej umożliwiającej zalogowanie do systemu oraz wylogowanie się. Punktowana będzie obsługa blędów wynikających z np. złych danych logowania, utraty połączenia z serwerem. 

:hammer_and_wrench: **Preferowane narzędzia**

- Dopuszczone jest używanie frameworków CSS. 
- Technologia dowolna, aczkolwiek preferowane są frameworki takie jak `Angular`, `React`, czy `Vue.js`. 

:heavy_check_mark: **Kryteria oceniania**

- Jakość kodu
- Interfejs i design

<a name="Design"></a>

## Design
### Panda Adapter

Zaprojektuj makietę strony internetowej lub aplikacji mobilnej do adopcji pand. Przygotuj wizualizację **przynajmniej dwóch różnych ekranów**. Makieta powinna przedstawiać funkcje aplikacji (np. wyświetlanie pand czekających na adopcję, przeglądanie profilu pandy, wyszukiwarkę etc.). Prace należy oddawać w formie plików obsługiwanych przez preferowane narzędzia, które znajdują się poniżej.

:hammer_and_wrench: **Preferowane narzędzia**

- aplikacje do tworzenia makiet (np. `AdobeXD`, `Sketch`)
- do grafiki wektorowej (np. `Inkscape`, `Adobe Illustrator`)
- do grafiki rastrowej (np. `Gimp`, `Photoshop`)

:heavy_check_mark: **Kryteria oceniania**

- okocieszność :heart_eyes_cat:
- przyjazność interfejsu użytkownika
- dodatkowe punkty za interaktywność makiety

<a name="Mobile"></a>

## Mobile
### Aplikacja Latarka!

Stwórz aplikację latarki jakiej pragnie ten świat, a na jaką nie zasługuje. Funkcjonalność apki jest jak widać prosta, a za razem błyskotliwa :wink: . Po wciśnięciu przycisku lub wykonaniu innej czynności (może wygrana w kółko i krzyżyk?), Twoja aplikacja powinna uruchomić laterkę. 

:hammer_and_wrench: **Preferowane technologie**

- Totalna dowolność i brak ograniczeń (dużego wyboru i tak nie ma :joy:)
- No dobra, jest jedno ograniczenie, apka powinna być natywna.

:heavy_check_mark: **Kryteria oceniania**

- Funkcjonalność
- Jakość kodu

<a name="Backend"></a>

## Backend
### Solvro checklist

Zaimplementuj prosty serwer obsługujący zapytania zgodnie z zasadami architektury REST. Aplikacja ma umożliwiać tworzenie i edytowanie list zakupów, planów, itp. zgodnie ze [specyfikacją](https://gitlab.com/solvro/rekrutacja-jesien-2018/blob/master/backend_spec.yaml).

:hammer_and_wrench: **Preferowane technologie**

- Najlepiej skorzystać z relacyjnej bazy danych (np. `MariaDB`, `PostgreSQL`) i frameworka do wysokopoziomowego języka (python: `django`, `flask`; js: `express`, `hapi`; java: `spring`)
- PHP, Java, Assembler i wszelkie inne technologie oczywiście dozwolone.

:heavy_check_mark: **Kryteria oceniania**

- 100% zgodność ze specyfikacją (zagadnienia nie opisane zostawione pod własną interpretację)
- Jakość kodu
- Podstawowa odporność na błędne dane, bardzo proste ataki (SQL injection)

<a name="DevOps"></a>

## DevOps
### Konteneryzacja stack'a aplikacji

Dostajesz gotową [aplikację](https://github.com/didinj/mean-stack-angular5-crud), jednak trzeba ją przygotować aby była łatwa w przenoszeniu i deploymencie. Nie pozostaje Ci nic innego jak stoworzyć parę kontenerów!

:hammer_and_wrench: **Preferowane technologie**

- `Docker` - Wykorzystywany w **Solvro** system konteneryzacji
- `docker-compose` - Rozwiązanie pozwalające spiąć ze soba kontenery aby ułatwić proces developmentu i deploymentu
- Preferowane bazowanie na obrazach: `nodejs`, `mongodb`(aby podać właściwy adres serwisu wymagana jest mała modyfikacja w kodzie) opcjonalnie można dodać `nginx`(do serwowania buildu frontend'u).

:heavy_check_mark: **Kryteria oceniania**

- Cała aplikacja ma działać, na kadżym z komputerów jaki jest wykorzystywany przez członków **Solvro**, po wpisaniu komend `docker-compose build` oraz `docker-compose up`
- Po wyłączeniu kontenerów, w szczególności bazy danych, kiedy znowu uruchomimy wszystkie aplikację żadne dane zapisane w bazie nie mogą wyparować.
