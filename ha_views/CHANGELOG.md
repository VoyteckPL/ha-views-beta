## 0.4.1-beta.200

- Przełączanie widoków palcem: jeśli puszczenie palca nie dotrze do strony i karta zostanie między widokami, kolejne dotknięcie przejmuje ją z miejsca, w którym stoi (bez skoku), a bez dotknięcia strona sama kończy gest po 1,5 s (było 4 s).
- Naprawa wyścigu: animacja powrotu po poprzednim geście nie resetuje już karty w trakcie następnego gestu ani w trakcie przejścia (mogło to dawać zatrzymanie lub mrugnięcie, także na kostce).
- Pusty widok: przeglądarka nie przejmuje już poziomego gestu (wcześniej przerywała przesuwanie).
- Gest rozpoczęty na wygaszanym podglądzie poprzedniego przejścia też działa.

## 0.4.1-beta.199

- Naprawa: kolor Flow wracał do starego po ponownym otwarciu aplikacji. Stara migracja przy każdym starcie kopiowała dawne pole `fillColor` do koloru i zapisywała układ. Teraz stare pola `fillColor`/`chevronMode` są jednorazowo usuwane, a kolor jest brany z nich tylko dla bardzo starych Flow (sprzed wyboru kształtu).

## 0.4.1-beta.198

- Beta zapisuje układ we własnym pliku `/config/ha_views/rewrite_state_beta.json` (przy pierwszym starcie kopiuje obecny `rewrite_state.json`). Stabilny dodatek HA Views zapisywał ten sam plik bez sprawdzania wersji, więc otwarta strona wersji stabilnej potrafiła cofnąć zmiany zrobione w becie na wszystkich urządzeniach.

## 0.4.1-beta.197

- Synchronizacja między urządzeniami: gdy inne urządzenie zapisało układ w międzyczasie, zmiany są łączone pole po polu zamiast odrzucania zmiany z tego urządzenia (np. kolor Flow ustawiony na telefonie nie wraca już do poprzedniego).
- W trybie edycji nowsze zmiany z innego urządzenia są wczytywane na miejscu, bez przeładowania strony i bez wychodzenia z edycji.
- Serwer odrzuca zapis ze starej, zbuforowanej wersji aplikacji (bez numeru rewizji), żeby nie nadpisała nowszego układu.

## 0.4.1-beta.196

- Górny pasek jest niższy (44 px zamiast 56 px), więc widok ma więcej miejsca. Menu edycji, menu widoku i panel More Info otwierają się tuż pod nowym paskiem.
- Usunięto niebieski pasek pod aktywną zakładką widoku — aktywny widok wyróżnia biała, pogrubiona nazwa.

## 0.4.1-beta.195

- Widoki (telefon, kostka): efekty 3D kostki (perspektywa, ukrywanie tylnej ściany) są włączone przez cały czas trybu „Kostka” zamiast przełączać się w chwili podmiany widoku — przebudowa warstw graficznych w tym momencie mogła dać mignięcie.
- Nowa opcja w menu widoku: „Diagnostyka przesuwania” (zapamiętywana tylko na danym urządzeniu). Pokazuje w rogu ekranu na żywo, co strona dostaje podczas przesuwania (dotknięcie, ruch, puszczenie, przerwanie gestu, fokus, widoczność) oraz decyzję po puszczeniu — pomaga ustalić, dlaczego przesuwanie czasem się zatrzymuje.

## 0.4.1-beta.194

- Widoki (telefon): poprawka z 193 mogła kończyć gest w połowie, gdy palec zatrzymał się na chwilę podczas przesuwania (jeśli strona nie dostawała zdarzeń dotyku) — widok wracał i trzeba było przeciągać drugi raz. Teraz „palec oderwany” jest rozpoznawany tylko na podstawie prawdziwych zdarzeń dotyku; bez nich strażnik czeka 4 s bez ruchu.
- Widoki (telefon): przesunięcie rozpoczęte, zanim skończyło się poprzednie przejście, zachowuje całą swoją długość (wcześniej część ruchu przepadała i gest wychodził za krótki). Kilka szybkich przesunięć pod rząd przełącza tyle widoków, ile razy przesunięto.
- Widoki (telefon): decyzja po puszczeniu palca jest odporniejsza — drgnięcie przy odrywaniu i łuk kciuka nie cofają przejścia; anuluje je dopiero wyraźne cofnięcie palca.

## 0.4.1-beta.193

- Widoki (telefon): przesuwanie i kostka nie zatrzymują się już w połowie między ekranami.
  - Śledzenie palca nie zależy od wewnętrznej listy wskaźników, którą niektóre zdarzenia systemowe czyściły w trakcie ruchu (wtedy widok przestawał podążać za palcem).
  - Jeśli przeglądarka zgubi zakończenie gestu, strażnik (sprawdzanie co 0,3 s na podstawie liczby palców na ekranie) domyka przejście do najbliższego widoku.
  - Karty, które zostały między ekranami bez aktywnego gestu, wracają na miejsce, a nowe dotknięcie zawsze zaczyna od czystego stanu.
  - Błąd w trakcie przejścia nie zostawia już kart w połowie.

## 0.4.1-beta.192

- Widoki (telefon): przesuwanie nie zamraża się już w połowie. Aplikacja HA potrafi zgłosić „fokus okna” zaraz po dotknięciu ekranu, co kasowało śledzenie palca — teraz fokus nie przerywa gestu, a utrata dotyku lub zejście aplikacji w tło płynnie cofa przesunięcie.
- Widoki (telefon): przesuwanie nie przestaje działać na stałe. Czekanie na wczytanie/dekodowanie obrazu tła ma teraz limity czasu, więc gest nigdy nie zostaje zablokowany (wcześniej trzeba było ubić aplikację HA). Dodano też awaryjne zakończenie gestu, gdy przeglądarka zgubi zdarzenie puszczenia palca.
- Widoki: nowe ustawienie „Przełączanie palcem” w menu widoku: Wyłączone (tylko zakładki), Przesunięcie, Kostka. Kostka to obrót 3D obu widoków wokół wspólnego środka, liczony przez kartę graficzną. Ustawienie jest wspólne dla wszystkich urządzeń.

## 0.4.1-beta.191

- Widoki (telefon): menu „Zarządzaj widokiem” wysuwa się od dołu ekranu jak edytor markera — z nagłówkiem (nazwa widoku) i przyciskiem zamknięcia, z większymi przyciskami.
- Widoki (telefon): „Tło” otwiera się jako druga strona tego samego menu (ze strzałką powrotu), więc nie zasłania już przycisków menu widoków.
- Tło: wybór obrazu z listy pokazuje najpierw podgląd w pełnych proporcjach z przyciskami „Anuluj” i „Ustaw tło” (jak przy tworzeniu nowego widoku); tło zmienia się dopiero po zatwierdzeniu. Dotyczy telefonu i komputera.

## 0.4.1-beta.190

- Widoki (telefon): właściwa poprawka mignięcia dołu ekranu po przesunięciu na widok z innym tłem. Podczas przesuwania kontener widoku przycinał zawartość także w pionie, a gdy prawdziwa karta na moment (w trakcie wczytywania nowego obrazu) stawała się niższa, kontener ucinał od dołu podgląd, który zasłaniał ekran. Teraz przycinanie działa tylko w poziomie, a wysokość kontenera jest na czas przesuwania zablokowana.
- Widoki: gdy obraz nowego tła jeszcze się wczytuje, karta zachowuje dotychczasowy rozmiar zamiast chwilowo przechodzić na rozmiar zastępczy (dotyczy też przełączania zakładkami).

## 0.4.1-beta.189

- Widoki (telefon): usunięto mignięcie tuż po przesunięciu na widok z innym obrazem tła. Prawdziwy widok przez jedną klatkę miał pośrednią geometrię (dopasowanie do nowego obrazu było odkładane o klatkę), a podgląd znikał za wcześnie. Teraz obraz jest dekodowany, geometria ustawiana od razu, a podgląd zaczyna znikać dopiero, gdy prawdziwy widok jest już narysowany pod nim.
- Widoki: przy przełączaniu zakładką geometria nowego tła ustawia się od razu po jego wczytaniu (krótszy moment pośredni).

## 0.4.1-beta.188

- Widoki (telefon): usunięto mrugnięcie u dołu wjeżdżającego widoku z panoramą — podgląd ma teraz także pasek pozycji panoramy, więc ma dokładnie tę samą wysokość co prawdziwy widok.
- Widoki (telefon): szybkie przewijanie kilku widoków pod rząd — przełączenie nie czeka już na odpowiedź serwera ze stanami (są już w pamięci), podglądy kolejnych widoków przygotowują się od razu, a machnięcie wykonane w trakcie kończenia poprzedniego przejścia jest zapamiętywane i wykonywane zaraz po nim.

## 0.4.1-beta.187

- Widoki (telefon): przesuwanie między widokami działa jak w galerii telefonu. Sąsiedni widok jest przygotowywany zawczasu — obraz w docelowej rozdzielczości i geometrii (także panorama na pełną wysokość), markery i Flow dodawane po wczytaniu obrazu — więc w trakcie ruchu nic się nie dociąga.
- Decyzja po puszczeniu zależy od kierunku i prędkości palca: jeśli cofasz palec, widok wraca na miejsce; szybkie machnięcie w stronę kolejnego widoku przełącza; przy wolnym ruchu przełącza powyżej 40% szerokości. Dojazd ma tempo zależne od prędkości palca.
- W widoku z panoramą najpierw przewija się obraz, a po dojściu do jego krawędzi dalszy ruch przesuwa do sąsiedniego widoku.
- Przesuwa się cała karta widoku, a podgląd ma identyczne położenie i rozmiar jak widok po przełączeniu.

## 0.4.1-beta.186

- Widoki (telefon): przy przesuwaniu palcem widok, do którego zmierzasz, pojawia się już w trakcie ruchu i wsuwa się obok bieżącego (tło, markery z aktualnymi wartościami i Flow) — jak przewijanie stron. Po puszczeniu dojeżdża do końca i zamienia się w pełny widok; za krótki ruch cofa oba widoki na miejsce.
- Stany encji są pobierane dla wszystkich widoków, więc podgląd sąsiedniego widoku pokazuje prawdziwe wartości.

## 0.4.1-beta.185

- Widoki (telefon): przesuwanie palcem między widokami ma animację — widok podąża za palcem i lekko blednie, po puszczeniu odjeżdża w bok, a następny wjeżdża z drugiej strony. Przełącza szybkie machnięcie albo przeciągnięcie ponad 30% szerokości; krótszy ruch płynnie wraca na miejsce. Na pierwszym i ostatnim widoku przesuwanie stawia wyraźny opór. Przy ustawieniu systemowym „ogranicz ruch” animacja jest pomijana.

## 0.4.1-beta.184

- Synchronizacja między urządzeniami: otwarta aplikacja (np. w aplikacji HA na telefonie) sprawdza co 20 s i przy powrocie na ekran, czy układ zmienił się na innym urządzeniu, i wczytuje najnowszą wersję, zostając na tym samym widoku. W trybie edycji zamiast automatycznego przeładowania pojawia się przycisk „Wczytaj”.
- Ochrona przed nadpisaniem: serwer odrzuca zapis oparty na starszej wersji układu (np. z telefonu, który miał otwartą starą stronę). Takie urządzenie wczytuje wtedy aktualny układ i informuje, że jego ostatnia zmiana nie została zapisana — zmiany z drugiego urządzenia zostają.
- Przełączanie widoków nie zapisuje już całego układu na serwerze; otwarty widok jest zapamiętywany osobno na każdym urządzeniu.

## 0.4.1-beta.183

- Poprawka: marker encji, która ma też Flow, mógł „uciec” poza ekran podczas zmiany rozmiaru. Aktualizacja stanu encji przebudowywała scenę w trakcie przeciągania kółka i rozmiar liczony był z odłączonego elementu. Teraz aktualizacje stanu przebudowują tylko Flow, a zmiana rozmiaru i przeciąganie zawsze używają widocznego elementu.
- Poprawka: markery i Flow zapisane poza sceną wracają na jej krawędź przy wczytaniu, a „Pokaż w widoku” przywraca marker na scenę.

## 0.4.1-beta.182

- Flow: nowy suwak „Ostrość” w sekcji Kształt (10–100%). 100% = dotychczasowy kształt; mniejsza wartość spłaszcza i otwiera „V”, np. prostuje wąski chevron. Działa dla Chevronu, Grotu i Trójkąta, a przy Strzałce skraca grot. Rozmiar elementu, odstęp i ramka się nie zmieniają. Można go ustawić osobno dla wartości ujemnej i kopiować ze stylem.

## 0.4.1-beta.181

- Flow: nowy przycisk „Duplikuj Flow” w nagłówku edytora — tworzy niezależną kopię z tym samym stylem, lekko przesuniętą, i od razu otwiera ją do edycji. Ta sama encja może mieć dowolnie wiele Flow w różnych miejscach i z różnym stylem.

## 0.4.1-beta.180

- Flow: kształt strzałek nie zmienia się przy zmianie odstępu ani liczby — odstęp zmienia tylko odległość między strzałkami, a liczba tylko ich ilość. Ramka też zostaje taka sama.
- Flow: nowy suwak „Długość elementu” (rozmiar jednej strzałki); dotychczasowa „Długość” to teraz „Długość ramki”.
- Flow: elementy są wyśrodkowane w ramce; jeśli się nie mieszczą, są przycinane na krawędziach ramki.
- Flow: animacja przepływu zawsze wypełnia całą ramkę, niezależnie od liczby i odstępu.
- Flow: narożne kółka skalują ramkę razem ze strzałkami i odstępem (poziomo) oraz szerokość (pionowo).
- Istniejące Flow zachowują dotychczasowy wygląd po aktualizacji.

## 0.4.1-beta.179

- Flow: na komputerze edytor Flow otwiera się obok klikniętego Flow, tak jak edytor markerów, i przesuwa się razem z nim po przeciągnięciu (chyba że okno edytora zostało ręcznie przestawione).
- Flow: sekcje edytora są domyślnie zwinięte; rozwinięta sekcja zostaje otwarta tylko przy zmianach w tym samym Flow.

## 0.4.1-beta.178

- Widoki: kolejność zakładek można zmieniać przeciąganiem (mysz: przeciągnij; telefon: przytrzymaj i przeciągnij). Strzałki w menu zostają.
- Widoki: widok startowy ma ikonę domku na zakładce.
- Widoki: „Usuń widok” jest na dole menu, oddzielony od reszty; potwierdzenie podaje liczbę markerów i Flow, a po usunięciu przez kilka sekund można kliknąć „Cofnij”.
- Widoki: na telefonie (poza trybem edycji) przesunięcie palcem w lewo/prawo przełącza na sąsiedni widok. Przy przybliżonym obrazie lub panoramie przesunięcie nadal przewija obraz.
- Poprawka: kliknięcie Flow w trybie edycji zamyka menu edycji, tak jak kliknięcie markera.

## 0.4.1-beta.177

- Język: dodano ok. 150 brakujących tłumaczeń PL → EN — cały edytor Flow, opcje markerów (kolory i obrys ON/OFF, kształt ramki, pozycja ikony), okna potwierdzeń, ekran powitalny, tła, historia, wyszukiwanie encji, komunikaty błędów i etykiety ikon.
- Język: tłumaczone są też podpowiedzi (title), etykiety dostępności (aria-label) i placeholdery, również te tworzone po starcie aplikacji.
- Język: zdania z nazwą w środku (usuwanie Flow, usuwanie tła, zmiana typu markera) są tłumaczone w całości.
- Język: nazwy encji, Flow i integracji nie są tłumaczone (np. encja „Basen” nie zmieni się na „Pool”).
- Tłumaczenie działa szybciej — mapa odwrotna PL/EN jest liczona raz, a nie przy każdym tekście.

## 0.4.1-beta.176

- Flow: animacja przepływu i pulsowania jest płynna także przy częstych aktualizacjach stanu encji. Niezmieniony Flow nie jest już przebudowywany przy każdym odświeżeniu sceny — aktualizowana jest tylko jego pozycja.
- Flow: przy opcji Tempo od wartości zmiana tempa zachowuje bieżącą pozycję strumienia zamiast przeskakiwać.

## 0.4.1-beta.175

- Flow: próg aktywności działa jednakowo w obu trybach — Flow jest nieaktywny, gdy |wartość| ≤ próg. Próg 0 wyłącza więc strzałki przy 0 W (np. fotowoltaika w nocy).
- Flow: nieaktywny Flow z animacją przepływu nie pokazuje już zdublowanych strzałek wystających poza ramkę.
- Flow: ukryty Flow (Ukryj poniżej progu) poza edycją jest całkowicie niewidoczny; w trybie edycji zostaje tylko przerywana ramka bez strzałek, żeby dało się go kliknąć i edytować.
- Flow: po włączeniu trybu edycji Flow są od razu odświeżane.

## 0.4.1-beta.174

- Start aplikacji: układ, lista teł i uprawnienia są pobierane równolegle, a stany encji razem z obrazem tła, a nie jeden po drugim.
- Start aplikacji: scena pojawia się dopiero, gdy znane są układ, tło i pierwsze stany — bez mignięcia panelu wyboru tła i bez chwilowo czerwonych ikon.
- Start aplikacji: przyciski edycji są ukryte do sprawdzenia uprawnień, więc w trybie Viewer nie migają.
- Start aplikacji: arkusz ikon MDI nie blokuje już uruchomienia skryptu; język interfejsu jest zapamiętywany i ustawiany od razu.
- Zabezpieczenie: jeśli coś się zawiesi, widok i tak pokazuje się najpóźniej po 5 s. Funkcje aplikacji bez zmian.

## 0.4.1-beta.173

- Flow: Długość i Szerokość określają teraz rozmiar ramki. Liczba elementów i odstęp rozkładają strzałki wewnątrz ramki i nie zmieniają jej rozmiaru.
- Flow: narożne kółka zmieniają rozmiar ramki (przeciwległy róg zostaje w miejscu).
- Flow: kliknięcie Flow w trybie edycji na telefonie przybliża i centruje go tak samo jak Badge.
- Istniejące Flow dostają długość ramki równą dotychczasowej, więc wyglądają tak samo po aktualizacji.

## 0.4.1-beta.172

- Flow: naprawiono za małe strzałki — stara reguła CSS wymuszała 22×22 px, przez co Długość, Szerokość i narożne kółka zmieniały tylko ramkę. Ramka znów dokładnie obejmuje strzałki.
- Flow: przepływ nie znika w połowie animacji — ciąg strzałek zawsze wypełnia całą ramkę.
- Flow: naprawiono pulsowanie — pulsuje cała grupa (jasność i skala); wcześniej skalowanie blokowała stara reguła CSS.

## 0.4.1-beta.171

- Flow: Długość i Szerokość są liczone względem kierunku strzałki — po obrocie o 90° nie zamieniają się miejscami.
- Flow: narożne kółka skalują jak w markerach — przeciwległy róg zostaje w miejscu, także przy obróconym Flow.
- Flow: większe limity — długość/szerokość do 600 px, odstęp do 300 px, grubość do 120 px, do 12 elementów, tempo do 6×.
- Flow: próg aktywności działa także przy stałym kierunku (np. wyłączenie strzałek fotowoltaiki w nocy); w trybie edycji ukryty Flow jest widoczny jako przygaszony, żeby dało się go kliknąć.
- Flow: nowe rodzaje: Chevron, Strzałka, Grot, Trójkąt, Segment. Usunięto stare warianty i osobny wybór Chevrony/Segmenty.
- Flow: usunięto niejasne Wypełnienie/Kontur — kształt jest zawsze wypełniony, a Obrys (grubość + kolor) jest widoczny na zewnątrz kształtu.
- Flow: w trybie + / − przełącznik Wartość + / Wartość − pokazuje podgląd każdej strony; opcja Osobny styl dla − pozwala ustawić dla minusa własny kształt, rozmiar, obrys, poświatę, krycie i animację.
- Flow: skaluje się razem ze sceną, tak jak markery.
- Flow: w edytorze widać aktualną wartość encji.

## 0.4.1-beta.170

- Flow: edytor wygląda i działa jak edytor markerów (ten sam nagłówek, sekcje, suwaki, palety kolorów, przeciąganie okna).
- Flow: w nagłówku przyciski Ustaw domyślny, Kopiuj styl, Wklej styl, Usuń Flow i Zamknij. Kopiuj/wklej działa tylko Flow → Flow.
- Flow: każdy suwak ma przycisk przywracania wartości domyślnej.
- Flow: nowy, logiczny podział sekcji: Encja i kierunek, Kształt, Rozmiar i pozycja, Kolory i wygląd, Animacja. Po zmianie opcji otwarta sekcja zostaje otwarta.
- Flow: uproszczone kolory — kolor główny (lub kolor dla + / −) barwi całe Flow; osobny kontur i osobna poświata są opcjonalne.
- Flow: naprawiono tempo animacji i odstęp — zmienne CSS nie były wcześniej w ogóle ustawiane.
- Flow: animacja nie restartuje się przy każdej zmianie stanu encji, strumień jest płynny i bez przeskoku na łączeniu.
- Flow: poświata nie jest ucinana podczas animacji przepływu.
- Flow: Escape i kliknięcie w tło zamykają edytor Flow; usuwanie Flow wymaga potwierdzenia.

## 0.4.1-beta.169

- Flow: naprawiono błąd `$(...).forEach` w edytorze Flow, przez który nie działały przyciski Kopiuj styl, Wklej styl i Usuń Flow.
- Flow: palety kolorów nie dublują już obsługi kliknięć po ponownym otwarciu edytora (paleta otwiera się za każdym razem, RGB pyta tylko raz).

## 0.4.1-beta.168

- Flow: odwrócono kierunek przesuwającego się strumienia, aby był zgodny z kierunkiem strzałek.
- Flow: suwak zmieniono na tempo animacji — większa wartość oznacza szybszy ruch.

## 0.4.1-beta.167

- Flow: animację „Przepływ” zmieniono na zapętlony przesuwający się strumień całej grupy chevronów.

## 0.4.1-beta.166

- Flow: dodano niezależne kopiowanie i wklejanie stylu wyłącznie między Flow.
- Flow: paleta kolorów działa wielokrotnie bez zamykania i ponownego otwierania edytora.
- Flow: pełne chevrony obsługują widoczny obrys oraz jego grubość.

## 0.4.1-beta.165

- Flow: usunięto szerokość pola — ramka zawsze ma dokładnie rozmiar zawartości.
- Flow: narożne uchwyty niezależnie zmieniają szerokość i wysokość chevronów.
- Flow: edytor podzielono na sekcje oraz dodano palety dla wypełnienia, konturu i poświaty.
- Flow: dodano warianty strzałek: klasyczny, szeroki, strzałka i strzałka z belką.

## 0.4.1-beta.164

- Flow: dodano automatyczne sterowanie kierunkiem na podstawie wartości dodatniej/ujemnej, z osobnymi kierunkami i kolorami dla + oraz −.
- Flow: dodano próg martwy i opcję ukrywania w tym progu.
- Flow: dodano animacje pulsowania i przepływu, regulację prędkości oraz opcjonalną prędkość zależną od wartości.

## 0.4.1-beta.163

- Naprawiono kształt chevronów Flow: są renderowane jako wektory SVG zamiast obróconych ramek CSS.
- Chevron zachowuje prawidłowy kształt przy każdej niezależnej szerokości i wysokości.

## 0.4.1-beta.162

- Flow: dodano niezależną szerokość i wysokość chevrona — można rozciągać dowolny kształt.
- Flow: dodano wypełnienie pełne albo kontur, grubość konturu, poświatę i przezroczystość.
- Narożne uchwyty skalują teraz równomiernie aktualny kształt.

## 0.4.1-beta.161

- Flow: ramka zaznaczenia śledzi element podczas przeciągania.
- Flow: cztery narożne uchwyty zmieniają jednolicie rozmiar chevronów.

## 0.4.1-beta.160

- Flow: usunięto zdublowaną ramkę zaznaczenia; pozostała jedna ramka z uchwytami.
- Flow: ramka obejmuje całą zawartość, także większe chevrony i segmenty.
- Flow: dodano regulację liczby elementów (1–8).
- Flow: obrót nazwano korektą obrotu i dodano przycisk Reset.

## 0.4.1-beta.159

- Naprawiono błąd startu aplikacji po dodaniu uchwytów Flow.
- Poprawiono podpinanie uchwytów standardowych markerów i Flow do list elementów DOM.

## 0.4.1-beta.158

- Flow: chevrony nie deformują się przy większym rozmiarze; pole automatycznie zachowuje potrzebną szerokość.
- Flow: dodano niebieskie uchwyty do zmiany szerokości pola bezpośrednio na scenie.

## 0.4.1-beta.157

- Flow: dodano wybór kształtu: pojedynczy, potrójny albo segmenty.
- Flow: dodano ręczny kierunek: prawo, lewo, góra albo dół; obrót pozostaje niezależną korektą.

## 0.4.1-beta.156

- Naprawiono błąd, który zatrzymywał dodawanie Flow testowego do widoku.
- Renderowanie chevronów nie zależy już od pojedynczego selektora DOM.

## 0.4.1-beta.155

- Naprawiono wizualną aktualizację rozmiaru, odstępu i koloru chevronów Flow. Wartości są teraz nakładane bezpośrednio na właściwy Flow.

## 0.4.1-beta.154

- Naprawiono podpięcie kontrolek w edytorze Flow. Zmiany rozmiaru, odstępu, obrotu, szerokości, koloru i blokady są teraz zapisywane oraz od razu widoczne.

## 0.4.1-beta.153

- Naprawiono obsługę kontrolek edytora Flow: kolor, rozmiar, odstęp, obrót, szerokość i blokada działają od razu na właściwym Flow.
- Ujednolicono wygląd panelu Flow z głównym edytorem markerów.

## 0.4.1-beta.152

- Flow ma własny, niezależny edytor otwierany kliknięciem w trybie Edytuj widok.
- Dodano regulację: koloru, rozmiaru chevronów, odstępu, obrotu, szerokości pola oraz blokadę przesuwania i usuwanie Flow.
- Ustawienia geometrii są zapisywane wyłącznie w osobnym obiekcie Flow, bez wpływu na zwykłe markery.

## 0.4.1-beta.151

- Flow testowy jest teraz widoczny na scenie jako trzy statyczne chevrony.
- Każdy Flow ma niezależnie zapisane w JSON-ie pozycję, rozmiar i obrót; w trybie Edytuj widok można go przeciągać bez wpływu na markery.
- Nadal bez logiki kierunku, wartości encji i animacji — to wyłącznie bezpieczny test geometrii oraz zapisu.

## 0.4.1-beta.150

- Etap testowy Flow: encję można dodać niezależnie jako Flow przez przycisk `↝`, także gdy ma już zwykły marker.
- Flow jest zapisywany osobno od markerów, pokazuje się na liście „Dodane do widoku” i można go bezpiecznie usunąć.
- Ten etap celowo nie rysuje jeszcze chevronów ani nie zmienia istniejących markerów.

## 0.3.0-beta.149

- Podgląd istniejącego tła zachowuje proporcje oryginalnego obrazu i pokazuje cały kadr w kompaktowym rozmiarze.

## 0.3.0-beta.148

- Wybór istniejącego tła pokazuje jego podgląd oraz przycisk potwierdzający załadowanie.
- Po załadowaniu tła obrazkowego pusty widok pokazuje ten sam ekran „Dodaj pierwszą encję”, co po wyborze tła jednokolorowego.

## 0.3.0-beta.147

- Ustabilizowano dwa panele ekranu wyboru tła: przyciski i lista istniejących obrazów mieszczą się w obrysie.
- Usunięto zbędny przycisk z ptaszkiem. Wybór istniejącego tła z listy jest stosowany od razu.

## 0.3.0-beta.146

- Ekran wyboru tła podzielono na dwa panele: Obraz (wgranie lub wybór istniejącego) oraz Kolor.
- Usunięto niebieską ikonę/kafelek z ekranu powitalnego.

## 0.3.0-beta.145

- Język przeniesiono na sam dół menu Edytuj widok.
- Na ekranie nowego/pustego widoku można wybrać istniejące tło z listy — bez ponownego wgrywania pliku.
- Uporządkowano ekran powitalny: usunięto instrukcję trzech kroków, pozostawiając prosty wybór tła (nowy obraz, istniejące tło lub kolor).

## 0.3.0-beta.144

- Uproszczono pasek narzędzi: usunięto menu Ustawienia, a Integracje i wybór języka przeniesiono do menu Edytuj widok.
- Menu Widok: strzałki kolejności są na początku, bez opisu, i zajmują pełną szerokość jednego wiersza; ujednolicono typografię z menu Edytuj widok.
- Ikona Edytuj widok nie ma już niebieskiej obwódki poza aktywnym trybem edycji.

## 0.3.0-beta.143

- Wycofano eksperymentalny marker Przepływ / Chevrony z beta.140–.142.
- Przywrócono stabilny kod interfejsu z beta.139, w tym Viewer mode dla zwykłych użytkowników.

## 0.3.0-beta.142

- Przepływ ma całkowicie niezależny edytor: zmiany typu, koloru, rozmiaru i animacji nie dotyczą już głównego markera tej samej encji.
- Ukryto zakładki Badge/Gauge/Ikona/Podkowa podczas edycji Przepływu; domyślne chevrony są rysowane bezpośrednio na markerze.
- Dodano przycisk `↝` przy każdym wpisie „Dodane do widoku”, aby utworzyć kolejny Przepływ z tej encji bez szukania jej w Integracjach.

## 0.3.0-beta.141

- Naprawiono markery Przepływ: zachowują swój typ po F5/restartcie i po kliknięciu otwierają właściwy edytor chevronów.
- Usunięcie Przepływu usuwa wyłącznie ten marker, bez naruszania głównego wskaźnika tej samej encji.
- Wyszukiwarka Integracji pokazuje teraz także przycisk dodawania Przepływu dla encji już dodanej do widoku; przepływy odświeżają się na bieżąco wraz ze stanem źródła.

## 0.3.0-beta.140

- Nowy marker **Przepływ**: animowane chevrony niezależne od Badge, Gauge, Ikony i Podkowy. Tę samą encję można użyć wielokrotnie — jako wskaźnik i jako osobne przepływy.
- Cztery style: konturowe, pełne, impuls i kapsuła; regulacja liczby, rozmiaru, odstępu, szybkości animacji, przezroczystości, linii, geometrii i obrotu.
- Sterowanie: moc ze znakiem (+/−), tylko dodatnia, tylko ujemna, dwie encje, ON/OFF albo kierunek stały; z progiem martwym oraz oddzielnymi kolorami przód / wstecz / nieaktywny.

## 0.3.0-beta.139

- Viewer mode: ukryto także ikonę edycji, edytor widoków i zębatkę wraz z ich panelami dla zwykłych użytkowników.
- Kliknięcie markera w Viewer mode nadal świadomie otwiera wyłącznie More Info; sterowanie ON/OFF pozostaje dostępne dla administratora.
- Rozpoznawanie administratora uwzględnia grupę Home Assistant `system-admin`.

## 0.3.0-beta.138

- Dodano Viewer mode dla zwykłych użytkowników Home Assistant: panel jest widoczny, ale edycja widoków, markerów i teł oraz sterowanie encjami są blokowane także po stronie serwera.
- Administratorzy zachowują pełny edytor. Gdy nie można potwierdzić uprawnień użytkownika, aplikacja bezpiecznie przechodzi do trybu tylko do odczytu.

## 0.3.0-beta.137

- Badge: stany closed/open korzystają z tekstów OFF/ON; przełączniki sekcji faktycznie zwijają zależne pola.
- Własna ikona Badge ma przełączany wariant ON/OFF jak typ Ikona.

## 0.3.0-beta.136

- Edytor Badge pokazuje wyłącznie opcje potrzebne dla aktualnie włączonych funkcji, tak jak edytor Ikony.

## 0.3.0-beta.135

- Poprawiono niestandardowe teksty ON/OFF także dla encji zwracających stan z wielkimi literami.

## 0.3.0-beta.134

- Dodano regulację gradientów tła markera: pozycję, rozproszenie i wypełnienie.
- Efekt od ściany ma wybór kierunku oraz pozycję światła wzdłuż ściany.

## 0.3.0-beta.133

- Dodano cztery warianty gradientowego światła tła markera: centralny, róg, od ściany i ambient.
- Każdy gradient korzysta z wybranego koloru i przezroczystości tła markera.

## 0.3.0-beta.132

- Dodano blokadę geometrii markera w sekcji Rozmiar: chroni rozmiar i pozycję przed przypadkową zmianą.
- Ujednolicono styl menu widoków, w tym sterowanie kolejnością.

## 0.3.0-beta.131

- Ujednolicono wygląd sterowania kolejnością widoków z menu widoków.
- Dodano wybór widoku startowego uruchamianego przy każdym otwarciu HA Views.

## 0.3.0-beta.130

- Dodano zmianę kolejności widoków strzałkami ← / → w menu widoków.
- Strzałki są nieaktywne na początku i końcu listy.

## 0.3.0-beta.129

- Poprawiono rozciąganie rogu: róg po przekątnej jest utrzymywany w dokładnie tym samym miejscu na ekranie.

## 0.3.0-beta.128

- Cofnięto deformowanie powierzchni markerów z beta.127.
- Rozciąganie rogiem zachowuje prostokątny kształt i kotwi róg przeciwny.
- Zwiększono maksymalny rozmiar markera do 2400 × 1800 px.

## 0.3.0-beta.127

- Dodano niezależne przesuwanie pojedynczego rogu powierzchni markera.
- Treść markera nie jest deformowana i pozostaje wycentrowana.

## 0.3.0-beta.126

- Recovery: cofnięto wadliwą swobodną deformację markera z beta.125.
- Przywrócono stabilne zachowanie markerów i ich treści.

## 0.3.0-beta.125

- Dodano swobodną transformację markera: każdy z czterech rogów można przesuwać niezależnie, bez ruszania trzech pozostałych.

## 0.3.0-beta.124

- Poprawiono kotwiczenie rogów podczas rozciągania: pozycja przeciwległego rogu nie jest już zaokrąglana przez siatkę.

## 0.3.0-beta.123

- Przeciąganie każdego rogu markera kotwiczy róg przeciwny i rozciąga marker w wybraną stronę.
- Przywrócono stopniowanie siatki S/M/L: 0,25% / 1% / 4%.

## 0.3.0-beta.122

- Siatka w trybie edycji jest wyraźniejsza i mniej gęsta.
- Zmieniono kroki S/M/L na 0,5% / 2% / 8%.

## 0.3.0-beta.121

- Rozdzielono przezroczystość wypełnienia i obrysu ikon MDI.
- Obrys ma własną przezroczystość, także osobno dla wariantów ON/OFF.

## 0.3.0-beta.120

- Dodano przycisk testowego stanu ON/OFF obok „Przywróć domyślne” w edytorze markera.
- Przycisk zmienia wyłącznie podgląd markera w trybie edycji; nie steruje encją Home Assistant.
- Po wyjściu z trybu edycji marker wraca do rzeczywistego stanu encji.

## 0.3.0-beta.119

- Dla własnej ikony MDI aktywna zależność ON/OFF pokazuje tylko pola Ikona ON i Ikona OFF.
- Ikona podstawowa jest widoczna wyłącznie przy wyłączonej zależności ON/OFF.

## 0.3.0-beta.118

- Przywrócono suwak „Zaokrąglenie” w Ramce typu Ikona.
- Suwak jest dostępny dla kształtu „Zaokrąglony”; dla Koła / owalu jest ukryty.

## 0.3.0-beta.117

- Checkbox w typie Ikona odświeża teraz tylko aktualnie otwartą zakładkę zamiast całego popupu.
- Usunięto podwójne zdarzenie input/change dla checkboxów i list wyboru.

## 0.3.0-beta.116

- Edytor zapamiętuje aktywną zakładkę przy jej ręcznym otwarciu.
- Kliknięcia checkboxów i list wyboru są odseparowane od obsługi rozwijania sekcji popupu.

## 0.3.0-beta.115

- Naprawiono zachowanie otwartej sekcji po zmianie checkboxa niezależnie od języka interfejsu.
- Edytor zapamiętuje teraz indeks zakładki zamiast jej przetłumaczonej nazwy.

## 0.3.0-beta.114

- Zachowano otwartą sekcję edytora już podczas przebudowy popupu po zmianie checkboxa.
- Przełączniki w Ikonie, Tle i Ramce nie zwijają aktualnie edytowanej zakładki.

## 0.3.0-beta.113

- Naprawiono zachowanie rozwiniętej sekcji popupu po zmianie checkboxa.
- Zakładka Ikona, Tło lub Ramka pozostaje otwarta podczas zmiany jej opcji.

## 0.3.0-beta.112

- Uporządkowano popup tylko dla typu Ikona: sekcje Encja, Rozmiar, Ikona, Tło i Ramka pokazują wyłącznie potrzebne ustawienia.
- Wyłączone przełączniki Pokaż, Wypełnienie i Obrys ukrywają zależne pola.
- Logo integracji nie pokazuje ustawień kolorów, obrysu ani wariantów ON/OFF.
- Własna ikona MDI ma niezależny przełącznik wariantu ON/OFF; przy wyłączeniu widoczna jest tylko ikona podstawowa.
- Ujednolicono nazwy opcji zależnych ON/OFF oraz dodano niezależną zależność przezroczystości ikony.

## 0.3.0-beta.111

- Dopasowano promień zewnętrznej ramki do zaokrąglenia tła.
- Usunięto puste przestrzenie między ramką a tłem przy zaokrąglonych markerach.

## 0.3.0-beta.110

- Zastąpiono render ramki niezależną warstwą wokół markera.
- Ramka jest widoczna na zewnątrz tła i nie wpływa na rozmiar ani zawartość markera.

## 0.3.0-beta.109

- Naprawiono render zewnętrznej ramki markerów — ramka jest ponownie widoczna dla wszystkich typów.

## 0.3.0-beta.108

- Ramka markera jest teraz rysowana na zewnątrz tła dla wszystkich typów.
- Ramka nie zabiera już miejsca wewnątrz markera ani nie wpływa na pozycję jego zawartości.

## 0.3.0-beta.107

- Dodano niezależne ustawienia ON/OFF dla tła: kolor i przezroczystość.
- Dodano niezależne ustawienia ON/OFF dla ramki: kolor, przezroczystość i grubość.
- Ikony MDI mają przełączaną zależność ON/OFF dla koloru i przezroczystości; obrys ma osobne kolory oraz grubości ON/OFF.

## 0.3.0-beta.106

- W Ramce dodano wybór kształtu: prostokąt, zaokrąglony lub koło / owal.
- Ikony MDI mają niezależne wypełnienie i obrys: oba można włączać, a obrys ma własny kolor oraz grubość 1–8 px.
- Logo integracji pozostaje obrazem bez nakładanego obrysu.

## 0.3.0-beta.105

- Dodano mały przycisk resetu przy każdym suwaku w edytorze markera.
- Reset przywraca wyłącznie daną wartość do domyślnej dla typu markera, bez potwierdzenia i bez zmiany pozostałych ustawień.

## 0.3.0-beta.104

- Wyśrodkowano domyślną ikonę w Badge i typie Ikona, także dla istniejących markerów z poprzednim domyślnym przesunięciem.
- W sekcji Ikona dodano osobny suwak „Lewo / prawo”; dotychczasowy suwak opisano jako „Góra / dół”.

## 0.3.0-beta.103

- Powiększono widoczne uchwyty ramki markerów; mają teraz delikatną przezroczystość.

## 0.3.0-beta.102

- Zwiększono maksymalny rozmiar markerów do 1200 × 900 px.
- Niebieskie uchwyty ramki mają większy, niewidoczny obszar chwytu — łatwiej je złapać przy większym oddaleniu.

## 0.3.0-beta.101

- Zwiększono maksymalną wartość suwaka „Skala elementów” z 2,5× do 5× dla wszystkich typów markerów.

## 0.3.0-beta.100

- Dodano potwierdzenie przed zmianą typu markera; zmiana nadal przywraca domyślny wygląd wybranego typu.

## 0.3.0-beta.99

- Usubtelniono ramkę zaznaczenia i niebieskie uchwyty markerów w trybie edycji.

## 0.3.0-beta.98

- Zwiększono limit przeciągania ramki niebieskimi uchwytami do 900 × 600 px dla wszystkich typów markerów.
- Uchwyt i suwaki „Rozmiaru” mają teraz ten sam maksymalny zakres.

## 0.3.0-beta.97

- Zwiększono maksymalny rozmiar ramki do 900 × 600 px dla wszystkich typów markerów.

## 0.3.0-beta.96

- Zwiększono maksymalny rozmiar ramki Badge do 900 × 600 px.
- Zakres pozostałych typów markerów pozostaje bez zmian.

## 0.3.0-beta.95

- Powiększenie domyślnych markerów przeniesiono do bazowego stylu typu markera.
- Suwak „Skala elementów” znów startuje neutralnie od 1× dla Badge, Gauge, Ikony i Podkowy, bez zmiany aktualnego wyglądu.

## 0.3.0-beta.94

- Naprawiono synchronizację toggle ON/OFF z ikoną markera.
- Po przełączeniu aplikacja potwierdza docelowy stan z Home Assistant i ignoruje spóźnione, stare zdarzenia.

## 0.3.0-beta.93

- Domyślne rozmiary wszystkich typów markerów zwiększono o kolejne 30%.
- Wyszukiwarka Integracji pobiera teraz encje jednym zbiorczym żądaniem zamiast osobno dla każdej integracji — wyniki pojawiają się znacznie szybciej.

## 0.3.0-beta.92

- Domyślny rozmiar wszystkich typów markerów zwiększono o kolejne 30%.
- Dotyczy nowych markerów oraz opcji „Ustaw domyślny”.

## 0.3.0-beta.91

- Domyślny rozmiar Badge, Gauge, Ikony i Podkowy zwiększono o 30%, wraz z całą zawartością markera.
- Dotyczy nowych markerów oraz opcji „Ustaw domyślny”.

## 0.3.0-beta.90

- Zmieniono kroki siatki: S 0,25%, M 1%, L 4%.
- S pozwala precyzyjnie dosuwać markery do siebie; istniejący wybór siatki jest migrowany proporcjonalnie.

## 0.3.0-beta.89

- Markery zachowują teraz proporcjonalny rozmiar i odstępy względem tła na desktopie i telefonie.
- Usunięto mobilne wymuszenie minimalnej skali, które powodowało nachodzenie markerów.

## 0.3.0-beta.88

- Rozłączono rozmiar łuku Podkowy od rozmiaru ramki markera.
- Łuk skaluje się teraz wyłącznie suwakiem „Skala elementów”.

## 0.3.0-beta.87

- Wyśrodkowano typ markera Ikona względem środka markera.
- Poprawiono również działanie przesunięć ikony w osi X i Y.

## 0.3.0-beta.86

- Ustawiono domyślny układ Podkowy dokładnie według zatwierdzonego markera: stan 0.65× / -19 px, procent 0.8× / -8 px.

## 0.3.0-beta.85

- Poprawiono domyślny układ tekstów Podkowy: stan jest centralnie i mniejszy.
- Procent jest mniejszy, nad stanem oraz bez nakładania się na niego.

## 0.3.0-beta.84

- Naprawiono przeciąganie wszystkich suwaków markerów na telefonie.
- Gauge i Podkowa odświeżają geometrię po puszczeniu suwaka, bez przerywania gestu.

## 0.3.0-beta.83

- Przywrócono płynne przesuwanie suwaków w sekcji Nazwa.
- Marker nie jest już przebudowywany podczas przeciągania suwaka.

## 0.3.0-beta.82

- Naprawiono regulację nazwy we wszystkich typach markerów: Badge, Gauge, Ikona i Podkowa.
- Ustawienia widoczności, koloru, przezroczystości, rozmiaru i pozycji nazwy odświeżają marker od razu.
- Podkowa korzysta z tego samego pozycjonowania tekstu co Gauge.

## 0.3.0-beta.81

- Wygląd domyślnej Podkowy zachowuje bazowe przesunięcie i skalę, ale suwaki startują od 0 px i 1×.
- Dodano migrację istniejących Podków, aby zachować ich wygląd po wyzerowaniu wartości.
- Suwak Pozycja w geometrii Podkowy jest stosowany bezpośrednio do łuku.

## 0.3.0-beta.80

- Domyślna Podkowa nie pokazuje podziałki.
- Cztery ikony typu markera są wyświetlane w jednym rzędzie.

## 0.3.0-beta.79

- Dodano typy markera Ikona oraz Podkowa.
- Podkowa używa łuku U z podziałką i pełną konfiguracją Gauge.
- Wybór typu markera ma teraz cztery ikony: Badge, Gauge, Ikona i Podkowa.

## 0.3.0-beta.78

- Wyszukiwarka Integracji przeszukuje wszystkie integracje, także nierozwinięte.
- Wyniki pojawiają się w trakcie ładowania kolejnych integracji.
- Wyniki zawierają wyłącznie encje, które nie są jeszcze dodane do aktywnego widoku.

## 0.3.0-beta.77

- Naprawiono zablokowanie pinch-zoomu po powrocie do aplikacji na telefonie.
- Aktywne dotknięcia są resetowane po anulowaniu gestu, utracie focusu oraz powrocie WebView, bez resetowania aktualnego zoomu.

## 0.3.0-beta.76

- Nowy pusty widok na telefonie domyślnie używa sceny 9:16, więc kreator nie jest obcięty.
- Kreator używa tej samej palety kolorów i własnego pola RGB co edytor markera, zamiast systemowego okna wyboru koloru.

## 0.3.0-beta.75

- Dodano ikonę pobierania przy wybranym tle widoku.
- Pobieranie działa bezpośrednio przez HA Views i zapisuje oryginalny plik tła bez błędu 401 z edytora plików.

## 0.3.0-beta.74

- Tła widoków mają osobny trwały cache przeglądarki.
- Po pierwszym pobraniu pełnej rozdzielczości przełączenie z powrotem do otwartego widoku używa obrazu od razu.
- Pliki aplikacji nadal nie są cache'owane, więc kolejne bety odświeżają się poprawnie.

# Changelog

## 0.3.0-beta.73

- frontend assets under /rewrite-assets now use no-store cache headers;
- prevents Home Assistant WebView from retaining a stale app.js or app.css after an add-on update;
- keeps the existing build-token cache busting as a second safeguard.

## 0.3.0-beta.72

- added a compact search field in Integrations for entity name and entity_id;
- search begins after two characters, loads entities only when needed, and keeps the search field fixed above results;
- integration entities are fetched with a maximum of four concurrent requests.

## 0.3.0-beta.71

- fixed the post-toggle refresh error when the optional connection-status element is absent;
- toggle now refreshes the marker state without showing a false error.

## 0.3.0-beta.70

- added an optional per-marker “Tap in View” action for switch, light, fan and input_boolean entities;
- default remains More info; selecting Toggle ON/OFF makes a View-mode tap call the corresponding HA service.

## 0.3.0-beta.69

- explicitly centers the complete Gauge SVG in its marker;
- global element scaling now scales from that fixed center.

## 0.3.0-beta.68

- added a per-marker “Element scale” slider in Size (0.4×–2.5×, default 1×);
- scales marker contents only: text, icon and complete Gauge graphic including ticks;
- marker width, height, background and border remain unchanged.

## 0.3.0-beta.67

- keeps the mobile scene canvas at the same size in Edit and View modes;
- prevents background rescaling that made markers appear to move after leaving Edit mode.

## 0.3.0-beta.66

- mobile marker rendering now always uses each marker’s saved position;
- leaving Edit mode can no longer visually shift markers to collision-avoidance positions.

## 0.3.0-beta.65

- simplified the grid preset row to its grid icon and S / M / L buttons only.

## 0.3.0-beta.64

- replaced the continuous grid-size slider with three discrete S / M / L buttons;
- S = 1%, M = 5%, L = 10%; the closest button is highlighted for existing saved layouts.

## 0.3.0-beta.63

- hides the transient editor status field, including the unnecessary “Saved” message;
- CSS-only change; no JavaScript or startup logic changed.

## 0.3.0-beta.62

- recovery build: reverted beta.61 after its startup crash on mobile;
- restored the exact beta.60 frontend with a new cache token;
- no functional changes in this build.

## 0.3.0-beta.60

- recovery build: restored the exact known-working beta.57 snapshot (commit `73b108449cb54b518124a34c0ff839d399db3d75`) after beta.56, beta.58 and beta.59 startup crashes;
- no functional changes in this build.

## 0.3.0-beta.57

- emergency recovery build: restored the known-working beta.55 frontend after beta.56 prevented the app from starting;
- no new UI features in this build.


## 0.3.0-beta.55

- mobile first-view creator is compact and scrollable, keeping background-selection actions reachable on short screens.

## 0.3.0-beta.54

- restored full-width background expansion while zooming on mobile;
- hide the edit grid during that expanded-camera state, so the side area stays clean.

## 0.3.0-beta.53

- render restored-view markers immediately on startup; a slow initial state refresh can no longer leave the scene blank;
- mobile Edit marker focus is 20% closer (2.1×), with a 2.35× cap;
- clip the expanded portrait camera so the grid and canvas edge never paint in the clean area outside the background.

## 0.3.0-beta.52

- mobile Edit camera can move beyond the lower scene edge, keeping low markers above the editor;
- selecting a mobile marker now uses a closer 1.75× focus zoom (still capped, never maximum);
- explicitly reattach and render the restored view’s markers during startup.


## 0.3.0-beta.51

- fixed Gauge text anchoring: resizing no longer shifts the name, state or percentage;
- remember the last active view after refresh and render its saved markers immediately;
- on mobile Edit, selecting a marker centres it in the upper scene with a moderate zoom;
- mobile editor is limited to 50% of screen height and text controls no longer retain scene-touch gestures.


## 0.3.0-beta.50

- Gauge label, value and percentage now use fixed pixel anchors;
- resizing a Gauge no longer shifts those text layers or changes their saved offsets.


## 0.3.0-beta.49

- reduced minimum marker dimensions: Badge to 36 × 24 px and Gauge to 44 × 28 px;
- applies consistently in both size sliders and corner-handle resizing.


## 0.3.0-beta.48

- translated all confirmation dialogs, prompts and copy-style notifications in both languages;
- Width and Height sliders now show and store clean whole-pixel values, without decimal noise.


## 0.3.0-beta.47

- completed the safe explicit translation of onboarding buttons and first-entity guidance;
- keeps the beta.46 Edit-mode highlight and stable zoom behaviour.


## 0.3.0-beta.46

- safely added explicit bilingual labels for the first-view onboarding;
- translate dynamic New View prompts without the earlier unstable observer change;
- make active Edit mode visually unmistakable with a brighter pencil button.


## 0.3.0-beta.45

- preserve the current zoom when toggling between View and Edit modes;
- switching to another view still resets its camera to the default fit.


## 0.3.0-beta.44

- recovery build: restored the stable beta.42 frontend engine after beta.43 could cause browser crashes;
- keeps the menu, background, grid-slider and marker-resize features from the stable engine;
- translation/zoom refinement is temporarily deferred until it is tested safely.


## 0.3.0-beta.43

- fixed translation of inline welcome text, button labels and dynamic name dialogs;
- translate prompt title, message and confirmation labels;
- preserve the current zoom when toggling Edit mode;
- changing to another view remains the only action that resets canvas zoom.


## 0.3.0-beta.42

- marker width and height now snap to the currently selected grid size while resizing;
- disabling the grid retains fully free marker resizing.


## 0.3.0-beta.41

- completed static tooltip translation and added automatic title translation;
- menus close when clicking outside them;
- Views and Edit controls are disabled while Integrations is open;
- grid size is now a compact continuous slider with a 1–20 range;
- removed the unnecessary background arrow;
- added an animated background-upload indicator over the first-run canvas.


## 0.3.0-beta.40

- close the Views menu after creating a view;
- keep the last active view highlighted while browsing Integrations;
- opening Background now closes marker editing and More Info;
- solid-colour canvases preserve the previous image ratio;
- added a saved colour-canvas format selector: 16:9, 4:3, 1:1 and 9:16.


## 0.3.0-beta.39

- fixed the no-image background fitting path;
- a solid-colour view now keeps a full-size canvas after entering Edit mode or switching views.


## 0.3.0-beta.38

- render the chosen solid colour directly on the empty-view layer as well as the scene;
- retain the add-entity guidance above the selected canvas colour.


## 0.3.0-beta.37

- fixed a CSS rule that kept a previously loaded image visible after choosing a solid colour;
- a solid-colour view now fully hides the image layer before rendering the canvas.


## 0.3.0-beta.36

- aligned the Views menu vertically with Settings and Edit menus;
- corrected the background submenu to open to the right;
- forced solid-colour rendering above all empty-view overlays;
- solid colour now clears the selected image state and immediately enables marker workflow.


## 0.3.0-beta.35

- increased separation between the Views icon and its menu;
- aligned all primary menus with a consistent vertical gap;
- enforced left-opening background submenu;
- added selectable grid size: small, medium, large and very large;
- strengthened solid-colour canvas refresh after selection.


## 0.3.0-beta.34

- fixed menu anchoring for views, settings and edit controls;
- moved background management into the Views menu;
- background picker now uses the same palette and RGB dialog as marker styling;
- selecting a colour reliably clears the image, saves a solid background and enables adding markers;
- compact icon-only upload/delete actions with tooltips.

## 0.3.0-beta.33

- introduced compact Settings and Edit menus;
- added views management menu and initial background submenu.

## 0.3.0-beta.32

- initial navigation-menu redesign for testing.


## 0.3.0-beta.31

- beta delivery channel introduced;
- configurable views, backgrounds and marker editor;
- responsive desktop/mobile canvas, zoom and panorama navigation;
- Badge and Gauge markers with styling, icons, ticks and gradients;
- first-run guidance and solid-colour background support.

This is a testing build. The stable channel is updated only after confirmation.
