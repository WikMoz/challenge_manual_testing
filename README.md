# Spis treści

* [**Task 1**](#task-1)
  * [Subtask 1](#subtask-1)
  * [Subtask 3](#subtask-3)
  * [Subtask 4](#subtask-4)
    * [Testowana aplikacja](#testowana-aplikacja)
    * [Znalezione błędy](#znalezione-błędy)
      - [Strona główna](#strona-główna)
      - [Dodaj gracza](#dodaj-gracza)
      - [Gracze](#gracze)
      - [Dodawanie meczów dla gracza](#dodawanie-meczów-dla-gracza)
      - [Funkcja ROZPOCZNIJ MECZ](#funkcja-rozpocznij-mecz)
      - [Dodawanie raportu do meczu](#dodawanie-raportu-do-meczu)
      - [Raport meczowy](#raport-meczowy)
      
 * [**Task 2**](#task-2)
   * [Subtask 1](#subtask-1-1)
   * [Subtask 2](#subtask-2)
   * [Subtask 3](#subtask-3-1)
   * [Subtask 4](#subtask-4-1)
   
 * [**Task 3**](#task-3)
   * [Subtask 1 & 2](#subtask-1--2)
   * [Subtask 3](#subtask-3-2)
   * [Subtask 4](#subtask-4-2)
     
 * [**Task 4**](#task-4)
   * [Subtask 1 & 2](#subtask-1--2-1)
   * [Subtask 3](#subtask-3-3)
   * [Subtask 4](#subtask-4-3)
---

# Task 1
---

## *Subtask 1*
**10 punktów** :tada:👩🏼‍🎓![image](https://user-images.githubusercontent.com/122229411/215879441-df2a4968-a97c-400b-a9f8-49d0e1ddf7bc.png)


---

## *Subtask 3*
<p align="center">
Cześć!
</p>

<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;Nazywam się Wika 😊. Bardzo się cieszę, że mogę brać udział w tym projekcie, ponieważ chcę pójść zupełnie nową ścieżką 👩‍🚀🚀, wyjść poza to, co znam i w czym czuję się pewnie i bezpiecznie. Zupełnie nie mam doświadczenia w tej dziedzinie, dlatego czuję się trochę zagubiona 😱, ale z drugiej strony też bardzo pozytywnie nakręcona🥳. Mam nadzieję, że poznawanie nieznanego da mi dużo frajdy, satysfakcji i to fantastyczne uczucie, które się pojawia gdy się coś nowego odkrywa🕵️‍♀️. Bardzo chciałabym się jak najwięcej nauczyć, przygotować się jak najlepiej oraz prawidłowo wykonać wszystkie zadania. W DARE IT macie w sobie super energię i entuzjazm, który naprawdę zaraża🤧 i daje kopa do działania i bardzo sie cieszę że mogę się od Was uczyć.


PS Czuję się trochę jak ten Pan na zdjęciu poniżej &darr; - Nie wie czy mu się uda ale przecież MUSI spróbować 🐱‍🐉.
</p>

![](https://i.pinimg.com/originals/47/43/a9/4743a96340c0dc4d46938e6df8f19f65.jpg)

---

## *Subtask 4*

### Testowana aplikacja

**Platforma skautingowa Futbol kolektyw**


<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;Aplikacja służy do zapisywania i zarządzania danymi o wybranych piłkarzach oraz o meczach, w jakich brali udział. Służy do tworzenia szczegółowych oberwacji meczowych  - wprowadzania statystyk meczu z opcją notowania również w trakcie jego trwania. Daje możliwość tworzenia raportów dotyczących danego, obserwowanego zawodnika. </p>

***Funkcjonalości:***

- logowanie
- wylogowanie
- dodanie gracza  
- edycja gracza
- dodanie meczu dla gracza 
- edycja meczu
- przeglądanie danych graczy
- drukowanie danych graczy
- pobranie danych graczy w formie tabeli
- tworzenie raportu z meczu
- prowadzenie statystyk meczu w formie graficznej (plansza)
- kontakt z developerem/pomoc
- monitorowanie ostatnich aktualizacji danych (gracza, meczu, raportu)
- monitorowanie całkowitych ilości graczy, meczów, raportów w tworzonej bazie danych


<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;Aplikacja ma bardzo prostą i mało atrakcyjną szatę graficzną. Elementy na stronie głównej, która jest wizytówką aplikacji są niedopracowane- nieprawidłowe umiejscowienie linków (helpdesk w panelu głównym i główna funkcja strony czyli dodanie gracza w oknie linki pomocnicze), literówki (aktywnosć, zaaktualizowane), brak wyrównania tekstu (linki w oknie aktywność). 
Dodanie gracza, (mimo że opcja znajduje sie w linkach pomocniczych) oraz dodanie meczu dla gracza jest proste, dość intuicyjne. Mało intuicyjnym elemetem, który może sprawiać problemy jest obsługa opcji graficznego przedstawienia/wprowadzania danych statystycznych z meczu. Brakuje instrukcji, opisu przycisków, możliwości edycji już dodanej akcji. Przechodzi się do tej opcji poprzez małą ikonę umieszczoną na końcu tabeli meczów. Również tworzenie raportu może stanowić problem, ponieważ klikając opcję dodaj raport użytkownik jest przekierowywany do tabeli meczów, gdzie musi odnaleźć małą ikonkę odpowiedzialną za tę funkcję. </p>

---


### Znalezione błędy



&nbsp;&nbsp;&nbsp;&nbsp;Testowanie przeprowadziłam na komputerze z systemem Windows Home 10 w przeglądarce Microsoft Edge oraz na telefonie z systemem Android w przeglądarce Google Chrome.

---

#### ***Strona główna***

- przy wchodzeniu na stronę, jeszcze przed zalogowaniem pojawia się kod błędu odpowiedzi HTTP - 404- strona https://scouts-test.kolektyw.pl/pl/favicon.ico nie została odnazleziona 
>request URL: https://scouts-test.kolektyw.pl/pl/favicon.ico 
- pojawiły się informacje o problemie z logowaniem, dlatego sprawdziłam możliwość zalogowania się na kilku przeglądarkach: chrome, edge, firefox i brave – na wszystkich się powiodło
- przy wylogowaniu pojawia się informacja dotycząca braku autouzupełniania formularza logowania '[DOM] Input elements should have autocomplete attributes (suggested: "current-password")'
- przypomnienie hasła przy logowaniu - pojawia się błąd '550 You are not allowed to send e-mails as the domain strapi.io'
- na górze strony głównej – literówka -'ilość meczy' zamiast 'ilość meczów'
- po prawej w okienku aktywność –literówka- aktywnosć (s) zamiast aktywność (ś)
- po lewej stronie - literówki - zaaktualizowany (2 razy 'a') zamiast zaktualizowany - błąd pojawia się 3 razy: zaktualizowany gracz, mecz i raport
- w ‘Scouts panel’ powinna być opcja DODAJ GRACZA, a w ‘linkach pomocniczych’- DEV TEAM CONTACT z adnotacją w języku polskim że chodzi o kontakt/pomoc/helpdesk
- link DEV TEAM CONTACT odsyła do strony logowania na Slack’u
- 'scauts panel' - jest w języku angielskim a cała reszta strony jest przetłumaczona na język polski (panel skautingowy)
- w przypadku utraty połączenia z internetem (celowo ustawiony tryb offline), po odzyskaniu połączenia na stronie głównej pojawia się dodatkowa rubryka 'niezapisany mecz' (oraz dane, którego meczu dotyczy) a pod nim link WRÓĆ DO RAPORTU, który po kliknięciu nie otwiera się.
- Po analizie strony parametr wydajności jest najniższy spośród wszystkich badanych, jednak jest na wysokim poziomie 87%. Parametry, które mogą obniżać wydajność strony to całkowity czas blokowania i zbiorcze przesunięcie układu (analiza lighthouse w devtools)
- brak linku do polityki prywatności
- brak informacji o plikach cookies
- dane w oknie 'Aktywność' rozjeżdżają się (zdjęcie poniżej), nie są wyrównane do lewej jak nagłówki

![image](https://user-images.githubusercontent.com/122229411/212754456-276183fb-53fd-4d4e-b33a-01bfd85fac29.png)


---

#### ***Dodaj gracza***


- przy polach formularza pojawiają się gwiazdki, * do których nie ma odniesienia – na dole strony powinno być odniesienie, że są to pozycje obowiązkowe do wypełnienia w formularzu
- waga – brak jednostki miary w nawiasie (kg) 
- wszystkie informacje są w języku polskim, natomiast na samym końcu jest 'SUBMIT' i 'CLEAR'
- w wersji po angielsku – 'AGE' zamiast DATE OF BIRTH
- literówka – ‘pozycja alternatywa’ zamiast  alternatywna
- można ustawić datę urodzenia z przyszłości, dowolną wagę i wzrost bez ograniczeń, przedziałów
- telefon - można wpisać zbyt dużą ilość znaków 
- niewiele miejsca na wpisanie osiągnięć
- przed polami ‘łączy nas piłka’ ‘90min’ ‘profil facebook’ brak nagłówka –  np. profile w portalach
- dobrym rozwiązaniem byłaby lista wyboru opcji do ‘główna pozycja’, ‘pozycja alternatywna’, ‘poziom rozgrywek’, szczególnie ważna w przypadku pozycji zawodnika - (bramkarz ma inne opcje do wyboru w statystykach meczów niż np. napastnik i gdy wpisze się pozycję z literówką nie można wprowadzić prawidłowo danych)
- użytkownicy mogą zmieniać dane wpisane przez innego użytkownika
- email - w przypadku wpisania adresu email w nieprawidłowej formie nie ma możliwości zapisania gracza, jednak pole email nie podświetla się na czerwono z odpowiednią adnotacją. W devtools pojawia się informacja ["email must be a valid email"]
- przycisk 'CLEAR' usuwa tylko dane wpisane jako nowe, nie ma funkcji wyczyszczenia wszystkich danych po kliknięciu, a jedynie tych które nie zostały zapisane
- pole 'województwo' nie jest oznaczone gwiazdką jako obowiązkowe, jednak w momencie gdy chcemy utworzyć raport meczu pojawia się komunikat o konieczności uzupełnienia tego pola

---

#### ***Gracze***


- po otwarciu sekcji gracze pojawia się komunikat:
>Params `start` and `limit` are deprecated. Use `_start` and `_limit`”
- wszystkie informacje są w języku polskim, natomiast przy ikonkach w prawym górnym rogu wyświetlają się napisy po angielsku ‘download’, ‘print’, ‘view columns’, ‘filter rate’
- tak samo po kliknięciu w ‘view columns’ mamy ‘show columns’ i  w ‘filter rate’ mamy ‘filters’, ‘rate’ i ‘age’ a pozostałe pozycje są po polsku
- po kliknięciu w ikonę ‘download CSV’ pobieramy plik, w którym:
   * wiek nie jest wyliczony lecz przedstawiany jako data urodzenia
   * w kolumnach recenzji, meczów i raportów pojawia się : ‘[object]’ zamiast danych liczbowych
   * pobrany plik dotyczy tylko wyświetlanych w oknie wyników (max 10 pozycji), nie ma możliwości pobrania wszystkich danych jednocześnie
- nie można przefiltrować wyników pod kątem ilości raportów, meczów, recenzji
- po wybraniu drukowania – raport drukuje się bez marginesów ale może to celowe. Tabela jest odwrócona – inny układ tabeli niż na stronie i nie możliwości zmiany tego układu.

---

#### ***Dodawanie meczów dla gracza***


- '*' gwiazdka przy niektórych polach formularza bez odnośnika z wyjaśnieniem, że chodzi o pola obowiązkowe
- jest możliwość ustawienia daty meczu w przyszłości
- czas gry - brak jednostki czasu w nawiasie (min) oraz brak ograniczeń, przedziału - można wpisać dowolną wartość
- numer – trzeba dopisać, że chodzi o numer na koszulce (taka informacja pojawia się na raporcie meczowym)
- webmatch – powinno być : link do meczu
- general – pozycja w języku angielskim, gdy pozostałe są w języku polskim. Nie wiadomo do czego się odnosi ta rubryka - czy chodzi o uwagi ogólne?
- w edycji meczu dla gracza na dole mamy listę zdarzeń – w rubryce 'meta dane; pojawiają się komunikaty takie jak np. 'meta._id' (zdjęcie poniżej) 

![image](https://user-images.githubusercontent.com/122229411/212755904-43fdce05-e532-45a8-a570-3b9f2ae3d2e4.png)

- rubryka 'meta dane' powinna mieć inną nazwę odnoszacą się do zawartości tej rubryki
- przycisk 'clear' usuwa tylko dane wpisane jako nowe, nie ma funkcji wyczyszczenia wszystkich danych po kliknięciu, a jedynie tych które nie zostały zapisane
- lista zdarzeń powinna być osobno lub np. jako uzupełnienie raportu meczowego - jest na stronie pod edycją meczu. Jej umiejscowienie nie jest logiczne i można jej nie zauważyć.
- na liście zdarzeń nie ma podziału na połówki meczu - np. jeśli akcja odbędzie się w 5 sekundzie drugiej połowy jest oznaczana jako 5 sekunda (tak samo jakby odbyła się w 5 sekundzie pierwszej połowy meczu)
- strona nie dostosowuje się do ekranu smartfona w edycji meczu oraz w tabelach meczów 

---

#### ***Funkcja ROZPOCZNIJ MECZ*** 

- funkcja jest dostępna pod ikoną piłki nożnej w zakładce mecze - mało intuicyjne, może powodować trudności w odnalezieniu
- brak instrukcji, opisu co to jest, jak działa i w jakim celu jest umieszczone (raportowanie danych statystycznych meczu)
- przyciski funkcji nie posiadają opisów
- przycisk z obrazkiem kosza nie usuwa wcześniej zapisanych akcji, jedynie nowe
- jest możliwość wyboru ujemnych wartości oraz powyżej 2 połówek meczu. Brak możliwości zaznaczenia osobno czasu dogrywki i rzutów karnych. W języku angielskim zamiast połówka meczu (half) występuje słowo part - jako kolejna część meczu. W języku polskim można by również zastąpić słowo połowa słowem część meczu, aby uwzględnić kolejne etapy jak dogrywka, rzuty karne. 
- jest możliwość wpisania nierealnych wartości czasu trwania meczu – po wpisaniu bardzo wysokiej wartości pojawiają się liczby ujemne (zdjęcie poniżej)

![image](https://user-images.githubusercontent.com/122229411/212908513-44f29e08-f7bd-432f-8d4a-e33f25a085c3.png)

- komentarze dopisywane podczas oznaczania danej akcji na planszy nie pojawiają się potem w raporcie – pojawiają się na liście akcji
- po dodaniu danej akcji na planszy nie można do niej wrócić, zmienić jej, rozróżnić lub usunąć. Trzeba albo usunąć wszystko albo użyć opcji cofnij, która jest oznaczona strzałką
- można zaznaczać nielogiczne akcje np. jednocześnie: dośrodkowanie po przyjęciu oraz rzut rożny
- dla bramkarza  - literówka w interwencjach - PRZERWANIE PODANIE
- dla bramkarza można dodać akcję 'podanie ręką' a gdy się ją uruchomi do zaznaczenia mamy podanie lewą i prawą NOGĄ (zdjęcie poniżej)

![image](https://user-images.githubusercontent.com/122229411/212756584-8e155246-a263-46a4-b629-4cf33e5d0fa6.png)


---

#### ***Dodawanie raportu do meczu***



- po kliknięciu ‘dodaj raport’ odsyła do zakładki mecze – tam trzeba znaleźć odpowiednią ikonkę 'raport'. Dobra byłaby funkcja dodania raportu w zakładce raporty ale umożliwiająca wybór do którego meczu dany raport się odnosi
- po kliknięciu utwórz raport pojawia się okno tworzenie raportu gracza z danymi ID gracza i ID meczu, które musimy potwierdzić (zdjęcie poniżej). Czy jest to potrzebny krok? Może wystarczające byłoby przekierowanie bezpośrednio do okna tworzenia raportu. 

![image](https://user-images.githubusercontent.com/122229411/212759422-376b12cb-8849-46c5-9a43-d1d0e16502b1.png)

- Przyciski 'submit' i 'clear' są w języku angielskim, gdy cała strona jest w języku polskim.
- Przycisk 'clear' nie powoduje wyczyszczenia danych z formularza. Dane te są nieedytowalne, więc przycisk 'clear' jest tu zbędny.
- można dodać wiele raportów do jednego meczu i nie można ich usunąć
- strona nie dostosowuje się do ekranu smartfona w tabeli raportów

---

#### ***Raport meczowy***

- przycisk ‘save’ porusza się razem z przewijaniem raportu i może zasłaniać pola ‘dane meczu’ oraz ‘komentarz dodatkowy’ 
- przycisk ‘save’ w wersji po polsku powinien być w formie ‘zapisz’
- link do meczu nie odsyła do podanego linku (mimo że podany w edycji meczu link jest prawidłowy) – błąd 404
- wstęp – brak spacji po nawiasie
- inteligencja boiskowa -’Ustawienie na boisku//szukanie wolnej przestrzeni/ruch bez piłki’ – dwa ukośniki i brak kropki na końcu zdania i spacji przed kolejnym.
- mentalność – brak kropki po nawiasie: ‘(czerwona kartka/strata gola itp.)’ i brak znaku zapytania w ostatnim zdaniu.
- recenzja – polecenie brzmi: ‘Wybieramy 1 z poniższych punktów’, natomiast gwiazdki można zaznaczać też jako połówki punktów np. 3,5
- raportu nie można wydrukować 
- strona nie dostosowuje się do ekranu smartfona w edycji raportu
- dane statystyczne:

  * Gdy nie mamy danych do danego wykresu, pojawia się nagłówek (jeśli jest), a pod nim same opisy kolumn wykresu oraz komentarz ‘nie odnotowano’. Sam nagłówek wykresu i komentarz ‘nie odnotowano’ byłby bardziej czytelny w przypadku braku danych.
  * nad drugim wykresem odnoszącym się do podań krótkich jest nagłówek ‘kierunek podań’. Czytelniejszy byłby ‘kierunek podań krótkich’
  * nad trzecim wykresem brakuje nagłówka  np. ‘kierunek podań długich’
  * nad szóstym i dziesiątym wykresem również brak nagłówków
  * brak danych dotyczących dośrodkowania głową (możliwych do zaznaczenia na planszy dla napastnika)
  * brak danych dotyczących pojedynków 1 na 1 (możliwych do zaznaczania na planszy dla napastnika) (np.2 graczy, 3 graczy, 4 lub więcej graczy, przejęcie, przerwanie)
  * brak danych w raporcie odnośnie rzutów karnych i wolnych, które na planszy można zaznaczać wybierając opcję strzały, pojawiają się w liście zdarzeń pod edycją     meczu
  * inne nazwy odbioru na planszy i w raporcie – odbiór ‘głową’ na planszy, ‘w walce o górną piłkę’ na raporcie oraz straty 'holowanie piłki' na planszy i ‘przez przetrzymywanie piłki’ na raporcie
  * w wersji angielskiej mamy dwa razy fouled (zarówno jako 'faulowany' i jako 'faulował')
  * dla bramkarza – brak wykresów dla podań ręką, interwencji, obron strzału, brak danych o piłce poza polem karnym. Nie pojawiają się raporcie również dane o faulowaniu i byciu faulowanym. Konieczne jest dostosowanie raportu dla każdej pozycji zawodnika.

---
---


# Task 2
---

## *Subtask 1*

[Subtask 1 - test cases for user stories](https://docs.google.com/spreadsheets/d/1lodk83NlXzVX2n_N-y8rW2jbiDuHJxqD/edit?usp=sharing&ouid=117170517202558210113&rtpof=true&sd=true)

---

## *Subtask 2*

[Subtask 2 - test cases](https://docs.google.com/spreadsheets/d/1YmXbnhtnpeROPaZI6VZ_JnWPs83CFGMd/edit?usp=sharing&ouid=117170517202558210113&rtpof=true&sd=true)


---
## *Subtask 3*

**Why we are writting test cases?**

Test case is a set of conditions under which tester will determine whether an application or software system or one of its feature is working as expected.

Test case writting:

- clarify what needs to be done to test the system
- provide a clear and straightforward testing instuction
- gives us a steps which we execute in a system
- gives us the input data values which we enter in the system
- gives us expected results when we execute a perticular test case
- helps to expand test coverage
- are like the checklist to ensure that we are not missing anything that is required
- helps us to not skip as much as in ad-hoc testing

---

## Subtask 4  


[Subtask 4 - test cases for pick.eat.up app](https://docs.google.com/spreadsheets/d/1Z4GQxUTicf-5v0iVSGIMF_72bpZmDYHq/edit?usp=sharing&ouid=117170517202558210113&rtpof=true&sd=true) 

![image](https://user-images.githubusercontent.com/122229411/216087729-a6a76f30-e267-4b39-804c-e36a9d012ed2.png)


---
---


# Task 3
---

## *Subtask 1 & 2* 

[Subtask 1 & 2 - bug report](https://docs.google.com/spreadsheets/d/1yNjSEN-VvtSfSd5MfSlgpfMwzW0bd1FGTANk7rX8lcE/edit?usp=sharing)  

![image](https://user-images.githubusercontent.com/122229411/216088152-1b175371-6e0f-4707-84fa-1ed97f5faa8d.png)


---

## *Subtask 3*

[Subtask 3 - test report](https://docs.google.com/spreadsheets/d/1IvBLQX9O88la2VP2aUuf9GlSBBfTlNkv5cXqbucVlKc/edit?usp=sharing) 

![image](https://user-images.githubusercontent.com/122229411/216088312-035e083e-f56f-40c8-a90b-17d008375ce1.png)


---
## *Subtask 4*

[Subtask 4 - explorative testing - tour](https://docs.google.com/spreadsheets/d/1TrnbCMN6Ii4YK9mdQORSYsZ59pRR7AjU5uM4_7y8bEg/edit?usp=share_link) 

![image](https://user-images.githubusercontent.com/122229411/216087970-2eb30d9e-994e-4daf-8dd0-0409c71f1a28.png)


---
---


# Task 4
---

## *Subtask 1 & 2* 

🐛[Subtask 1 & 2 - bug report](https://docs.google.com/spreadsheets/d/1psyvC75DrlCn2q9qnlad02WGcFH9bQkzEdPt1OVgCuA/edit?usp=share_link)


---

## *Subtask 3*

*Aplikacja natywna OLX*
![image](https://user-images.githubusercontent.com/122229411/216633952-e635b138-7ad0-47c9-9b23-1d99e464422b.png)

**1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?**

Aplkacja olx służy do:

- kupna/sprzedaży/wymiany lub oddawania za darmo: nowych i używanych produktów, nieruchomości czy usług,
- poszukiwania/publikowania ofert pracy,
- poszukaiwania nowego domu dla zwierząt.

Uzytkownicy mogą:

- wyszukiwać, przeglądać, wybierać, zapisywać oferty,
- obserwować zdefiniowane przez siebie wyszukiwania, sprzedających lub konkretne oferty
- dodawać własne oferty wraz ze zdjęciami 
- nawiązywać kontakt ze sprzedającym/kupującym poprzez podany formularz lub podając swój numer telefonu jako sprzedający
- skorzystać z opcji przesyłki olx
- dokonywać płatności za pośrednictwem aplikacji

**2. Kto ma być użytkownikiem końcowym aplikacji?**

Uzytkownikiem końcowym aplikacji są osoby sprzedające/ kupujące/ wymieniające/ oddające z darmo produkty, nieruchomości, usługi jak również szuakjące nowego domu dla zwierząt

**3. Czy według Ciebie aplikacja jest user friendly?**

1) Aplikacja jest intuicyjna, łatwa w obsłudze i dostępna dla wszystkich.
2) Po pierwszym uruchomieniu aplikacji użytkownikowi wyświetlają się podpowiedzi/instrukcje jak poruszać się po aplikacji. Nawigacja po aplkacji jest łatwa i logiczna, pozwala na szybkie zapoznanie się z zawartością kluczowych części.
3) Jest dostępne centrum pomocy a w nim wyszukiwarka z podziałem na kategorie, FAQ, porady, przydatne wskazówki, opcja 'sprawdż link do "odbioru wypłaty". Istnieje możliwość bezpośredniego kontaktu w celu uzyskania pomocy - formularz kontaktowy jest zamieszczony pod artykułami dotyczącymi konkretnych zapytań w centrum pomocy. Fromularz ten mógłby być również umieszczony w miejscu łatwiej dostępnym dla użytkownika. 
4) Czasami aplikacja zawiesza się podczas użytkowania, ładownie zdjęć jest spowolnione. Zdarza się, że dodani do ulubionych sprzedawcy pokazują się z opóźnieniem w sekcji 'Obserwujesz'. 
5) Aplikacja nie posiada trybu oszczędzania energii. 
6) Dane zapisane w aplikacji synchronizują się z tymi ze strony internetowej olx - można łatwo zarządzać dostępem do konta użytkownika na róznych urządzeniach. 
7) Aplikacja ma możliwość wyświetlania personalizowanych powiadomień push. Uzytkownik ma zapewnioną mozliwość wyboru co spowoduje pojawienie się powiadomienia np. pojawienie się nowego ogłoszenia pasującego do tego co obserwuje dany użytkownik.
8) Występuje dwuczynnikowa weryfikacja - podczas próby dodania oferty użytkownik musi być zalogowany a następnie proszony jest o podanie numeru telefonu, na który wysyłany jest kod weryfikujący. 
70 Aplikacja posiada tryb jasny i ciemny umożliwiający użytkownikowi wybór bardziej przyjaznego w odbiorze ekranu aplikacji


**4. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?**

- Dodanie trybu oszczędzania energii
- Szybszy, łatwiejszy dostęp do formularza kontaktowego w celu uzyskania pomocy
- Krótki film instuktarzowy na początku dla nowych użytkowników (i możliwy do pominięcia) (np. szczególnie dla osób starszych mniej zaznajomionych z tego typu aplikacjami)
- Bardziej zaawansowana wyszukiwarka noclegów: noclegi do zaznaczenia z kalendarzem przyjazdu i wyjazdu oraz widoczne na mapce z cenami (np. jak na booking.com)
- Usługi, wypozyczenia również mogłyby mieć opcje dodania kalendarza dostępności 
- Produkty dla dzieci mogłyby mieć filtrowanie z kategorią wiekową
- Możliwość dodania opinii o kupującym z komentarzem
- Możliwość dodania opinii o sprzedajacym z komentarzem
- Możliwość wsparcia Wielkiej Orkiestry Świątecznej Pomocy/ Organizacji charytatywnej (np. złotówka przy zakupie)
- Możliwość automatycznego skierowania prośby do wysyłającego o opakowanie bardziej ekologiczne (np. mniej plastiku) - np. opcja do zaznaczenia przy wybieraniu formy dostawy


**5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?**
 
 Testowanie aplikacji natywnej vs internetowej
 
 W aplikacja natywnej w odróżnieniu do aplikacji internetowej należy sprawdzić:
 
- Dodatkowe połączenia z urządzeniami do których aplikacja ma dostęp jak geolokacja, czujniki światła, powiadomienia push, kamera itp. 
- Wpływ zmiany orientacji obrazu na zachowanie, dostosowywanie się aplikacji (landscape/portrait mode)
- Czy aplikacja działa również w trybie offline jęsli jest do tego dedykowana
- Jak bardzo energochłonne jest używanie aplikacji na telefonie
- Responsywność - działanie aplikacji na różnych modelach smartfonów, na róznych systemach operacyjnych Android, iOS
- Czy umiejscowanie nawigacji jest wygodne w uzytkowaniu na telefonie - czy jest nisko przy kciuku

W aplikacji internetowej w odróżnieniu od natywnej:
- Można do testowania użyć devtools dzięki czemu można zobaczyć jakiego rodzaju błąd się pojawia w systemie gdy jakaś funkcja nie działa prawidłowo
- Należy zbadać responsywność w odniesieniu do używania aplikacji zarówno na komputerze jak i na różnych modelach smartfonów 
- Obserwuje się prędkość wczytywania strony
- Bada się funkcjonowanie aplikacji na róznych przeglądarkach


---
## *Subtask 4*



