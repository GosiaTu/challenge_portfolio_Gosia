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
# Task 2
## Subtask 1
<https://docs.google.com/spreadsheets/d/1lLVgGJZ2UG5K5dSujl92mGO9lUM15L3XBI6Uca3WW3I/edit?usp=sharing>
## Subtask 2
<https://docs.google.com/spreadsheets/d/1nxDRmZZfMhtwFvmUgaS5EoVJi_bini25yfLH_0N6WgU/edit?usp=sharing>
## Subtask 3
<img src="https://media.giphy.com/media/oOVlFfxJMdui2nQP6b/giphy.gif">
... a bardziej serio :upside_down_face: : przypadki testowe mogą się przydać Tobie samemu/-mej, gdy po jakimś czasie wracasz z potrzebą dotestowania czegoś - zapewne nie będziesz w stanie bez tego odtworzyć dokładnie, co wtedy robiłeś/-ąś, w jakiej kolejności itd. Mogą też się przydać innym testerom, np. dochodzącym do projektu już w jego trakcie.

# Task 3

<https://drive.google.com/drive/folders/1OTsTA4tMrAj_kbtRQJt_6O_HaYSDoMre?usp=sharing>

# Task 3

## Subtask 3
1. Aplikacja służy do praktykowania medytacji, ćwiczenia oddechu i redukcji stresu za pomocą muzyki relaksacyjnej.
2. Użytkownikiem prawdopodobnie może być każda osoba zainteresowana tematyką rozwoju osobistego i mindfulness.
3. Według mnie aplikacja zasadniczo jest user friendly.
* Zmodyfikowałabym układ menu głównego - ustawianie celu ('Choose your goal') mogłoby być na innym poziomie, np. wyżej. W tej chwili wygląda jak kurs kolejnego, wyższego poziomu.
4. Po dość pobieżnych testach eksploracyjnych (w tym tygodniu niestety miałam na to zadanie mało czasu) najważniejsze funkcjonalności wydają się działać. 
* Wybrałam kurs wprowadzający ('Introductory course'), który potem dodał się do menu głównego ('Home').
* Działają: muzyka i ćwiczenia oddechowe.

Raport:
<https://drive.google.com/drive/folders/1vv6UWxjJ9H4j5GO47hYfzR5GwZK62egK?usp=sharing>

5. Testowanie aplikacji natywnej było dla mnie bardziej intyicyjne, gdyż posługiwałam się interfejsem do którego byłam przyzwyczajona (DevTools jako narzędzie ma jeszcze przede mną dużo sekretów) - wydaje mi się, że my wszyscy jesteśmy w pewnym stopniu na co dzień testerami aplikacji natywnych używając aplikacji w telefonie.
