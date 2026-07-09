
Test Case ID: TC-006

Title:
Successful user registration with valid data

Preconditions:
- Użytkownik znajduje się na stronie rejestracji.
- Użytkownik posiada unikalny adres e-mail.

Steps:
1. Otwórz formularz rejestracji.
2. Wpisz poprawne imię.
3. Wpisz poprawne nazwisko.
4. Wpisz poprawny adres e-mail.
5. Wpisz poprawne hasło.
6. Kliknij przycisk „Zarejestruj”.

Expected Result:
Użytkownik zostaje poprawnie utworzony i otrzymuje komunikat o pomyślnej rejestracji.


Test Case ID: TC-007

Title:
Registration with password shorter than required

Preconditions:
- Użytkownik znajduje się na stronie rejestracji.

Steps:
1. Otwórz formularz rejestracji.
2. Wpisz poprawne dane użytkownika.
3. Wpisz hasło krótsze niż wymagane (np. Test1).
4. Kliknij przycisk „Zarejestruj”.

Expected Result:
System odrzuca rejestrację i wyświetla komunikat, że hasło musi mieć wymaganą długość.



Test Case ID: TC-008

Title:
Registration with password without special character

Preconditions:
- Użytkownik znajduje się na stronie rejestracji.

Steps:
1. Otwórz formularz rejestracji.
2. Wpisz poprawne dane.
3. Wpisz hasło bez znaku specjalnego (np. Test1234).
4. Kliknij „Zarejestruj”.

Expected Result:
System nie pozwala utworzyć konta i wyświetla informację, że hasło musi zawierać znak specjalny.



Test Case ID: TC-009

Title:
Registration with invalid email format

Preconditions:
- Użytkownik znajduje się na stronie rejestracji.

Steps:
1. Otwórz formularz rejestracji.
2. Wypełnij pozostałe pola poprawnymi danymi.
3. Wpisz email bez znaku „@”.
4. Kliknij „Zarejestruj”.

Expected Result:
System blokuje rejestrację i wyświetla komunikat o niepoprawnym adresie email.



Test Case ID: TC-010

Title:
Registration with already existing email

Preconditions:
- Konto z podanym adresem email już istnieje.

Steps:
1. Otwórz formularz rejestracji.
2. Wpisz dane użytkownika.
3. Podaj email przypisany do istniejącego konta.
4. Kliknij „Zarejestruj”.

Expected Result:
System nie tworzy nowego konta i wyświetla komunikat, że użytkownik o takim emailu już istnieje.
