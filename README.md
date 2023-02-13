# Spis treści

 * ## [**Task 1**](#task-1)
   * [Subtask 1](#subtask-1)
   * [Subtask 3](#subtask-3)
   * [Subtask 4](#subtask-4)
     * [Testowana aplikacja](#testowana-aplikacja)
     * [Znalezione błędy](#znalezione-błędy)
       1) [Strona główna](#strona-główna)
       2) [Dodaj gracza](#dodaj-gracza)
       3) [Gracze](#gracze)
       4) [Dodawanie meczów dla gracza](#dodawanie-meczów-dla-gracza)
       5) [Funkcja ROZPOCZNIJ MECZ](#funkcja-rozpocznij-mecz)
       6) [Dodawanie raportu do meczu](#dodawanie-raportu-do-meczu)
       7) [Raport meczowy](#raport-meczowy)
      
 * ## [**Task 2**](#task-2)
   * [Subtask 1](#subtask-1-1)
   * [Subtask 2](#subtask-2)
   * [Subtask 3](#subtask-3-1)
   * [Subtask 4](#subtask-4-1)
   
 * ## [**Task 3**](#task-3)
   * [Subtask 1 & 2](#subtask-1--2)
   * [Subtask 3](#subtask-3-2)
   * [Subtask 4](#subtask-4-2)
     
 * ## [**Task 4**](#task-4)
   * [Subtask 1 & 2](#subtask-1--2-1)
   * [Subtask 3](#subtask-3-3)
   * [Subtask 4](#subtask-4-3)
   
 * ## [**Task 5**](#task-5)
   * [Subtask 1](#subtask-1-2)
   * [Subtask 3](#subtask-3-4)
  
---

# Task 1
---

## *Subtask 1*
**10 punktów** ![image](https://user-images.githubusercontent.com/122229411/215879441-df2a4968-a97c-400b-a9f8-49d0e1ddf7bc.png)


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

---
### 1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?

*Aplikacja OLX służy do:*

- kupna/sprzedaży/wymiany lub oddawania za darmo: nowych i używanych produktów👕🏀, nieruchomości🏡 czy usług👨🏼‍🔧💅🏼🚀,
- poszukiwania/publikowania ofert pracy, 👨🏼‍💼
- poszukiwania nowego domu dla zwierząt. 🐕🐈🐠

*Uzytkownicy mogą:*

- wyszukiwać, przeglądać, wybierać, zapisywać oferty,
- obserwować zdefiniowane przez siebie wyszukiwania, sprzedających lub konkretne oferty,
- dodawać własne oferty wraz ze zdjęciami, 
- nawiązywać kontakt ze sprzedającym/kupującym poprzez podany formularz lub podając swój numer telefonu jako sprzedający,
- korzystać z opcji przesyłki olx,
- dokonywać płatności za pośrednictwem aplikacji.
---
### 2. Kto ma być użytkownikiem końcowym aplikacji?

Uzytkownikiem końcowym aplikacji są osoby sprzedające/ kupujące/ wymieniające/ oddające z darmo produkty, nieruchomości, usługi jak również szukające nowego domu dla zwierząt

---
### 3. Czy według Ciebie aplikacja jest user friendly?

1. ❤ Aplikacja jest intuicyjna, łatwa w obsłudze i dostępna dla wszystkich.
2. ❤ Po pierwszym uruchomieniu aplikacji użytkownikowi wyświetlają się podpowiedzi/instrukcje jak poruszać się po aplikacji. Nawigacja po aplkacji jest łatwa i logiczna, pozwala na szybkie zapoznanie się z zawartością kluczowych części.
3. ❤ Jest dostępne centrum pomocy a w nim wyszukiwarka z podziałem na kategorie, FAQ, porady, przydatne wskazówki, opcja 'sprawdż link do "odbioru wypłaty". Istnieje możliwość bezpośredniego kontaktu w celu uzyskania pomocy - formularz kontaktowy jest zamieszczony pod artykułami dotyczącymi konkretnych zapytań w centrum pomocy.  
4. 💔 Formularz ten mógłby być również umieszczony w miejscu łatwiej dostępnym dla użytkownika. 
5. 💔 Czasami aplikacja zawiesza się podczas użytkowania, ładownie zdjęć jest spowolnione. Zdarza się, że dodani do ulubionych sprzedawcy pokazują się z opóźnieniem w sekcji 'Obserwujesz'. 
6. 💔 Aplikacja nie posiada trybu oszczędzania energii. 
7. ❤ Dane zapisane w aplikacji synchronizują się z tymi ze strony internetowej olx - można łatwo zarządzać dostępem do konta użytkownika na róznych urządzeniach. 
8. ❤ Aplikacja ma możliwość wyświetlania personalizowanych powiadomień push. Uzytkownik ma zapewnioną mozliwość wyboru co spowoduje pojawienie się powiadomienia np. pojawienie się nowego ogłoszenia pasującego do tego co obserwuje dany użytkownik.
9. ❤ Występuje dwuczynnikowa weryfikacja - podczas próby dodania oferty użytkownik musi być zalogowany a następnie proszony jest o podanie numeru telefonu, na który wysyłany jest kod weryfikujący. 
10. ❤ Aplikacja posiada tryb jasny i ciemny umożliwiający użytkownikowi wybór bardziej przyjaznego w odbiorze ekranu aplikacji

---
### 4. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?

- Dodanie trybu oszczędzania energii 🔋
- Szybszy, łatwiejszy dostęp do formularza kontaktowego w celu uzyskania pomocy 🧯🔥
- Krótki film instuktarzowy na początku dla nowych użytkowników (i możliwy do pominięcia) (np. szczególnie dla osób starszych mniej zaznajomionych z tego typu aplikacjami) 🎬
- Bardziej zaawansowana wyszukiwarka noclegów: noclegi do zaznaczenia z kalendarzem przyjazdu i wyjazdu oraz widoczne na mapce z cenami (np. jak na booking.com)🗺
- Usługi, wypożyczenia również mogłyby mieć opcje dodania kalendarza dostępności 🗓
- Produkty dla dzieci mogłyby mieć filtrowanie z kategorią wiekową 👶🏼
- Możliwość dodania opinii o kupującym z komentarzem 📜
- Możliwość dodania opinii o sprzedajacym z komentarzem 📜
- Możliwość wsparcia Wielkiej Orkiestry Świątecznej Pomocy/ Organizacji charytatywnej (np. złotówka przy zakupie) 🦽
- Możliwość automatycznego skierowania prośby do wysyłającego o opakowanie bardziej ekologiczne (np. mniej plastiku) - np. opcja do zaznaczenia przy wybieraniu formy dostawy🌍

---
### 5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?

 
 W aplikacji natywnej w odróżnieniu do aplikacji internetowej należy sprawdzić:
 
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


https://sirtester.atlassian.net/browse/CPP

*1) CPP-2 The registration window is cropped*
- AUTHOR: Wiktoria Mozalewska
- [CPP-2.pdf](https://github.com/WikMoz/challenge_portfolio_Wiktoria/files/10614016/CPP-2.pdf)
- SCREENSHOT/ SCREENCAST:	
[CPP-2](https://user-images.githubusercontent.com/122229411/216847250-a513ca26-e12c-41da-864d-a2dba5616a9e.mp4)


*2) CPP-3	After adding new like ('polub') - the total number of likes doesn’t change*
- AUTHOR: Wiktoria Mozalewska
- [CPP-3.pdf](https://github.com/WikMoz/challenge_portfolio_Wiktoria/files/10614000/CPP-3.pdf)
- SCREENSHOT/ SCREENCAST:
[CPP-3](https://user-images.githubusercontent.com/122229411/216847701-300ed0ba-5723-4497-9161-75d6f979d810.mp4)


*3) CPP-4 The quick flash of previous article before opening the new, chosen one*
- AUTHOR: Wiktoria Mozalewska
- [CPP-4.pdf](https://github.com/WikMoz/challenge_portfolio_Wiktoria/files/10613994/CPP-4.pdf)
- SCREENSHOT/ SCREENCAST:
[CPP-4](https://user-images.githubusercontent.com/122229411/216848500-90ff042e-636a-4212-984f-4ae05ceee7c8.mp4)


*4) CPP-5 No possibility to add comment to the article*
- AUTHOR: Wiktoria Mozalewska
- [CPP-5.pdf](https://github.com/WikMoz/challenge_portfolio_Wiktoria/files/10613982/CPP-5.pdf)
- SCREENSHOT/ SCREENCAST:
[CPP-5](https://drive.google.com/file/d/1Hk4CA7y46jmeFjd4jy2x-7m2uVLGanS4/view?usp=share_link)


*5) CPP-6 Name of the author overlaps the icons*
- AUTHOR: Wiktoria Mozalewska
- [CPP-6.pdf](https://github.com/WikMoz/challenge_portfolio_Wiktoria/files/10613965/CPP-6.pdf)
- SCREENSHOT/ SCREENCAST:
[CPP-6](https://drive.google.com/file/d/1lOVSLKrvoZg3jJ-e3gnJUDC9dj4ZoO_Z/view?usp=share_link)

Zadanie robiłam w grupie z :
- Sonią Topolewską
- Iwoną Mierzejewską
- Adrianem Pachowskim

---
---

# Task 5
---

## *Subtask 1*

### Wymień operatory/zapytania, których się nauczyłeś:

---

#### 1. Pierwsze zapytania

- `USE AdventureWorks2014` - zmiana kontekstu bazy danych na AdventureWorks2014 (przełącz się na bazę danych AdventureWorks2014)

- `SELECT * FROM Productionn.Product` - polecenie, które wyświetla zawartość tabeli (* - pokaż zawartość wszystkich kolumn) z tabeli Production.Product (gdzie: Production to nazwa schematu, która umożliwia grupowanie tabel aby ułatwić nadawanie uprawnień i Product to nazwa tabeli) 

- `GO`- dzieli nam zapytania (albo wsady - czyli jakiś szereg instrukcji) na osobne zapytania- przyspieszy to wykonanie skryptu

- `SELECT * FROM [HumanResources].[Job Candidate]` - jeśli chcemy napisać nazwę tabeli ze spacją w zapytaniu - konieczne jest użycie []

- `SELECT ProductID, Name, Color, Size FROM Production.Product` - chcemy wyświetlić wybrany zestaw kolumn: ProductID, Name, Color, Size z tabeli Production.Product

- `SELECT ProductID AS ID, Name AS Nazwa, Color AS Kolor, Size AS Rozmiar FROM Production.Product` - aliasy - można dodać po nazwie kolumny (np.Name) słowo 'AS' i dalej nazwa kolumny, która ma nam się wyświetlić zamiast tej istniejącej (np. 'Nazwa') - nie zmienia się struktura tej kolumny, nie wprowadzamy zmian w tabeli- jedynie zmienia się nazwa w wyniku (np. z 'Name' na 'Nazwa')

--- 

#### 2. Sortowanie danych

- `SELECT * FROM Production.Product` :

    - `ORDER BY Name` - wiersze posortowane są ROSNĄCO wg zawartości kolumny Name
    - `ORDER BY Name ASC` - wiersze posortowane są ROSNĄCO wg zawartości kolumny Name
    - `ORDER BY Name DESC` - wiersze posortowane są MALEJĄCO wg zawartości kolumny Name
    - `ORDER BY Color, Name` - wiersze posortowane wg koloru ROSNĄCO, a te które mają ten sam kolor - wg nazwy ROSNĄCO
    - `ORDER BY Color DESC, Name` - wiersze posortowane MALEJĄCO wg koloru i ROSNĄCO wg nazwy
    
---

#### 3. Filtrowanie danych

- `SELECT * FROM Production.Product` :

   - `WHERE ProductID = 707` - wyszukuje produkt o wybranym identyfikatorze 707
   - `WHERE ProductID > 100` - > -wyszukuje produkty o identyfikatorze większym niż 100
   - `WHERE ProductID BETWEEN 14 AND 290` - BETWEEN..AND.. - wyszukuje produkty o identyfikatorze pomiędzy 14 a 290
   - `WHERE Color = 'Red'`- wyszukuje produkty o kolorze Red. Wartości tekstowe zapisujemy w pojedynczych apostrofach
   - `WHERE Color <> 'Red'`- wyszukuje produkty o kolorze innym niż Red
   - `WHERE Color != 'Red'`- wyszukuje produkty o kolorze innym niż Red.
   - `WHERE Size = 'M'` -wyszukuje produkty w rozmiarze M
   - `WHERE Name LIKE 'B%'` - Operator LIKE - wyszukuje produkty zaczynające się na literę B. % oznacza dowolony znak w dowolnej liczbie występujący po tej literze B ( z samym B włącznie)
   - `WHERE Name LIKE '%Bike%'` - wyszukuje produkty, które gdzieś w nazwie mają Bike obojętne czy na początku czy na końcu
   - `WHERE Name = 'Bike'` - wyszukuje produkty które nazywają się dokładnie 'Bike'
   - `WHERE Name LIKE 'Bike Socks, _'` - (_ dowolny pojedynczy znak) wyszukuje proukty, w którch po 'Bike Socks' występuje przecinek, spacja i jakiś pojedynczy znak np. Bike Socks, M (ale Bike Socks, XL już nie zostanie wyświetlone)
   - `WHERE Color = 'Black' AND Size = 'M'` - (operator AND) wyszukuje produkty koloru czarnego, o rozmiarze M
   - `WHERE Color = 'Black' OR Color = 'Silver' OR Color = 'Blue'` - (operator OR) - produkty koloru czarnego, srebrnego i niebieskiego
   - `WHERE Color IS NULL` - (zamiast niepoprawnego ~WHERE Color = NULL~) - wyszukuje wszytskie produkty które nie mają zdefiniowanego koloru - kolor nie jest określony w tabeli
   - `WHERE Color IS NOT NULL` - wyszukuje wszystkie produkty, które mają określony kolor (nie wyszukuje pozycji z kolorem oznaczonym jako NULL)
   - `WHERE Name LIKE '%Bike%' AND Color = 'White'` - wyszukuje wszystkie które gdzieś w nazwie mają Bike i są w kolorze białym
   - `WHERE Color = 'Black' AND Size IS NOT NULL AND Name LIKE '%Frame%' - wyszukuje produkty w kolorze czarnym, jakimś określonym rozmiarze i które gdzieś w nazwie mają Frame
   - `WHERE (Color = 'Black' AND Size = 'M') OR (Color = 'Red' AND Name LIKE '%Road%')` - (nawiasy) - wyszukuje produkty koloru czarnego i w rozmiarze M LUB czerwone produkty, które gdzieś w nazwie mają 'Road'
   - `WHERE Color = 'Black' OR Color = 'Red'` lub `WHERE Color IN ('Black', 'Red')` - wyszukje produkty czarne i czerwone, zamiast niepoprawnego:~`WHERE Color = 'Black' AND Color = 'Red'`~ gdzie warunki się wykluczają: produkty i czarne i czerwone jednocześnie
   
---
#### 4. Logiczna kolejność wykonywania zapytania

Kolejność wykonywania instrukcji SELECT

2 - `SELECT ProductID, Name, Color AS Kolor, Size`	

1 - `FROM Production.Product`	

3 - `ORDER BY Kolor`	

odwołanie się do aliastu kolumny w ORDER BY - jest OK

`SELECT ProductID, Name, Color AS Kolor, Size` 

`FROM Production.Product`

`ORDER BY Kolor`

Kolejność wykonywania instrukcji SELECT

3 - `SELECT ProductID, Name, Color AS Kolor, Size`

1 - `FROM Production.Product`	

2 - `WHERE Kolor = 'Red'`

odwołanie się do aliasu kolumny w WHERE nie zadziała

~`SELECT ProductID, Name, Color AS Kolor, Size`~

~`FROM Production.Product`~

~`WHERE Kolor = 'Red'`~

---

#### 5. Funkcje 

**1. SKALARNE**

- `SELECT GETDATE()` - zwraca bieżącą datę i czas. Funkcja ta nie przyjmuje argumentów

- `SELECT GETDATE() AS CurrentDateTime` - aby w nazwie kolumny uzyskać CurrentDateTime

- `SELECT UPPER('Bardzo ładny rower')` - przyjmuje argument tekstowy, operuje na tekście - zamienia wszystkie litery w tekście podanym w nawiasie na wielkie

- `SELECT LOWER('Bardzo ładny rower')` - zamienia wszystkie litery małe

(F1 (kliknąć na nazwę funkcji i F1) - aby doczytać o tej funkcji)

*godziny/ miesiace/ lata.... , OD KIEDY, DO KIEDY*

- `SELECT DATEDIFF(HOUR, '20190801 12:15', '20190801 15:15')` - oblicza różnicę między dwoma datami korzystając ze wskazanej jednostki czasu - tu data poczatkowa i końcowa, zwraca różnicę w godzinach

- `SELECT DATEDIFF(MONTH, '20190801', '20201201')`- zwraca różnicę w miesiącach

- `SELECT DATEDIFF(YEAR, '20190801', '20201201')` - zwraca różnicę w latach

*zagnieżdżenie funkcji GETDATE() w DATEDIFF():*

- `SELECT DATEDIFF(YEAR, GETDATE(), '20401201')` - zwraca różnicę w latach między datą bieżącą a podaną

- `SELECT DATEDIFF(DAY, GETDATE(), '20401201')` - zwraca różnicę w dniach między datą bieżącą a podaną

- `SELECT DATEDIFF(HOUR, GETDATE(), '20401201')`- zwraca różnicę w godzinach między datą bieżącą a podaną



*nazwy produktów wielkimi literami*

- `SELECT ProductID, UPPER(Name) AS Name, Color AS Kolor, Size 
FROM Production.Product` - używamy funkcji w ramach zapytań. 
UPPER(Name) AS Name = wyświetli nam w kolumnie Name wszytskie wyniki (nazwy produktów) WIELKIMI literami


*ile dni upłynęło od początku sprzedaży*

- `SELECT ProductID, Name, Color AS Kolor, Size, DATEDIFF(DAY, SellStartDate, GETDATE()) 
FROM Production.Product` - wylicza ile dni upłyneło pomiędzy datą w kolumnie SellStrtDate dla danego produktu a datą bieżącą



**2. FUNKCJE AGREGUJĄCE - pozwalają na wykonywanie obliczeń na wielu wierszach**

- `SELECT COUNT(*) AS FnCount FROM Production.Product` - zlicza wiersze, wszystkie wiersze i zwraca jeden wynik, zaagregowany wynik - tyle ile jest wierszy w tabeli Production.Product. FnCount to nadana nazwa kolumny nad wynikiem

- `SELECT SUM(ListPrice) AS FnSum FROM Production.Product` - sumowanie cen (ListPrice) wszytskich produktów w tabeli Production.Product

- `SELECT MIN(ListPrice) AS FnMIN FROM Production.Product` - zwraca najmniejszą cenę
- `SELECT MIN(ListPrice) AS FnMIN FROM Production.Product WHERE Color='Black'` - zwraca najniższą cenę dla produktów w kolorze czarnym

- `SELECT DATEDIFF (day,`
`(SELECT MIN(OrderDate) FROM Sale.SalesOrderHeader),`
`(SELECT MAX(OrderDate) FROM Sale.SalesOrderHeader))` - zwraca różnicę między najwcześniejsza datą w jakiej zostało złożone zamówienie a najpóźniejszą (najbardziej aktualną) datą złożenia zamówienia w tabeli Sale.SalesOrderHeader

---

#### 6. Grupowanie danych

*liczba produktów poszczególnych kolorów*

`SELECT Color, COUNT(*) AS Cnt` 

`FROM Production.Product`

`GROUP BY Color` - pokazuje tabelkę z wyliczoną ilością produktów danego koloru

*! nie możemy wyświetlać kolumn, po których nie pogrupowaliśmy* 

`SELECT Color, ~Size~, COUNT(*) AS Cnt`

`FROM Production.Product`

`GROUP BY Color` - w części SELECT nie możemy dodać kolumny, której nie ma w GROUP BY ( program najpierw grupuje a później wykonuje czynności z SELECT)


*... chyba, że po nich również pogrupujemy*

`SELECT Color, Size, COUNT(*) AS Cnt`

`FROM Production.Product`

`GROUP BY Color, Size` - pogrupowanie po dwóch kolumnach Color i Size (ile mamy czarnych w rozmiarze M, ile zielonych w rozmiarze S itd.)

---

#### 7. Łączenie tabel


- `SELECT * FROM Production.Product` - tabela 1, którą chcemy połączyć z tabelą 2

- `SELECT * FROM Production.ProductSubcategory` - tabela 2, którą chcemy połączyć z tabelą 1

*łączymy obie tabele 1 i 2:*

`SELECT * `

`FROM Production.Product` - tabela 1

`JOIN Production.ProductSubcategory` - tabela 2

`ON Production.Product.ProductSubcategoryID = Production.ProductSubcategory.ProductSubcategoryID` - ta kolumna która jest wpsólna - występuje zarówno 1 tabeli 1 jak i tabeli 2

*dalej - chcemy wybrać kolumny ale obie tabele zawierają kolumnę o nazwie 'Name'*

~`SELECT ProductID, Name, Color, Size, Name`~ - 2 razy występuje 'Name' - polecenie jest niepoprawne

`FROM Production.Product`

`JOIN Production.ProductSubcategory`

`ON Production.Product.ProductSubcategoryID = Production.ProductSubcategory.ProductSubcategoryID`

*więc musimy określić skąd to 'Name' pochodzi:*

`SELECT ProductID, Production.Product.Name, Color, Size, Production.ProductSubcategory.Name`

`FROM Production.Product`

`JOIN Production.ProductSubcategory`

`ON Production.Product.ProductSubcategoryID = Production.ProductSubcategory.ProductSubcategoryID`


*ale możemy to ułatwić, skrócić dodając aliasy całych tabel w częściach FROM i JOIN i używać ich w części SELECT i ON*

`SELECT p.ProductID, p.Name, p.Color, p.Size, ps.Name, p.ProductSubcategoryID, ps.ProductSubcategoryID`

`FROM Production.Product AS p` - od teraz Production.Product będzie występować jako p

`JOIN Production.ProductSubcategory AS ps`- od teraz Production.ProductSubcategory jako ps

`ON p.ProductSubcategoryID = ps.ProductSubcategoryID`

ZADANIA PODSUMIWUJĄCE: [plik.sql](https://drive.google.com/file/d/14rrnqmprZv3FGgG02IqRLosO4tMbxIsm/view?usp=share_link)

---

## *Subtask 3*

 
![2023-02-11_20h01_24](https://user-images.githubusercontent.com/122229411/218276428-0acd1535-e88c-42cc-9ea2-8928b24e2fbd.png)

---

![2023-02-11_20h01_43](https://user-images.githubusercontent.com/122229411/218276430-7ca5ca35-e01e-4857-98a1-7a35643f8adb.png)

 --- 
 
![2023-02-11_20h01_56](https://user-images.githubusercontent.com/122229411/218276434-1eb89693-1ce7-44c8-a206-573f981280fc.png)

---

![2023-02-11_20h02_19](https://user-images.githubusercontent.com/122229411/218276436-5d3adc49-8499-47ba-906b-9f05d178228a.png)

---

![2023-02-13_10h53_50](https://user-images.githubusercontent.com/122229411/218427207-2d81f6f5-44db-488a-b2f4-48c9a3f96187.png)

---

![2023-02-11_20h02_44](https://user-images.githubusercontent.com/122229411/218276444-a22aa04a-2003-4d0d-9b70-704805b35839.png)

---

![2023-02-13_10h55_18](https://user-images.githubusercontent.com/122229411/218427497-ba8ab7b5-a1d6-463f-a831-45fede7e58f2.png)

---

![2023-02-13_10h55_48](https://user-images.githubusercontent.com/122229411/218427509-03ae7f94-619f-4f82-b4ff-b4be85a3ccfb.png)

---

![2023-02-13_10h56_24](https://user-images.githubusercontent.com/122229411/218427520-b533d660-0fd4-465d-9728-e3376129e5f0.png)

---

![2023-02-11_20h03_15](https://user-images.githubusercontent.com/122229411/218276458-61f87330-ba84-4c40-a3ab-2f73082678c8.png)

