# challenge_portfolio_Gosia
# Task 1
## Subtask 1
10 pkt :D
## Subtask 3
Biorę udział w projekcie z dwóch powodów:
* jestem w trakcie przekwalifikowania się na scrum mastera i chciałabym lepiej rozumieć, o czym mówi zespół ;)
* z ciekawości - bardzo lubię uczyć się nowych rzeczy, a kto wie, czy kolejny fach w zanadrzu kiedyś się nie przyda.
## Subtask 4
* Aplikacja służy scoutom futbolowym do prowadzenia i zarządzania bazą danych obiecujących zawodników wraz z ich meczami (i raportami z nich).
* Jej główną funkcjonalnością są **Gracze**. Po wejściu w to pole byłam w stanie przeglądać wpisy, przejść ze strony na stronę. Kliknięcie w wiersz gracza prowadzi na stronę, gdzie można edytować jego dane osobowe. Według mnie przejście do edycji tych danych powinno wymagać jeszcze jednego kliknięcia. **Mecze** i **Raporty** zadownika można rozwinąć z menu po lewej stronie - nie było to dla mnie zbyt intuicyjne położenie. Zmiana języka działa bez zarzutu. Wg mnie przydałaby się opcja powrotu do menu głównego.
* **Interfejs aplikacji w wersji desktopowej** - dość ubogi, widać że to dopiero szkic strony. Bardzo nieestytyczna wg mnie jest czcionka Menu głównego. **Interfejs wersji mobilnej** wygląda stosunkowo dobrze (tzn. dobrze dopasowuje się do wielkości ekranu).
* **Intuicyjność**: poza opisanymi powyżej mało intuicyjnymi elementami (dodawanie nowego gracza, wyświetlenie raportów zawodnika) nie mam większych zastrzeżeń.
* **Błędy**:
  * funkcjonalność nie działająca jak powinna: byłam w stanie dodać gracza z przyszłą datą urodzenia (2026 r.)
  * Przy przechodzeniu ze Strony głównej do Graczy i klikaniu zmiany języka wyświetla się następujące ostrzeżenie: 
```
e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1 Params `start` and `limit` are deprecated. Use `_start` and `_limit`
```
Po kliknięciu w ostatnio dodanego gracza z poziomu strony głównej, pojawiły się poniższe błędy:
```
e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1          POST https://api.scouts-test.futbolkolektyw.pl/auth/local 400
```
```
login-0b8cae71f37d51d9054e.js:1 Identifier or password invalid.
```
```
e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1          POST https://api.scouts-test.futbolkolektyw.pl/auth/local 400
```
```
login-0b8cae71f37d51d9054e.js:1 Identifier or password invalid.
```
```
e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1          POST https://api.scouts-test.futbolkolektyw.pl/auth/local 400
```
```
login-0b8cae71f37d51d9054e.js:1 Identifier or password invalid.
```
```
e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1          POST https://api.scouts-test.futbolkolektyw.pl/auth/local 400
```
```
e37646be6bec636a7b98d9f81a3aeebfba345560.b0333572accba70fd07f.js:1          POST https://api.scouts-test.futbolkolektyw.pl/auth/local 400
```
Miało to jednak miejsce tylko raz (później po analogicznym kliknięciu nie było już błędów), stąd zastanawiam się, czy to nie był problem z moim internetem :)
