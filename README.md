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

  
 
 
 
   
   
