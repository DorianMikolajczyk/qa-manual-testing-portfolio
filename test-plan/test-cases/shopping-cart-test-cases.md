
Test Case ID: TC-011

Title:
Add product to shopping cart

Preconditions:
- Użytkownik znajduje się na stronie sklepu.
- Lista produktów jest dostępna.

Steps:
1. Otwórz stronę sklepu.
2. Wybierz dowolny produkt.
3. Kliknij przycisk „Dodaj do koszyka”.
4. Przejdź do koszyka.

Expected Result:
Wybrany produkt zostaje dodany do koszyka i jest widoczny na liście produktów.



Test Case ID: TC-012

Title:
Remove product from shopping cart

Preconditions:
- Użytkownik ma produkt dodany do koszyka.

Steps:
1. Otwórz koszyk.
2. Kliknij przycisk „Usuń” przy produkcie.
3. Odśwież stronę koszyka.

Expected Result:
Produkt zostaje usunięty i nie jest widoczny w koszyku.



Test Case ID: TC-013

Title:
Change product quantity in shopping cart

Preconditions:
- Użytkownik ma produkt w koszyku.

Steps:
1. Otwórz koszyk.
2. Zmień ilość produktu z 1 na 2.
3. Zapisz zmianę lub odśwież koszyk.

Expected Result:
Ilość produktu zostaje zmieniona, a cena całkowita aktualizuje się poprawnie.



Test Case ID: TC-014

Title:
Verify empty shopping cart

Preconditions:
- Użytkownik nie posiada produktów w koszyku.

Steps:
1. Otwórz stronę koszyka.

Expected Result:
System wyświetla informację, że koszyk jest pusty.


Test Case ID: TC-015

Title:
Proceed from cart to checkout

Preconditions:
- Użytkownik posiada produkt w koszyku.

Steps:
1. Otwórz koszyk.
2. Kliknij przycisk „Przejdź do zamówienia”.
3. Poczekaj na załadowanie strony.

Expected Result:
Użytkownik zostaje przekierowany do formularza składania zamówienia.
