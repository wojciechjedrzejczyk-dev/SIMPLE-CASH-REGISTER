# Kasa Fiskalna (Tkinter)
Prosta aplikacja kasy fiskalnej napisana w Pythonie z użyciem biblioteki Tkinter. Umożliwia wybór produktów, ustawianie ilości oraz generowanie paragonu z sumą zamówienia.


## Funkcje aplikacji
* Wybór produktów z listy przycisków
* Ustawianie ilości za pomocą klawiatury numerycznej w aplikacji
* Dodawanie produktów do zamówienia
* Wyświetlanie „paragonu”
* Automatyczne sumowanie wartości zamówienia
* Resetowanie zamówienia


## Wymagania
* Python 3.8+
* Tkinter (standardowo dostępny w większości instalacji Pythona)


## Jak używać
1. Kliknij produkt z listy
2. Wprowadź ilość za pomocą klawiatury aplikacji
3. Kliknij **„Dodaj”**, aby dodać produkt do zamówienia
4. Powtarzaj dla kolejnych produktów
5. Kliknij **„Suma”**, aby zobaczyć całkowitą wartość
6. Kliknij **„Kasuj”**, aby zresetować zamówienie lub cofnąć błędny produkt


## Struktura aplikacji
* `CashRegisterApp` – główna klasa aplikacji
* `products` – słownik dostępnych produktów i ich cen
* `current_order` – lista dodanych pozycji
* `total_price` – suma zamówienia
* `order_display` – pole tekstowe symulujące paragon


## Główne metody
* `select_product()` – wybór produktu
* `set_quantity()` – ustawienie ilości
* `add_selected_product()` – dodanie produktu do zamówienia
* `update_order_display()` – aktualizacja paragonu
* `update_total_display()` – aktualizacja sumy
* `reset_order()` – czyszczenie zamówienia


## Licencja
Projekt edukacyjny – do dowolnego wykorzystania i modyfikacji.
