Wyższa Szkoła Informatyki i Umiejętności Łódź


Projekt Zespołowy - Informatyka semestr 5, studia stacjonarne


Grupa:
- Sebastian Świeczkowski 31590
- Damian Pabich 31588
- Filip Koper 31581
- Wojtek Zaguła 31594


Nazwa Projektu: Sneakers - e-commerce


Link do strony: https://wsinf-sneakers.web.app/


Opis strony: 


Strona wykonana przez naszą grupę to e-commerce, czyli sklep internetowy, który jest podzielony następująco:
1. Strona głowna 
- zawierająca wszystkie produkty.
- możliwość filtrowania produktów.  
- wyszukiwarka konkretnego produktu.


2. Podstrony dla każdego produktu:
- dokładny opis produktu.
- slider ze zdjęciami produktu.
- możliwość dodania produtku do koszyka.
- możliwość dodania produtku do listy życzeń.


3. Strona logowania z przekierowaniem na strone profilu po zalogowaniu.
- formularz logowania z walidacją.
- możliwość rejestracji.


5. Strona profilowa:
- wyświetlanie calej historii zakupów i szczegółów każdego zamówienia.
- możliwość ustawienia zdjęcia profilowego - awatara
- resetowanie hasła, w postaci powiadomienia mailowego z linkiem do strony zawierającej formularz do wprowadzenia nowego hasła.


6. Koszyk:
- wyświetlanie produktów wcześniej dodanych do listy.
- zapiasnie dodanych produktów w pamięci lokalnej urządzenia. 
- możliwość edycji ilości dodanych produktów. 
- podsumowanie i przejście do płatności. 
- po poprawnym wprowadzeniu danych karty kredytowej, zakupione produkty zapisywane sa w bazie danych do konkretnego użytkownika. Później wyświetlane w historii zamówień na stronie profilowej.


7. Lista życzeń:
- możliwość dodania produktu do tzw. listy życzeń ( wishlist ), zapisywane w pamięci lokalnej urządzenia.


Podział obowiązków:


Wojciech Zaguła 31594 - strona wizualna:
- grafiki, zdjęcia - przygotowanie 3 zdjęć, dla każdego produktu, co dla 36 produktów łącznie daje 108 zdjęć + pozostałe grafiki występujące na stronie.            Optymalizacja ( minifikacja ) rozmiarów wszystkich grafik w celu poprawy wydajności. Dodatkowa grafika służąca jako placeholder dla produktów - wyświetlana jest do momentu wczytania przez klienta odpowieniego zdjęcia produktu.
- czcionki - dobór odpowiednich czcionek pod wersje mobilne i desktopowe, zarówno rozmiar jak i odpowiedni krój.
- kolorystyka - przygotowanie kolorów występujących na stronie z motywem przewodnim - kolor pomarańczowy.


Filip Koper 31581 - struktura HTML, CSS
- przygotowanie layoutu strony, wykorzystując semantyczny HTML5.
- CSS w styled-components - layouty stron wykonane w technologiach grid i flex, efekty po najechaniu myszką na dany element ( hover ), animacje ( keyframes ), wszystko wykonane w technologii RWD ( Responsive Web Design ), strona adaptuje się do wielkości ekranu użytkownika.
- animacje wsytępujące na stronie napisane, przy użyciu biblioteki GSAP.


Damian Pabich 31588 - przygotowanie API ( backendu )
- firebase - skonfigurowanie wszystkich ustawień w firebase, przygotowanie struktury bazy danych dla fireStore ( przetrzymywanie informacji o złożonych zamówieniach ), konfiguracja uwierzytelniania poprzez email użytkowników - rejestracja i logowanie przez email, możliwość resetowania hasła. Obsługa błedów i wyświetlanie poprawnych komunikatów dla konkretnego rodzaju błędu. Konfiguracja hostingu i deploy strony na serwer.
- DatoCMS - konfiguracja headless CMS'a - miejsce do przetrzymywania treści wyświetlanych na stronie, możliwość dodawania nowych produktów na strone lub aktualizowania ich, poprzez interfejs graficzny.


Sebastian Świeczkowski 31590 - JavaScript ( React JS ) - funkcjonalność strony
- przygotowanie kodu w języku JavaScript z wykorzystaniem biblioteki React JS. 
- wykorzystanie komponentów funkcjonalnych, co zapewniło większą reużywalność, prostsze testowanie kodu.
- zastosowanie większości nowszych funkcjonalnosci JavaScriptu ( również ES6 ), takich jak - destrukturyzacja obiektów i tablic, domyślne wartości parametrów funkcji, importowanie i eksportowanie domyślne plików, funkcje strzałkowe, spread i rest operator i inne.
- paginacja produktów - wyświetlanie konkretnej liczby produktów na daną stronę.
- routing na stronie wykonany przy użyciu biblioteki React-router-dom w najnowszej wersji v6.	
- Redux Toolkit, połaczone z local storage - koszyk i lista życzeń ( wishlist ) wykonane z wykorzystaniem globalnego stanu aplikacji ( dostęp do danych z koszyka i wishlist na przestrzeni całej aplikacji ), zapisywanie zmian wykonanych przez użytkownika w pamięci lokalnej komputera. 
- Axios i GraphQL - łączenie z API ( axios ), pobieranie odpowiedniej struktury danych ( graphQL )
- struktura aplikacji - podział wszystkich komponentów strony na odpowiednie foldery w zależności od roli.
- Pozostałe biblioteki wykorzystanie w projekcje: Formik ( obsługa formularzy ), Yup ( walidacja formularzy ), React-downshift ( comboboxy ), React-scroll, React-spinners, 
React-firebase-hooks, payment ( walidacja płatności ) i inne.   
