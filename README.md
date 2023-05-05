## Task 1 Exploratory testing

### Subtask 1 Test result

*9/10* 	:sweat_smile:

### Subtask 3 Dlaczego zdecydował_ś się na udział w challenge portfolio?

* Na zmianę ścieżki zawodowej zdecydowałam się około rok temu. Zaczełam czytać o zawodzie testera. Uczestniczyłam w kilku kursach online z manualnego testowania oprogramowania. Po mieściącu " zabawy" w testera zdecydowałam, że to zawód dla mnie, że chcę to robić. Zdałam egzamin ISTQB. Wtedy usłyszałam od kolzeżanki o Dare IT. 
Wzięłam udział w targach pracy zorganizowanych przez dziewczyny. Armosfera była świetna, wiele dowiedziałam się o możliwościach nauki i szukania pracy jako tester, byłam zachwycona prezentacjami partnerów. Wtedy zdecydowałam, że chcę się uczyć dalej z Dare IT 😃*

### Subtask 4 Scouts panel- expoatory testing
<details>
<summary> Do czgo służy aplikacja "Scouts Panel" :bouncing_ball_person: </summary>
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
   
:link:https://docs.google.com/spreadsheets/d/1BS9FQMi4cMR6nWRtIOf_vz-EfgEsHABfbocw8Z0jvYM/edit?usp=share_link
   
### Subtask 2 Pisanie przypadków testowych na podstawie “własnych doświadczeń.
   
:link:https://docs.google.com/spreadsheets/d/1ktodWwi7WKhbJfeY0MSsycrN49G2QBi5VYoj_XrG70w/edit?usp=share_link
   
### Subtask 3 Po co piszemy test case’y?
<details>
<summary>Przyoadek testowy wg ISTQB :woman_student:</summary>
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
  * TestLink https://testlink.org/
  * Azure DevOPS https://learn.microsoft.com/pl-pl/azure/devops/test/create-test-cases?view=azure-devops
  
   
   
