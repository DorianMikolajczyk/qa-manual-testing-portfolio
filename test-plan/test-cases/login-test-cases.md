Test Case ID:
Title:
Preconditions:
Steps:
Expected Result:
Test Case ID: TC-001

Title:
Successful user login with valid credentials

Preconditions:
- Użytkownik posiada aktywne konto.
- Użytkownik znajduje się na stronie logowania.

Steps:
1. Otwórz stronę logowania.
2. Wpisz poprawny adres e-mail.
3. Wpisz poprawne hasło.
4. Kliknij przycisk „Zaloguj”.

Expected Result:
Użytkownik zostaje poprawnie zalogowany i 
zostaje przekierowany do strony głównej lub panelu użytkownika.


Test Case ID: TC-002

Title:
Login with empty email field

Preconditions:
- Użytkownik znajduje się na stronie logowania.

Steps:
1. Otwórz stronę logowania.
2. Pozostaw pole e-mail puste.
3. Wpisz poprawne hasło.
4. Kliknij przycisk „Zaloguj”.

Expected Result:
System nie loguje użytkownika i wyświetla komunikat,
że pole e-mail jest wymagane.


Test Case ID: TC-003

Title:
Login with empty email field

Preconditions:
- Użytkownik znajduje się na stronie logowania.

Steps:
1. Otwórz stronę logowania.
2. Pozostaw pole e-mail puste.
3. Wpisz poprawne hasło.
4. Kliknij przycisk „Zaloguj”.

Expected Result:
System nie loguje użytkownika i wyświetla komunikat,
że pole e-mail jest wymagane.



Test Case ID: TC-004

Title:
Login with empty password field

Preconditions:
- Użytkownik znajduje się na stronie logowania.

Steps:
1. Otwórz stronę logowania.
2. Wpisz poprawny adres e-mail.
3. Pozostaw pole hasła puste.
4. Kliknij przycisk „Zaloguj”.

Expected Result:
System nie loguje użytkownika i wyświetla komunikat,
że pole hasła jest wymagane.



Test Case ID: TC-005

Title:
Login with invalid email format

Preconditions:
- Użytkownik znajduje się na stronie logowania.

Steps:
1. Otwórz stronę logowania.
2. Wpisz adres e-mail bez znaku „@”.
3. Wpisz poprawne hasło.
4. Kliknij przycisk „Zaloguj”.

Expected Result:
System wyświetla komunikat o niepoprawnym formacie adresu e-mail i nie pozwala się zalogować.

