# Task 1


## *Subtask 1*
**10 punktów** :tada:👩🏼‍🎓


## *Subtask 3*
<p align="center">
Cześć!
</p>

<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;Nazywam się Wika 😁. Bardzo się cieszę, że mogę brać udział w tym projekcie, ponieważ chcę pójść zupełnie nową ścieżką 👩‍🚀🚀, wyjść poza to, co znam i w czym czuję się pewnie i bezpiecznie. Zupełnie nie mam doświadczenia w tej dziedzinie, dlatego czuję się trochę zagubiona 😱, ale z drugiej strony też bardzo pozytywnie nakręcona🥳. Mam nadzieję, że poznawanie nieznanego da mi dużo frajdy, satysfakcji i to fantastyczne uczucie, które się pojawia gdy się coś nowego odkrywa🕵️‍♀️. Bardzo chciałabym się jak najwięcej nauczyć, przygotować się jak najlepiej oraz zrobić wszystkie zadania. W DARE IT macie w sobie super energię i entuzjazm, który naprawdę zaraża🤧 i daje kopa do działania i bardzo sie cieszę że mogę się od Was uczyć.


PS. Czuję się trochę jak ten Pan na zdjęciu poniżej &darr; - Nie wie czy mu się uda ale przecież MUSI spróbować 🐱‍🐉.
</p>

![](https://i.pinimg.com/originals/47/43/a9/4743a96340c0dc4d46938e6df8f19f65.jpg)

## *Subtask 4*

### Testowana aplikacja

**Platforma skautingowa Futbol kolektyw**


<p align="justify">
Aplikacja służy do zapisywania i zarządzania danymi o wybranych piłkarzach oraz o meczach, w jakich brali udział. Służy do tworzenia szczegółowych oberwacji meczowych  - wprowadzania statystyk meczu z opcją notowania również w trakcie jego trwania. Daje możliwość tworzenia raportów dotyczących danego, obserwowanego zawodnika. </p>

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
Aplikacja ma bardzo prostą i mało atrakcyjną szatę graficzną. Elementy na stronie głównej, która jest wizytówką aplikacji są niedopracowane - nieprawidłowe umiejscowienie linków (helpdesk w panelu głównym i główna funkcja strony czyli dodanie gracza w oknie linki pomocnicze) , literówki (aktywnosć), brak wyrównania tekstu (linki w oknie aktywność). 
Dodanie gracza, (mimo że opcja znajduje sie w linkach pomocniczych) oraz dodanie meczu dla gracza jest proste, dość intuicyjne. Bardzo mało intuicyjnym elemetem, który może sprawiać problemy jest obsługa opcji graficznego przedstawienia/wprowadzania danych statystycznych z meczu. Brakuje instrukcji, opisu przycisków, możliwości edycji już dodanej akcji. Przechodzi się do tej opcji poprzez małą ikonę umieszczoną na końcu tabeli meczów. Również tworzenie raportu może stanowić problem, ponieważ klikając opcję dodaj raport użytkownik jest przekierowywany do tabeli meczów, gdzie musi odnaleźć małą ikonkę odpowiedzialną za tę funkcję. </p>



### Znalezione błędy

Testowanie przeprowadziłam na komputerze z systemem Windows w przeglądarce Edge oraz na telefonie z systemem Android w przeglądarce Google Chrome.
Zalogowałam się do aplikacji jako użytkownik user01@getnada.com



####***1. Strona główna***

- przy wchodzeniu na stronę, jeszcze przed zalogowaniem w dev toolsach pojawia się komunikat 404- request URL: https://scouts-test.kolektyw.pl/pl/favicon.ico 
- sprawdziłam logowanie oprócz przeglądarki edge i chrome również na przeglądarkach firefox i brave – na wszystkich się powiodło
– na górze strony – literówka -'ilość meczy' zamiast 'ilość meczów'
- po prawej w okienku aktywność –literówka- aktywnosć (s) zamiast aktywność (ś)
- w ‘Scouts panel’ powinna być opcja DODAJ GRACZA, a w ‘linkach pomocniczych’- DEV TEAM CONTACT z adnotacją w języku polskim że chodzi o kontakt/pomoc/helpdesk
- link DEV TEAM CONTACT odsyła do strony logowania na Slack’u
- 'scauts panel' - jest w języku angielskim a cała reszta strony jest przetłumaczona na język polski
- na telefonie z systemem android na stronie głównej pojawia się dodatkowa rubryka „niezapisany mecz” (oraz dane, którego meczu dotyczy) a pod nim link WRÓĆ DO RAPORTU, który po kliknięciu nie otwiera się. Na komputerze ta rubryka się nie pojawia.
- brak linku do polityki prywatności
- brak informacji o plikach cookies
- dane w oknie 'Aktywność' rozjeżdżają się (zdjecie poniżej), nie są wyrównane do lewej jak nagłówki

![image](https://user-images.githubusercontent.com/122229411/212754456-276183fb-53fd-4d4e-b33a-01bfd85fac29.png)


####***2. Dodaj gracza***


- przy polach formularza pojawiają się gwiazdki, * do których nie ma odniesienia – na dole strony powinno być odniesienie że są to pozycje obowiązkowe do wypełnienia w formularzu
- waga – brak jednostki miary w nawiasie (kg) 
- wszystkie informacje są w języku polskim natomiast na samym końcu jest SUBMIT i CLEAR
- w wersji po angielsku – AGE zamiast DATE OF BIRTH
- literówka – ‘pozycja alternatywa’ zamiast  alternatywna
- można ustawić datę urodzenia z przyszłości, dowolną wagę i wzrost bez ograniczeń, przedziałów
- telefon - można wpisać zbyt dużą ilość znaków 
- niewiele miejsca na wpisanie osiągnięć
- przed polami ‘łączy nas piłka’ ‘90min’ ‘profil facebook’ brak nagłówka –  np. profile w portalach
- dobrym rozwiązeniem byłaby lista wyboru opcji do ‘główna pozycja’ , ‘pozycja alternatywna’, ‘poziom rozgrywek’, szczególnie ważna w przypadku pozycji zawodnika - bramkarz ma inne opcje do wyboru w statystykach meczy niż np napastnik i gdy wpisze się pozycję z literówką nie można wprowadzić prawidłowo danych
- użytkownicy mogą zmieniać dane wpisane przez innego użytkownika
- przycisk clear usuwa tylko dane wpisane jako nowe, nie ma funkcji wyczyszczenia wszystkich danych po kliknięciu a jedynie tych które nie zostały zapisane
- pole województwo nie jest oznaczone gwiazdką jako obowiązkowe jednak w momencie, gdy chcemy utworzyć raport meczu pojawia się komunikat o konieczności uzupełnienia tego pola


####***3. Sekcja - Gracze***


- po otwarciu sekcji gracze pojawia się komuniakt:
        „Params `start` and `limit` are deprecated. Use `_start` and `_limit`”
- wszystkie informacje są w języku polskim, natomiast przy ikonkach w prawym górnym rogu wyświetlają się napisy po angielsku ‘download’ , ‘print’, ‘view columns’ , ‘filter rate’
- tak samo po kliknięciu w ‘view columns’ mamy ‘show columns’ i  w ‘filter rate’ mamy ‘filters’ i ‘rate’ i ‘age’a reszta po polsku

- po klinięciu w ikonę ‘download CSV’ pobieramy plik, w którym:
* wiek nie jest wyliczony lecz przedstawiany jako data urodzenia
* w kolumnach recenzji, meczów i raportów pojawia się : ‘[object]’ zamiast danych liczbowych
* pobrany plik dotyczy tylko wyświetlanych w oknie wyników(max 10 pozycji) , nie ma możliwości pobrania wszystkich danych jednocześnie

- nie można przefiltrować pod kątem ilości raportów, meczów, recenzji
- po wybraniu drukowania – raport drukuje się bez marginesów ale może to celowe. Tabela jest odwrócona – inny układ tabeli niż na stronie i nie możliwości zmiany tego układu.

### ***Dodawanie meczów dla gracza***


- '*' bez odnośnika z wyjaśnieniem, że chodzi o pola obowiązkowe
- jest możliwość ustawienia daty meczu w przyszłości
- czas gry - brak jednostki czasu w nawiasie (min) oraz brak ograniczeń, przedziału -można wpisać dowolną wartość
- numer – trzeba dopisać, że chodzi o numer na koszulce
- webmatch – powinno być : link do meczu
- general – pozycja w języku angielskim gdy pozostałe są w języku polskim. Czy są to uwagi ogólne? Nie wiadomo do czego się odnosi ta rubryka.
- w edycji meczu dla gracza na dole mamy listę zdarzeń – w rubryce meta dane pojawiają się komunikaty takie jak np. meta._id (zdjęcie poniżej) 
![image](https://user-images.githubusercontent.com/122229411/212755904-43fdce05-e532-45a8-a570-3b9f2ae3d2e4.png)

- przycisk 'clear' usuwa tylko dane wpisane jako nowe, nie ma funkcji wyczyszczenia wszystkich danych po kliknięciu a jedynie tych które nie zostały zapisane

- lista zdarzeń powinna być osobno lub np jako uzupełnienie raportu- jest na stronie pod edycją meczu. Jej umiejscowienie nie jest logiczne.
- na liście zdarzeń nie ma podziału na połówki meczu i np. jeśli akcja odbędzie się w 5 sekundzie drugiej polowy jest po prostu oznaczana jako 5 sekunda


#### ***funkcja  ROZPOCZNIJ MECZ pod ikonką piłki nożnej w zakładce mecze*** 


- brak instrukcji, opisu co to jest (statystyka meczu), jak działa i w jakim celu jest umieszczone (raportowanie danych statystycznych meczu)
- mało intuicyjne
- przyciski nie posiadają opisów
- przycisk z obrazkiem kosza nie usuwa wcześniej zapisanych akcji, jedynie nowe
- jest możliwość wyboru ujemnych wartości oraz nielogicznie dużej ilości połówek meczu
- jest możliwość wpisania nierealnych wartości czasu trwania meczu – po wpisaniu bardzo wysokiej wartości pojawiają się liczby ujemne (poniżej printscreen)
![image](https://user-images.githubusercontent.com/122229411/212756455-215af449-d512-474a-829e-6366a3287626.png)


- komentarze dopisywane podczas oznaczania danej akcji na planszy nie pojawiają się potem w raporcie – pojawiają się na liście akcji
- po dodaniu danej akcji na planszy nie można do niej wrócić, zmienić jej, rozróżnić lub usunąć. Trzeba albo usunąć wszystko albo użyć opcji cofnij która jest oznaczona strzałką
- można zaznaczać nielogiczne akcje np. jednocześnie dośrodkowanie po przyjęciu i rzut rożny
- dla bramkarza można dodać akcję: podanie ręką – gdy się ją uruchomi do zaznaczenia mamy podanie lewą i prawą NOGĄ (poniżej printscreen)
![image](https://user-images.githubusercontent.com/122229411/212756584-8e155246-a263-46a4-b629-4cf33e5d0fa6.png)

- dla bramkarza  - literówka w interwencjach-→  PRZERWANIE PODANIE


#### ***Dodanie raportu dla meczu, dla danego gracza***



- po kliknięciu ‘dodaj raport’ odsyła do zakładki mecze – a tam trzeba sobie znaleźć odpowiednią ikonkę raport – dobra byłaby funkcja dodania raportu w zakładce raporty ale umożliwiająca wybór do którego meczu dany raport się odnosi
- po kliknięciu utwórz raport pojawia się okno tworzenie raportu gracza z danymi ID gracza i ID meczu, które musimy potwierdzić (poniżej prtintscreen). Czy jest to potrzebny krok? Może wystarczające byłoby przekierowanie bezpośrednio do okna tworzenia raportu. (princreen ponieżej)

![image](https://user-images.githubusercontent.com/122229411/212759422-376b12cb-8849-46c5-9a43-d1d0e16502b1.png)


- Przyciski 'Submit' i 'Clear' są w języku angielskim gdy cała strona jest w języku polskim.
- Przyscik 'clear' nie powoduje wyczyszczenia danych z formularza.
- można dodać wiele raportów do jednego meczu i nie można ich usunąć
 

### ***RAPORT MECZOWY***


- przycisk ‘save’ porusza się razem z przewijaniem raportu i może zasłaniać pola ‘dane meczu’ oraz ‘komentarz dodatkowy’ 
- przycisk ‘save’ w wersji po polsku powinien być w formie ‘zapisz’
- link do meczu nie odsyła do podanego linku (mimo że podany w edycji meczu link jest prawidłowy) – błąd 404
- wstęp – brak spacji po nawiasie
- inteligencja boiskowa -’Ustawienie na boisku//szukanie wolnej przestrzeni/ruch bez piłki’ – dwa ukośniki i brak kropki na końcu zdania i spacji przed kolejnym.
- mentalność – brak kropki po nawiasie: ‘(czerwona kartka/strata gola itp.)’ i brak znaku zapytania w ostatnim zdaniu.
- recenzja – polecenie brzmi: ‘Wybieramy 1 z poniższych punktów’, natomiast gwiazdki można zaznaczać też jako połówki punktów np. 3,5
- dane statystyczne (testowane dla pozycji napastnika):
* Gdy nie mamy danych do danego wykresu pojawiają się nagłówek a pod nim same opisy kolumn wykresu oraz komentarz ‘nie odnotowano’. Sam nagłówek wykresu i komentarz ‘nie odnotowano’ byłby bardziej czytelny w przypadku braku danych.
* nad drugim wykresem odnoszącym się do podań krótkich jest nagłówek ‘kierunek podań’. Czytelniejszy byłby ‘kierunek podań krótkich’
* nad trzecim wykresem brakuje nagłówka  np. ‘kierunek podań długich’
* nad szóstym i dziesiątym wykresem również brak nagłówków
* brak danych dotyczących dośrodkowania głową (możliwych do zaznaczenia na planszy)
* brak danych dotyczących pojedynków 1 na 1 możliwych do zaznaczania na planszy (np.2 graczy, 3 graczy, 4 lub więcej graczy, przejęcie, przerwanie)
* brak danych w raporcie odnośnie rzutów karnych i wolnych, które na planszy można zaznaczać wybierając opcję strzały, pojawiają się w liście zdarzeń pod edycją meczu
* inne nazwy odbioru na planszy i w raporcie – odbiór ‘głową’ na planszy, ‘w walce o górną piłkę’ na raporcie oraz straty ‘’holowanie piłki’ na planszy i ‘przez przetrzymywanie piłki’ na raporcie
* w wersji angielskiej mamy dwa razy fouled jako faulowany i faulował


dla bramkarza – brak wykresów dla podań ręką, interwencji, obron strzału, brak danych o piłce poza polem karnym. Nie pojawiają się raporcie również dane o faulowaniu i byciu faulowanym. Konieczne jest dostosowanie raportu dla każdej pozycji zawodnika.

-raportu nie można wydrukować 

#### ***Inne uwagi***
-Strona nie dostosowuje się do ekranu smartfona w edycji meczu, edycji raportu oraz w tabelach meczów i raportów


- pojawia się błąd 12 - Node cannot be found in the current page.


 



