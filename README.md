<div align="center">
<img src="./assets/logo_solvro.png" height="200">
</div>

# Rekrutacja

W ramach rekrutacji stworzyliśmy cztery zadania z czterech różnych kategorii, żeby każdy znalazł coś dla siebie. Wybierz **jedno** zadanie, a rozwiązanie udostępnij w publicznym repozytorium kodu (np. GitHub). Zadania powinny być rozwiązywane indywidualnie. Masz na to 2 tygodnie. Link do repozutorium należy wysłać nam mailem lub przez wiadomość prywantną na Facebooku.

**Powodzenia!**

## Kategorie:

  - [Frontend](#Frontend)
  - [Design](#Design)
  - [Mobile](#Mobile)
  - [Backend](#Backend)

<a name="Frontend"></a>

## Frontend

_W [katalogu `./frontend` w tym repozytorium](https://github.com/Solvro/rekrutacja/tree/master/frontend) znajduje się proste API wraz z opisem endpointów dla poniższego zadania._

Korzystając z frameworka `React.js`, `Vue.js` lub `Angular` napisz formularz umożliwiający rezerwację lub zakup biletu do kina. 

Formularz ma udostępniać opcję **wyboru godziny** (lista godzin zwracana jest przez API), **wyboru miejsca lub kilku miejsc na planie kina** (dostępność miejsc dostępna przez API) oraz **wyboru zniżki** (te można sobie wymyślić :wink:). Po wypełnieniu powyższych informacji wraz z **danymi kontatowymi** (imię, nazwisko, email, numer telefonu), użytkownik przenoszony jest do **widoku podsumania**, który pozwala przejrzeć i edytować wszystkie pola. 

Dozwolone jest użycie frameworków CSS jak i bibliotek dostępnych w repozytorium NPM. Ocenie podlega wygląd, jakość kodu (między innymi właściwe dla danego frameworka wykorzystanie formularzy) oraz ogólny feeling aplikacji (responsywność, walidacja pól).

<a name="Design"></a>

## Design

TBA.

<a name="Mobile"></a>

## Mobile

Zaprojektuj i napisz aplikację mobilną zawierającą **listę dostępnych produktów spożywczych** w Twojej lodówce!

Użytkownik aplikacji powinien mieć możliwość dodawania do listy nowych produktów. Każda pozycja powinna zawierać informacje takie jak: **nazwa produktu**, **liczba sztuk / ilość** i, co najważniejsze, **termin przydatności do spożycia**. Może warto się pokusić o dodanie jakiegoś zdjęcia każdego produktu?

Zadbaj o pełną funkcjonalność aplikacji:

- użytkownik powinien mieć możliwość usunięcia produktu z listy oraz aktualizacji liczby/ilości danego produktu,
- produkty powinny być sortowane po terminie przydatności do spożycia,
- lista produktów powinna być pamiętana po zamknięciu aplikacji.

Do przechowywania listy produktów możesz użyć [Firebase'a](https://firebase.google.com/), **SQLite'a** lub innego stosownego rozwiązania.

Aplikację możesz napisać natywnie na systemy **iOS** lub **Android** albo pokusić się o skorzystanie z JSowego frameworka, na przykład **React Native**.

Oceniane będą **jakość kodu** oraz 'feeling' aplikacji (łatwość oraz wygoda użytkowania). Wszelkie własne 'ficzery' mile widziane!

<a name="Backend"></a>

## Backend

Wyobraź sobie, że piszesz backend do **aplikacji imitującej JakDojade**!

W [pliku](./backend/solvro_city.json) JSON dostaniesz zapisaną mapę przystanków w Solvro City. Napisz część serwisu odpowiadającą za rejestrację i logowanie się użytkownika oraz za podawanie informacji o przystankach i najkrótszej trasy pomiędzy dwoma z nich. O sposobie podawania tych informacji powie Ci [specyfikacja](./backend/stops_api.yaml) (część z wyznaczaniem trasy wykonaj bez używania zewnętrznych bibliotek)

Do Twojej dyspozycji dajemy [skrypt](./backend/city_generator.py), który generuje mapę miasta i zapisuję ją do pliku. Możesz go użyć do testowania swojego API dla różnych map.

Na koniec zadbaj o **przejrzyste readme**.

Nice to have:
 - łatwość odpalania Twojego kodu niezależnie od środowiska (serdecznie polecamy Dockera)
 - swagger wygenerowany z kodu na wybranym porcie :-)


Oceniana będzie jakość kodu, jego dokumentacja, rozwiązanie postawionego problemu, użycie odpowiednich technologii, odporność na podstawowe ataki oraz błędne dane (które nie są zawarte w specyfikacji) i praca z systemem kontroli wersji.
