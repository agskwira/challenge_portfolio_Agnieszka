# Become a Manual Tester
## Task 1 Exploratory testing

### Subtask 1 Test result
<details> 
 <summary> ❓Test result ❓	</summary>
           9/10 	:sweat_smile:
</details>

### Subtask 3 Dlaczego zdecydowałam się na udział w challenge portfolio?

Na zmianę ścieżki zawodowej zdecydowałam się około rok temu. Zaczełam czytać o zawodzie testera. Uczestniczyłam w kilku kursach online z manualnego testowania oprogramowania. Po mieściącu " zabawy" w testera zdecydowałam, że to zawód dla mnie, że chcę to robić. Zdałam egzamin ISTQB. Wtedy usłyszałam od kolzeżanki o Dare IT. 
Wzięłam udział w targach pracy zorganizowanych przez dziewczyny. Armosfera była świetna, wiele dowiedziałam się o możliwościach nauki i szukania pracy jako tester, byłam zachwycona prezentacjami partnerów. Wtedy zdecydowałam, że chcę się uczyć dalej z Dare IT 😃

### Subtask 4 :soccer: Scouts panel- exploratory testing:soccer:
<details>
<summary> Do czego służy aplikacja "Scouts Panel" :bouncing_ball_person: </summary>
"Scout panel" to aplikacja służąca dla zawodników piłki nożnej, która umożliwia przeglądanie wskaźników, umiejętności i pozycje zawodników.
</details>
<details>
<summary>Funkcjonalności aplikacji "Scouts Panel" 	:computer:</summary>
 
 * Logowanie do aplikacji
 
 * Zmiana języka wyświetlania strony
 
 - Dodawanie nowego gracza wypełniając formularz
    W mojej opini opcja mało intuicyjna, przycisk "DODAJ GRACZA" znajduje się w panelu "Linki pomocnicze". W mojej opini dużo lepszym rozwiązanie byłoby dodanie tego          przycisku w panelu bocznym z prawej strony
 
 - Dla kazdego zawodnika można dodać mecz w którym wziął/będzie brał udział za pomocą przycisku "Mecze">>> DODAJ MECZ
     W mojej opinii mało intuicyjna opcja widoczna dopiero o dodaniu zawodnika
 
 - Dla każdego zawodnika istnieje możliwośc stworzenia raportu za pomocą  przycisku "Raporty">>> DODAJ RAPORT
     W mojej opinii mało intuicyjna opcja widoczna dopiero o dodaniu zawodnika, chociaż istnieje przycisk "dodaj raport" nie można go dodać po wciśnięcu zmienia się na        przycisk "Dodaj mecz"
 
 - Można wyświetlić listę graczy za pomocą przycisku "Gracze"
     Opcja intuicyjna , widoczna w panelu bocznym 
 
 - istnieje możliwośc zmiany jezyka wyświetlania, dostępne języki : polski, angielski
     Opcja intuicyjna , możliwośc przełączania języków za pomocą przycisku przełączania 
 - Na liście mecze są możliwe do wykonania akcje t.j. edycja karty meczu, stworzenie raportu, rzpoczęcie meczu - opcje intuicyjne 
 </details>
 <details>
<summary> Znaezione błędy aplikacji :lady_beetle:</summary>
 
  - Mozlliwość dodania zawodnika, którego imie i nawisko zawodnika, zawierają liczby i znaki specjalne 
 
  - Możliwośc wpisania w pola zdobyte gole, stracone gole, oznaczające ilość  liter
 
  - Po wciśnięciu przyciski "+Dodaj raport" w panelu "Raporty" przycisk zmienia się na przycisk "+ Dodaj mecz" bez informacji 
</details>
<details>
<summary> Ogólna subiektywna :nauseated_face: opinia o aplikacji "Scouts Panel":speaking_head:</summary>
 W mojej opini interfejs aplikacji mało intuicyjny oraz mało atrakcyjny, wręcz nudny. Na stronie aplikacji brak jest walidacji wielu pól.
Brakuje informacji o sposobie działania wielu funkcji aplikacji. Nie chciałabym być uzytkownikem docelowym "Scouts Panel":wink:.
</details>

## Task 2 Przypadki testowe
   
### Subtask 1 Pisanie przypadków testowych na podstawie User Story.
   
:link:[Test Cases](https://docs.google.com/spreadsheets/d/1BS9FQMi4cMR6nWRtIOf_vz-EfgEsHABfbocw8Z0jvYM/edit?usp=share_link)
   
### Subtask 2 Pisanie przypadków testowych na podstawie “własnych doświadczeń.
   
:link:[Test Cases](https://docs.google.com/spreadsheets/d/1ktodWwi7WKhbJfeY0MSsycrN49G2QBi5VYoj_XrG70w/edit?usp=share_link)
   
### Subtask 3 Po co piszemy test case’y?
<details>
<summary>Przypadek testowy wg ISTQB :woman_student:</summary>
 to zbiór danych wejściowych, wstępnych warunków wykonania, oczekiwanych rezultatów i końcowych warunków wykonania opracowany w określonym celu lub dla warunku    testowego, jak wykonanie pewnej ścieżki programu lub zweryfikowanie zgodności z konkretnym wymaganiem.
</details>

<details>
 <summary> Dlaczego piszemy przypadki testowe :thinking:</summary>
 
  * Przypadki testowe są bazą wiedzy o aplikacji
  * Zdarza się, że przypadki testowe są jedyną dokumentacja o tym jak aplikacja prawidłowo powinna działać
  * Przypadki testowe dają możliwość powtarzalnego, udokumentowanego testowania.
  * Przypadki testowe dają możliwość konroli nad zmianami w konkretnych funkcjonalnościach aplikacji 
  * Przypadki testowe pomagają przygotowac dane testowe
  * Przypadki testowe opisują wizję klienta na temat działania aplikacji
</details> 
 <details>
  <summary>Narzędzia do pisania przypadków testowych:hammer_and_wrench:</summary> 
  * [TestLink](https://testlink.org/)
  * [Azure DevOPS](https://learn.microsoft.com/pl-pl/azure/devops/test/create-test-cases?view=azure-devops)
 </details>
 
 ## Task 3 Raportowanie błędów
 
 ### Subtask 1 Utworzenie formatki do zgłaszania błędów systemu
 
 :link:[Web aplication bug report model](https://docs.google.com/spreadsheets/d/1BbqoCe257RGy4SZTcFVb47UgAF1IMKgWGgDmEg4iTbI/edit?usp=sharing)
 
 ### Subtask 2 - Testowanie według planów testów i raportowanie błędów
 
 :link:[Bug reports](https://docs.google.com/spreadsheets/d/1Rvqpqf-KdS0s30Ftb4Haa-QBv1RLKWuH-Nt10hQvDTQ/edit?usp=share_link)
 
 ### Subtask 3 - Raport z wykonanych testów
 
 :link:[Tests report](https://docs.google.com/spreadsheets/d/1IC2BK474OZWyRk0eEsQSZXbyX7HKRuYfet6YZX_M4mY/edit?usp=share_link)
 

 
 ## Task 4 Testowanie aplikacji mobilnych
 
 ### Subtask 1 Utworzenie formatki do zgłaszania błędów systemu
 
  :link:[Mobile aplication bug report model](https://docs.google.com/spreadsheets/d/1NfH42HFPSWqqIKs4Aa1FclGJ-584u-LFOCzniWSXEX4/edit?usp=share_link)
  
###  Subtask 2  Testowanie eksploracyjne i raportowanie błędów
<details>
 <summary> :woman_teacher: Baza wiedzy </summary>
 
 * [Klasy równoważnosci](https://tester.milenabednarczyk.pl/podzial-na-klasy-rownowaznosci-blackbox/)
 * [Analiza wartości brzegowej](https://tester.milenabednarczyk.pl/analiza-wartosci-brzegowych-blackbox/)
 </details>
 
 :link:[Bug report](https://docs.google.com/spreadsheets/d/1CEJ4P2UkTNnLSNW4GrzOVeDnzjqWMgXVwgSVwRIV--E/edit?usp=share_link)
 
### Subtask 3 Do czego służy ta aplikacja?
<details>
<summary>❓Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?</summary>
 
 Aplikacja służy do
 
 * Wystawiania ogłoszeń o:
   * Sprzedaży przedmiotów używanych 
   * Chęci oddania przedmiotów używanych
   * Świadczeniu usług 
   * Poszukiwaniu pacownika
   * Poszukiwaniu pracy 
   * Oferowanej pomocy dla osób z Ukrainy
 * Zakupu ofrerowanych dóbr i usług za pośrednictwem aplikacji bądż bezpośrednio przez spotkanie umówione za pośrednictwem aplikacji ze sprzedającym 
 
 </details>
 <details>
 <summary>❓Kto ma być użytkownikiem końcowym aplikacji?</summary>
 
 * Użytkownikiem końcowym aplikacji ma być oferujący bądź odbiorca - kupujący oferowanych dóbr i usług
 </details>
 <details>
 <summary> ❓Czy według Ciebie aplikacja jest user friendly? (Przyjazna dla użytkownika- np. wchodzisz do aplikacji i szybko łapiesz do czego służą przyciski.</summary>
 
 * Moim zdni plikacja jest przyjazna dla użytkowanika . Szybko i łatwo się zniej korzysta. Jednak moja opinia jest pisana z perspektywy długoletniego użytkownika tej alikacji. Jestem już nauczona "Schematu " poruszania się w OLX slaego opinia nowego użytkownika, który dopiero się jej uczy , może być inna.
</details>
<details>
 <summary> ❓Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?</summary>
 
 
 W aplikacji OLX brakuje mi:
 
  * Możliwości poproszenia o alternatywną wysyłkę- nie przez OLX. Funkcjonalności, która będzie dawała mozliwośc dodania przesyłki od innego przewoźnika niż oferowane przez OLX i możliwości jej kontrolowania/śledzenia 
  * Przycisku/funkcjonalności dającej możiwość zaproponowania ceny ,
  * Możliwości tworzenia zestawów z produktów oferowanych przez jednego użytkowanika i otrzymywania dzięki temu zniżek

 
 </details>
 <details>
 <summary>❓Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej? </summary>
 
 
 Różnice:
 
  * Testowanie aplikacji mobilnej jest mniej wygodne ze względu na wielkość ekranu 
  * Jest wiecej przycisków - więcej rzeczy do przetestowania 
  * Bardzo ważne jest zwrócenie uwagi na lokalizację przycisków/nawigacji aplikacji żeby mozna z niej było szybko i wygodnie korzystać
  * Mnogość urządzeń mobilnych ich wielości ekranów sprawia , trudnośc w wyborze urzadzeń na których powinniśmy przetestować aplikację 
 </details>
 
## Task 5  SQL part 1
<details>
<summary>:woman_teacher:Strukturalny język zapytań (SQL)</summary>
to język deklaratywny stworzony przez firmę IBM w latach 70-tych. Służy on do tworzenia, modyfikowania, jak i wyciągania danych z bazy. Język ten cieszy się dużą popularnością choćby dlatego, że jest interpretowany przez systemy baz danych np.: MySQL czy też Microsoft SQL Server. Jednak nie należy on do bezpiecznych języków. Źle zabezpieczona baza danych może zostać w każdej chwili zaatakowana, w wyniku czego możemy utracić dane..
</details>

<details>
<summary> :woman_teacher:Baza danych</summary> 
to zorganizowany zbiór usystematyzowanych informacji, czyli danych, zwykle przechowywany w systemie komputerowym w formie elektronicznej. Bazą danych steruje zwykle system zarządzania bazami danych (DBMS). Dane i system DBMS oraz powiązane z nimi aplikacje razem tworzą system bazodanowy, często nazywany w skrócie bazą danych.

Dane w najpopularniejszych typach baz danych stosowanych obecnie są zwykle umieszczone w wierszach i kolumnach szeregu tabel, co usprawnia przetwarzanie danych i tworzenie dotyczących ich zapytań. Dzięki temu dostęp do danych, zarządzanie i sterowanie nimi oraz ich modyfikowanie, aktualizowanie i organizowanie jest łatwiejsze. Większość baz danych wykorzystuje do zapisywania danych i tworzenia dotyczących ich zapytań język SQL (Structured Query Language, strukturalny język zapytań).
 </details>
 
### Subtask 1 - Podstawy języka SQL
<details>
<summary> SELECT</summary> 
 
* SELECT * FROM tbl
 
wybiera wszystkie wiersze i kolumny z tabeli tbl
* SELECT c1, c2 FROM tbl
 
 wybiera kolumny c1, c2 i wszystkie wiersze z tabeli tbl
 
* SELECT c1, c2 FROM tbl
 WHERE *warunek*
 ORDER BY c1 ASC, c2 DESC
 
 wybiera rekordy z kolumn c1 i c2 zgodnie z warunkiem
 i porządkuje rekordy zgodnie z kolumną c1 rosnąco i kolumną c2 malejąco
 
 * SELECT DISTINCT c1, c2

 wybiera niepowtarzające się wiersze z kolumn c1 i c2 z tabeli tbl
</details>
<details>
<summary> GROUP BY, HAVING </summary> 
 
 *  SELECT  c1, aggregate(expr)
 FROM tbl
 GROUP BY
 
 Wybiera kolumnę c1 i oblicza funkcję aggregate(expr), grupuje po rekordach z kolumny c1 
 
 * SELECT c1, aggregate(expr) AS c2
 FROM tbl
 GROUP BY c1
 HAVEING c2>V
 
 Wybiera kolumny c1 i c2 jako tymczasowa nazwa kolumny z wynikiem funkcji aggregate(expr)
 Filtruje grupy utworzone naodstawie kolumny c1 z wartościami c2 większymi od V
 </details>
 
</details>
<details>
 
<summary>  COUNT(), AVG() and SUM(), MAX(), MIN()</summary> 
 
* COUNT()
SELECT COUNT(c1)
FROM tbl
WHERE x;
  
liczy rekordy z kolumny c1 dal których jest spełniony warunek x
  
* AVG()
SELECT AVG(c1)
FROM tbl
WHERE x;
  
liczy średnią dla rekordów z kolumny c1 dla których spełniony jest warunek x
  
* SUM()
SELECT SUM(c1)
FROM tbl
WHERE x;

liczy sumę rekrdów c1 z tabeli tbl dla których sełniony jest warunek x
  
* MAX()
SELECT MIN(c1)
FROM tbl
WHERE x;
  
wybiera wartosć maksymalną z rekordów z kolumny c1 dla tabeli tbl dla których spełniony jest warunek x

  
* MIN()
SELECT MIN(c1)
FROM tbl
WHERE x;

wybiera wartosć minimalną z rekordów z kolumny c1 dla tabeli tbl dla których spełniony jest warunek x

</details>
<details>
 
<summary>BETWEEN, IN, NOT IN, LIKE </summary> 
 
 Operatory określające zbiór do jakiego należą dane
 
* BETWEEN
 
Operator BETWEEN wybiera wartości w podanym zakreie (liczb, dat, liter)
bierze pod uwagę rówńież wartości poczatkowe i końcowe
 
SELECT c1
  FROM tbl
  WHERE c1 BETWEEN w1 AND w2;
 
* IN, NOT IN 
 
SELECT c1
  FROM tbl
  WHERE c1 IN (w1,w2....);
  wartości są w zbiorze danych , wartości nie nalerzą do zbioru danych 
 
*  LIKE wartości sa określone wg wzoru 
 
 
   Przykłady:
   - WHERE c1 LIKE 'a%'	znalduje wartości zaczynające się na "a" 
   - WHERE c1 LIKE '%a'	znajduje wartości kończące się na "a"
   - WHERE c1 LIKE '%or%'	znajduje wartości z wyrażeniem "or" 
   - WHERE c1 LIKE '_r%'	znajduje wartości z "r" na drugiej pozycji 
   - WHERE c1 LIKE 'a_%'znajduje wartości zaczynające się na "a" które mają conajmniej 2 znaki 
   - WHERE c1 LIKE 'a__%'	znajduje wartości zaczynające się na "a" które mają conajmniej 3 znaki 
  -  WHERE c1LIKE 'a%o'	znajduje wartości zaczynające się na "a" i kończące się na "o"

 
 
 
 
 
 
 

  
 
 
 
   
   
