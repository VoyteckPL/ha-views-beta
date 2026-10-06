## 0.4.1-beta.423

- **Wybór stanów pracy termostatu**: w sekcji „Ogólne” termostatu jest podsekcja **Stany pracy** z listą stanów (Grzeje, Nagrzewa, Chłodzi, Osusza, Wentyluje, Odmraża, Bezczynny, Wyłączony). Zaznacz te, których używa urządzenie — tylko one pojawiają się w tekstach i animacjach „Stanu pracy” oraz w kolorach stanu pracy tarczy. Bez zmian wybór jest dobierany z trybów urządzenia (np. piec z trybem grzania: Grzeje, Nagrzewa, Bezczynny, Wyłączony).

## 0.4.1-beta.422

- **Zoom poniżej 100% w edycji na telefonie**: w trybie edycji plan można pomniejszyć gestem szczypania mniej niż do dopasowanego rozmiaru (do 40%) i przesuwać go w kadrze — np. żeby zobaczyć cały duży termostat albo rozciągnąć go na cały ekran. Duży wybrany element też jest pomniejszany tak, by zmieścił się nad panelem. Po wyjściu z edycji zoom wraca do normalnego zakresu.

## 0.4.1-beta.421

- **Linie pomocnicze także od elementów poza kadrem**: przy przesuwaniu części rozgrupowanego termostatu (i etykiety) jej własne pozostałe części zawsze dają linie pomocnicze i przyciąganie, nawet gdy są poza ekranem (np. po przybliżeniu). Inne elementy liczą się, gdy są na ekranie albo tuż obok niego (do połowy widoku dalej), a nie tylko gdy są widoczne.

## 0.4.1-beta.420

- **Sekcja w panelu → zaznaczenie i przybliżenie części**: w edycji termostatu (i etykiety) kliknięcie nazwy sekcji części (np. Tarcza, Temperatura ustawiona, Tryby) zaznacza tę część na planie (rozgrupowana: kropki w rogach, zgrupowana: niebieska przerywana ramka), a na telefonie przybliża ją na środek nad panelem. Zamknięcie sekcji wraca do całego elementu.

## 0.4.1-beta.419

- **Edytowany termostat / etykieta zawsze na środku (telefon)**: po wybraniu termostatu albo jego części (także rozgrupowanych) plan przesuwa się tak, że element stoi na środku wolnego miejsca nad panelem edycji — również przy krawędziach planu i przy najmniejszym zoomie (wcześniej duży element nisko na planie zostawał pod panelem). Podczas edycji na telefonie plan można przesunąć trochę poza jego krawędź, żeby było to możliwe.

## 0.4.1-beta.418

- **Termostat na telefonie: przyciski działają**: dotknięcie trybu (np. Wyłącz) oraz − / + na telefonie przełącza tryb / temperaturę (wcześniej puszczenie palca trafiało w warstwę gestów planu i zamiast tego otwierało się okno szczegółów). Opcjonalne potwierdzenie włączenia / wyłączenia pojawia się teraz także na telefonie i nie zamyka się samo.

## 0.4.1-beta.417

- **Potwierdzenie włączenia i wyłączenia termostatu (opcjonalne)**: w części „Tryby” jest sekcja **Potwierdzenie** z opcją „Pytaj przy włączeniu i wyłączeniu”. Gdy jest włączona, przejście na „Wyłączony” albo z „Wyłączony” na inny tryb wymaga potwierdzenia w okienku (Włącz / Wyłącz albo Anuluj). Zmiana temperatury i przełączanie między innymi trybami działa bez pytania.

## 0.4.1-beta.416

- **Animacja stanu pracy termostatu**: w części „Stan pracy” jest nowa sekcja **Animacja** — dla każdego stanu (Grzeje, Nagrzewa, Chłodzi, …, Wyłączony) osobno: Brak, Mruganie, Pulsowanie, Przygasanie albo Drganie. Np. tekst „Grzeje” może mrugać tylko wtedy, gdy grzeje.

## 0.4.1-beta.415

- **Bez podwójnych linii przy przyciąganiu**: gdy element łapie ten sam rozmiar albo równy odstęp, nie rysują się już podwójne linie miary; przyciąganie działa jak dotąd, a to, do czego się złapało, pokazuje podświetlenie elementów.

## 0.4.1-beta.414

- **Linie pomocnicze cieńsze i dokładnie na krawędzi**: linie przyciągania i podświetlenie celu mają 1 piksel ekranu (bez poświaty). Przerywane ramki etykiet, termostatów i rozgrupowanych części są cieńsze i leżą środkiem dokładnie na krawędzi elementu (co do ułamka piksela), więc pokrywają się z liniami pomocniczymi. Etykiety stoją na pełnych pikselach planu.
- **Tarcza termostatu na spodzie**: tarcza jest najniższą warstwą, więc nazwę, ikonę, stan i inne części leżące na tarczy da się złapać i przenieść.

## 0.4.1-beta.413

- **Zmiana rozmiaru nie wychodzi poza plan**: przeciąganie kółeczka w rogu (termostat, etykieta, tekst, części; także proporcjonalnie z Shiftem) zatrzymuje się na krawędzi planu.

## 0.4.1-beta.412

- **Siatka kwadratowa i wyśrodkowana**: oczka są kwadratowe (bok = 10 % / 5 % / 2,5 % szerokości planu dla L / M / S), a linie liczone są od środka planu. **Środek planu** w poziomie i pionie jest zaznaczony wyraźną linią, **ćwiartki** (1/4 i 3/4) trochę cieńszą. Przyciąganie (przesuwanie i zmiana rozmiaru) łapie się tej samej siatki.

## 0.4.1-beta.411

- **Ramki edycji bez odstępu**: przerywane obrysy etykiet, termostatów, tekstów i ich części (żółty, niebieski zaznaczenia, zielony 1:1) leżą teraz dokładnie na krawędzi elementu, z jego zaokrągleniem, a kółeczka są dokładnie w jego rogach.
- **Podświetlenie celu przyciągania ma kształt elementu**: ramka obiektu, do którego się przyciągasz, ma dokładnie jego wymiary i zaokrąglenie narożników (etykiety, części, markery), więc linie pomocnicze, obrys i podświetlenie wypadają w tych samych miejscach.

## 0.4.1-beta.410

- **Kopiowanie stylu termostatu 1:1**: kopiuj / wklej styl przenosi teraz wszystkie ustawienia wyglądu — każdą część termostatu (tarcza, temperatury, stan pracy, przyciski, tryby, stan, nazwa, ikona) z rozmiarem, kolorami, tłem, ramką, jednostką, zaokrągleniem i tekstami, kolory stanu pracy, tarczę, grupowanie i układ części. Między dwoma termostatami wklejenie jest 1:1 (także położenie części); nazwa, encja i miejsce na planie zostają. Etykiety i pomieszczenia też kopiują teraz pełny wygląd części.

## 0.4.1-beta.409

- **Szablony termostatu** (Ogólne → Szablony): dyskietka zapisuje aktualny układ i wygląd termostatu (wszystkie części, ich położenie, rozmiary, kolory, ramki, teksty, kolory stanu pracy, tarczę) jako szablon w jednym z 5 miejsc; kliknięcie numeru wczytuje szablon do zaznaczonego termostatu (nazwa, encja i miejsce na planie zostają). Kosz przełącza miejsca w tryb usuwania na jedno kliknięcie. Szablony są wspólne dla wszystkich widoków.

## 0.4.1-beta.408

- Termostat: **kolory zależą od stanu pracy** (`hvac_action`), a nie od trybu. W sekcji Tarcza podsekcja „Kolory stanu pracy”: Grzeje, Nagrzewa, Chłodzi, Osusza, Wentyluje, Odmraża, Bezczynny, Wyłączony (+ tor tarczy). Kolorem bieżącego stanu pracy rysowany jest łuk, uchwyt, „Kolor wg trybu” części i aktywny przycisk trybu. Gdy encja nie podaje `hvac_action`, stan pracy wynika z trybu (grzanie → Grzeje, chłodzenie → Chłodzi, wyłączony → Wyłączony, inne → Bezczynny).

## 0.4.1-beta.407

- **Panel podąża za klikniętą częścią**: w rozgrupowanej etykiecie, termostacie albo tekście kliknięcie części (ikony, nazwy, tarczy, temperatury…) otwiera w panelu jej sekcję, zwija pozostałe i przewija do niej. Sekcja edytowanej części jest lekko podświetlona w jej kolorze i ma kropkę przy nazwie.

## 0.4.1-beta.406

- Termostat **wyłączony pokazuje temperaturę zadaną** (jak karta termostatu w Home Assistant) zamiast „Wył.” — łuk tarczy jest wtedy w kolorze „wyłączony”, a − / + dalej zmieniają temperaturę. Tekst trybu wyłączonego pokazuje się tylko, gdy encja nie podaje żadnej temperatury zadanej. Dotyczy też starego termostatu z bety 394.

## 0.4.1-beta.405

- Termostat: **podgląd ON / OFF używa własnych tekstów trybów** — podgląd „wyłączony” pokazuje Twój tekst trybu wyłączonego (w Stanie i na środku tarczy) zamiast „Wył.”, a podgląd „włączony” tekst bieżącego (albo pierwszego niewyłączonego) trybu. Tarcza, stan pracy i przyciski trybów też pokazują podglądany tryb.

## 0.4.1-beta.404

- Termostat: „Teksty trybów” były pokazane w dwóch sekcjach (Stan i Tryby), ale to te same ustawienia — teraz są tylko w sekcji **Stan**. Teksty dalej działają też jako podpowiedzi przycisków trybów i „wyłączony” na tarczy.

## 0.4.1-beta.403

- **Mocniejsze łapanie siatki** przy zmianie rozmiaru: większy zasięg chwytu, a złapana linia trzyma kółeczko dłużej (można dalej ruszać kursorem / palcem, element zostaje na linii, dopóki nie odjedziesz wyraźnie dalej).
- **Przesuwanie elementów łapie się siatki**: przy włączonej siatce krawędzie i środki przeciąganych etykiet, termostatów, tekstów, markerów, Flow i narożniki pomieszczeń przyciągają się do linii widocznej siatki (S / M / L), z jasną linią pomocniczą.

## 0.4.1-beta.402

- **Siatka edycji wg S / M / L**: widoczna siatka zmienia się z wyborem w menu przyciągania — **L** jak dotąd (co 10 % planu), **M** dwa razy gęstsza (5 %), **S** jeszcze dwa razy gęstsza (2,5 %). Linie zaczynają się od krawędzi planu, więc siatka jest zawsze symetryczna względem środka i skaluje się z planem.
- **Zmiana rozmiaru przyciąga się do siatki**: przy włączonej siatce przeciągane kółeczka w rogach etykiet, termostatów, tekstów i ich części oraz uchwyty wskaźników / markerów łapią się linii siatki (obok przyciągania do innych elementów i 1:1).

## 0.4.1-beta.401

- Termostat:
  - **Tarcza** domyślnie trochę większa; nowe suwaki: **Kropka temperatury aktualnej** i **Uchwyt temperatury ustawionej** (rozmiar w %).
  - **Temperatura ustawiona i aktualna**: podsekcja „Format” — zaokrąglenie (automatycznie / 0 / 0,1 / 0,01) i jednostka (domyślnie °C, można zmienić albo usunąć).
  - **Temperatura aktualna** bez ikonki termometru.
  - Sekcje części termostatu (Tarcza, Temperatury, Stan pracy, Przyciski, Tryby) mają własne kolory paska, tytułu i włączonych przycisków (tło / ramka / opcje) — jak części etykiety, zamiast szarych / czarnych.

## 0.4.1-beta.400

- Termostat: **Stan pracy bez ikon** — dla wszystkich stanów (Grzeje, Bezczynny, Chłodzi, Wyłączony…) widać sam tekst.

## 0.4.1-beta.399

- **Poprawka**: „Ustaw domyślny” w termostacie zmieniał go w zwykłą etykietę (kasował też znacznik termostatu). Teraz termostat zostaje termostatem i wraca do swojego domyślnego wyglądu.

## 0.4.1-beta.398

- **Termostat — nowy domyślny układ** (po dodaniu i po „Ustaw domyślny”): na górze ikona encji w okrągłej ramce, pod nią nazwa w ramce, stan pracy, tarcza z temperaturą ustawioną i aktualną w środku, przyciski − / + po bokach dołu tarczy i tryby pod spodem.

## 0.4.1-beta.397

- **Termostat — własne teksty**: w części **Stan pracy** podsekcja „Teksty” z polem dla każdego stanu `hvac_action` (Grzeje, Nagrzewa, Chłodzi, Osusza, Wentyluje, Odmraża, Bezczynny, Wyłączony); puste pole = tekst domyślny.
- **Stan główny (tryb)**: część **Stan** termostatu pokazuje bieżący tryb (`hvac_mode`) — można ją włączyć w Grupa → Pokaż jako „Tryb (stan)”. W jej sekcji (i w sekcji Tryby) podsekcja „Teksty trybów” z własnym tekstem dla każdego trybu; tekst trybu „wyłączony” zastępuje też „Wył.” na środku tarczy, a teksty trybów są podpowiedziami przycisków trybów.

## 0.4.1-beta.396

- **Termostat: części na tarczy**: po rozgrupowaniu na tarczę można nakładać inne części (np. temperaturę ustawioną, aktualną, przyciski) — tarcza nie odpycha ich i sama też nie jest odpychana. Pozostałe części dalej się nie nakładają.
- **Termostat większy domyślnie**: większe czcionki (nazwa, temperatury, stan pracy, przyciski, tryby) i tarcza.
- **„Ustaw domyślny” w termostacie** przywraca wygląd termostatu (części, układ, kolory trybów, tarczę), a nie etykiety.
- Znak stopnia przy temperaturze ustawionej wyrównany do góry liczby także po rozgrupowaniu.

## 0.4.1-beta.395

- **Termostat na silniku etykiet (etap 1)**: kafelek „Termostat” w menu plus tworzy teraz etykietę na encji `climate` — z grupą, kółeczkami w rogach, przyciąganiem, 1:1, kopiowaniem stylu i rozgrupowaniem. Części: **Nazwa, Tarcza, Temperatura ustawiona, Temperatura aktualna, Stan pracy, Przycisk −, Przycisk +, Tryby** (oraz Ikona i Stan jak w etykiecie). Każdą można pokazać / ukryć (Grupa → Pokaż), przesunąć wewnątrz grupy albo po rozgrupowaniu postawić osobno; każda ma rozmiar, grubość czcionki, kolor (także „Kolor wg trybu”), tło i ramkę.
- Tarcza: grubość łuku, kolory trybów (grzanie / chłodzenie / auto / osuszanie / wentylator / wyłączony) i toru, zakres min / max, poświata podczas pracy. Łuk, uchwyt i stan pracy mają kolor bieżącego trybu.
- Kreator: nazwa → „Co ma być widać?” (kafelki części). W trybie przeglądania − / + i tryby sterują termostatem, dotknięcie w innym miejscu wykonuje akcję etykiety (domyślnie szczegóły encji).
- Termostaty dodane w becie 394 (stary typ) nadal działają.

## 0.4.1-beta.394

- **Nowy element „Termostat”** (osobny kafelek w menu plus, tylko encje `climate`): tarcza od `min_temp` do `max_temp` z łukiem do temperatury ustawionej w kolorze trybu (grzanie / chłodzenie / auto / osuszanie / wentylator / wyłączony), kropką temperatury aktualnej i dużą wartością docelową. Nad tarczą nazwa i stan pracy (`hvac_action`: Grzeje / Bezczynny / Chłodzi…, pulsuje podczas pracy); pod nią przyciski − / + (krok `target_temp_step`) i przyciski trybów z `hvac_modes`.
- W trybie przeglądania − / + i tryby sterują termostatem (temperatura wysyłana po chwili od ostatniego kliknięcia, tarcza zmienia się od razu); dotknięcie w innym miejscu otwiera szczegóły encji. Użytkownik bez uprawnień administratora może sterować termostatami umieszczonymi na widokach.
- Panel: **Pokaż** — nazwa, stan pracy, temperatura aktualna, − / +, tryby, zakres min / max, wilgotność, preset, wentylator (niedostępne atrybuty są wyszarzone z opisem); **Inne atrybuty** — każdy pozostały atrybut encji można dodać jako mały wiersz; **Kolory** trybów i toru; rozmiar, skala zawartości, tło, ramka.

## 0.4.1-beta.393

- **Nowy element „Tekst”** (menu plus): działa jak etykieta — ten sam wygląd, grupa, ikona / nazwa / podpis, kółeczka, przyciąganie, kopiowanie stylu — ale bez encji. Kreator: **Tekst** → **Akcja po dotknięciu** (brak / przejdź do widoku / strona Home Assistant / link, z polem celu) → co pokazać. W panelu, w sekcji Ogólne: Tekst, Podpis (druga linia, pokazuje się po wpisaniu) i akcja z celem. W trybie przeglądania dotknięcie wykonuje akcję.
- Dotychczasowe elementy „Tekst / przycisk” działają jak wcześniej.

## 0.4.1-beta.392

- **Tylko 4 kółeczka w rogach**: kropki na bokach zniknęły. Róg zmienia teraz szerokość i wysokość dowolnie (przeciwny róg zostaje w miejscu); **Shift** + róg skaluje proporcjonalnie. Zostaje przyciąganie każdego boku do linii i rozmiarów innych elementów oraz łapanie 1:1 z zieloną ramką i plakietką.
- **Rozgrupowana etykieta**: kółeczka ma tylko ostatnio kliknięta część (pozostałe mają sam lekki obrys), więc kropki nie nakładają się na siebie.
- **Ramki edycji widoczne przy dużym zoomie**: linie mają minimalną grubość i ciemną obwódkę, więc nie znikają po maksymalnym przybliżeniu.

## 0.4.1-beta.391

- **Pasek „Grupa”**: przełączniki „Grupuj” oraz pokazywania ikony / nazwy / stanu są teraz na pasku sekcji Grupa (wiersze „Grupa” i „Pokaż” zniknęły z jej środka). Od przycisków Tło i Ramka oddziela je odstęp z kreską, żeby się nie zlewały.
- **Wyraźniejsze ramki edycji**: przerywane obrysy etykiet i rozgrupowanych części mają stałą grubość na ekranie (nie robią się cienkie przy małych etykietach ani przy zoomie) i są mocniejsze.
- **Wskaźnik „równe boki”**: gruba, ciągła zielona ramka z delikatną poświatą i mała plakietka „1:1” nad elementem.

## 0.4.1-beta.390

- **Wskaźnik „równe boki” wrócił**: gdy zaznaczona ikona / część albo zgrupowana etykieta ma szerokość równą wysokości, jej obrys i kółeczka robią się zielone.
- **Przyciąganie do kwadratu** przy zmianie szerokości / wysokości kropkami na bokach — także dla zgrupowanej etykiety. Łapie się tylko, gdy w zasięgu nie ma innego obiektu (dopasowanie do sąsiadów ma pierwszeństwo).

## 0.4.1-beta.389

- **Suwak „Rozmiar” w grupie zmienia tylko zawartość**: ikona, nazwa i stan w środku zgrupowanej etykiety rosną / maleją, a ramka (tło i obramowanie) zostaje tej samej wielkości na planie. Ramka powiększa się tylko wtedy, gdy zawartość przestaje się w niej mieścić. Całą etykietę razem z ramką skalują kółeczka w rogach.

## 0.4.1-beta.388

- **Szerokość i wysokość niezależnie**: zaznaczona etykieta i rozgrupowana część mają teraz kółeczka w rogach (proporcjonalne skalowanie) **i** kropki na środkach boków (tylko szerokość albo tylko wysokość, przeciwny bok zostaje w miejscu). Zgrupowana etykieta zapamiętuje swoją szerokość / wysokość ramki (nie mniejszą niż zawartość). Boki przyciągają się do linii innych elementów i do szerokości / wysokości innej etykiety lub części.

## 0.4.1-beta.387

- **Jednakowe kółeczka dla etykiet i rozgrupowanych części**: rozgrupowana ikona / nazwa / stan (także sama ikona po automatycznym rozgrupowaniu) ma teraz kółeczka w czterech rogach zamiast kropek na środkach boków — tak jak zgrupowana etykieta. Przeciągnięcie rogu skaluje część proporcjonalnie (rozmiar, ramka, margines), przeciwny róg zostaje w miejscu, z tym samym przyciąganiem: róg do linii innych elementów i rozmiar do szerokości / wysokości innej etykiety lub części.

## 0.4.1-beta.386

- **Komputer: plan nie mruga / nie skacze**: strona z planem miała dokładnie wysokość okna, więc jeden piksel zaokrąglenia (np. przy skalowaniu ekranu 125 %) włączał pasek przewijania, karta planu przeliczała się na węższą, pasek znikał i tak w kółko — plan skakał góra–dół. Teraz na komputerze strona z planem nigdy się nie przewija (zawsze stoi na górze), a karta ma 2 px zapasu. Strona integracji przewija się jak dotąd.

## 0.4.1-beta.385

- **Poprawka grubych linii pomocniczych**: linia i podświetlenie od wskaźnika (marker / gauge / podkowa) przejmowały style samych markerów i rysowały się jako szeroki niebieski pas. Teraz są cienkie jak pozostałe.
- **„Zoom poza edycją” osobno dla każdego widoku**: ustawienie zapisuje się w widoku, a przełącznik w Opcjach pokazuje stan otwartego widoku. Wyłączenie w jednym widoku nie blokuje już zoomu w innych (także po przejściu między widokami w trybie edycji). Wcześniejsze ustawienie globalne nie jest przenoszone — w razie potrzeby wyłącz zoom ponownie w wybranym widoku.

## 0.4.1-beta.384

- **Przyciąganie przy skalowaniu etykiety kółeczkami w rogach**: przeciągany róg łapie się do krawędzi / środków innych elementów na ekranie (zgodnie z menu magnesu), a cała etykieta do szerokości lub wysokości innej etykiety — z linią pomocniczą, znacznikami wymiaru i podświetleniem wzorca. Alt wyłącza przyciąganie.
- Skalowanie rogiem nie skacze już na początku przeciągania (liczone od miejsca chwycenia kółeczka).

## 0.4.1-beta.383

- **Kółeczka na rogach etykiety**: zaznaczona (zgrupowana) etykieta ma małe kółeczka w czterech rogach. Przeciągnięcie rogu skaluje całą etykietę proporcjonalnie, a przeciwny róg zostaje w miejscu. Suwak „Rozmiar” w popupie pokazuje nową wartość.

## 0.4.1-beta.382

- **Komputer: bez paska przewijania w trybie przeglądania**: karta planu mieści się w oknie (bez dolnego marginesu, który robił stronę o kilkadziesiąt pikseli wyższą od ekranu), a dopasowanie liczy pozycję karty na stronie, nie na ekranie — przewinięta strona nie powiększa już karty. Po wyjściu z edycji strona wraca na górę, więc nazwy widoków i przyciski integracji / edycji są zawsze w całości widoczne.

## 0.4.1-beta.381

- **Przybliżony plan na komputerze wypełnia cały wolny ekran**: po zoomie (edycja i przeglądanie) plan nie jest już przycinany do swojej karty — sięga od paska u góry do dołu okna, od lewej krawędzi do panelu edycji. Dotyczy każdego formatu (tło kolorem, np. 9:16, i obrazy). Plan można przesuwać w całym tym obszarze; po powrocie do 100% wraca do karty.

## 0.4.1-beta.380

- Menu Widok → Opcje bez poziomego przewijania: długie nazwy ucinają się wielokropkiem zamiast poszerzać menu, przełącznik zoomu zawsze widoczny. Krótsze teksty: „Panel startowy HA” z opcjami „Bez zmian”, „HA Views (konto)”, „HA Views (urządzenie)”.

## 0.4.1-beta.379

- **Menu Widok w stylu popupów**: mniejsze ikony (jak w popupach elementów), Tło / Opcje jako zwykłe wiersze zamiast dużych kafli, w Opcjach nazwa po lewej i lista po prawej; całe menu (także strona Tło) jest bardziej kompaktowe.
- **Opcja „Zoom poza edycją”** (Widok → Opcje): wyłączona blokuje przybliżanie w trybie przeglądania (szczypanie, kółko myszy, podwójne stuknięcie). W trybie edycji zoom działa zawsze.

## 0.4.1-beta.378

- **Zmiana rozmiaru części kółeczkami**: przyciąganie do sąsiednich elementów (ten sam rozmiar, krawędzie, środki) ma teraz pierwszeństwo przed wyrównaniem ikony do kwadratu. Proporcja „szerokość = wysokość” łapie się tylko wtedy, gdy w zasięgu nie ma innego obiektu — linie pomocnicze i znaczniki wymiaru do sąsiedniej ikony już nie znikają.

## 0.4.1-beta.377

- Menu przyciągania: wiersz „Punkty” nazywa się teraz „Wyrównuj po” (środki, krawędzie, odstępy).

## 0.4.1-beta.376

- Menu przyciągania: ikony „Przyciągaj do” w kolejności Etykiety, Pomieszczenia, Wskaźniki, Flow. Usunięte przyciąganie do tła (krawędzie i środek tła nie dają już linii pomocniczych).

## 0.4.1-beta.375

- Panel edycji bez zaznaczenia: nowe teksty „Kliknij element, aby go edytować.” i „Nowe elementy dodasz z menu plus lub z menu integracji.”, ustawione zaraz pod nagłówkiem „Edycja”.

## 0.4.1-beta.374

- Menu przyciągania: ikony „Przyciągaj do” w jednym rzędzie (po polsku dłuższy napis spychał ostatnią ikonę niżej, a napis wyglądał na wyrównany do dołu); menu dopasowuje szerokość do zawartości.

## 0.4.1-beta.373

- Usunięty przycisk „Duplikuj” elementu (marker / wskaźnik, Flow, pomieszczenie / etykieta) z nagłówków ich popupów. Duplikowanie widoku zostaje.

## 0.4.1-beta.372

- **Wklejanie stylu nie przesuwa celu**: przy kopiowaniu stylu (np. z etykiety pomieszczenia do zwykłej etykiety) nie są już przenoszone przesunięcia etykiety i jej części względem punktu — docelowy element zostaje na swoim miejscu, zmienia się tylko wygląd (kolory, tła, ramki, rozmiary, wewnętrzny układ grupy).

## 0.4.1-beta.371

- **Dopasowanie rozmiaru do sąsiednich elementów**: przy zmianie rozmiaru rozgrupowanej części kółeczkami szerokość / wysokość przyciąga się do rozmiaru innych widocznych etykiet i ich części (np. ikony sąsiedniego pomieszczenia, nawet gdy samo pomieszczenie nie mieści się na ekranie), a nie tylko do części tej samej etykiety. Przy dopasowaniu widać znaczniki wymiaru na obu elementach i podświetlenie wzorca.

## 0.4.1-beta.370

- **Menu przyciągania w stylu popupu**: bez tytułu; każdy wiersz ma nazwę po lewej i ikony po prawej (siatka z S / M / L na górze). Usunięta cała sekcja „Więcej” (granice tła, wyrównanie do tła, obrót) — **granice tła są zawsze włączone**.
- **Linie pomocnicze przy zmianie rozmiaru części kółeczkami**: przeciągana krawędź rozgrupowanej części przyciąga się do krawędzi / środków pozostałych części i innych etykiet na ekranie (zgodnie z ustawieniami magnesu), z różowym odcinkiem i podświetleniem celu.
- Przy przesuwaniu rozgrupowanej części odległe etykiety dają odcinek od części do etykiety (wcześniej linię przez cały plan).

## 0.4.1-beta.369

- **Animacja ikony** (etykieta / pomieszczenie): w pasku sekcji „Ikona” nowy przełącznik „Animacja” (pierwszy, przed obrysem, tłem i ramką). Po włączeniu podsekcja „Animacja”: rodzaj (obrót — np. kręcący się wentylator, pulsowanie, miganie, kołysanie), czas cyklu, kierunek obrotu, „Tylko gdy ON” (dla encji ON/OFF) oraz „Prędkość z encji (%)” dla wentylatorów — im wyższy procent obrotów, tym szybciej. Animacja nie „przeskakuje” przy odświeżaniu stanu i wyłącza się przy systemowym ograniczeniu ruchu.

## 0.4.1-beta.368

- Usunięte przyciąganie „8 px obok” sąsiedniej etykiety (zostają: ta sama krawędź, styk, środki oraz „Odstępy”).

## 0.4.1-beta.367

- **Menu przyciągania — siatka w jednym rzędzie**: bez napisu „Siatka” i „ON”; sama ikona siatki jest przełącznikiem (podświetlona, gdy siatka włączona, szara, gdy wyłączona), a obok w tym samym rzędzie wielkości S / M / L (przygaszone przy wyłączonej siatce).

## 0.4.1-beta.366

- **„Odstępy” jako osobna opcja przyciągania**: w menu magnesu obok „Środki” i „Krawędzie” jest nowa ikona „Odstępy” — ustawianie etykiety dokładnie pośrodku między dwiema innymi oraz powtarzanie odstępu z sąsiedniej pary. Ma własny, limonkowy kolor znaczników i podświetlenia (krawędzie i środki zostają różowe). Odstęp 8 px „obok” nadal należy do krawędzi.

## 0.4.1-beta.365

- **Przyciąganie do częściowo widocznych etykiet**: przy przybliżonym widoku plan zajmuje cały ekran (poza kartą), a „widoczny obszar” był liczony tylko z karty — etykiety widoczne na ekranie, ale poza kartą, były pomijane. Teraz liczy się cały ekran pod górnym paskiem; każdy obiekt choć częściowo widoczny jest celem przyciągania.

## 0.4.1-beta.364

- **Przyciąganie słucha ustawień „Krawędzie” / „Środki”**: przy przeciąganiu etykiet wyłączone krawędzie nie przyciągają (także styk, odstęp 8 px i równe odstępy, które się na nich opierają), a wyłączone środki — środków.
- **Środek łapie z dalszej odległości**: środek do środka przyciąga z ok. 1,7× większej odległości niż krawędzie (etykiety, wskaźniki, Flow, pomieszczenia i tło).

## 0.4.1-beta.363

- **Etykieta w pomieszczeniu przyciąga się też do innych etykiet**: etykieta pomieszczenia leżąca w nim w całości przyciąga się do tego pomieszczenia oraz (przy włączonych „Etykietach” w menu magnesu) do innych etykiet; nadal nie do innych pomieszczeń, wskaźników, Flow ani tła.

## 0.4.1-beta.362

- **Nazwa przechodzi do wyszukiwania encji**: w kreatorze nowej etykiety / pomieszczenia wpisana nazwa (np. „wyspa”) trafia od razu do pola wyszukiwania w kroku encji (można ją tam edytować), a lista od razu podpowiada pasujące encje. Gdy nic nie pasuje, widać zwykłe podpowiedzi.
- **Mądrzejsze wyszukiwanie encji w kreatorze**: po słowach w dowolnej kolejności, bez polskich znaków i z tolerancją końcówek („wyspa” znajduje „Lampa nad wyspą”, „kuchnia” — „kuchni”).

## 0.4.1-beta.361

- **Etykieta w swoim pomieszczeniu przyciąga się tylko do niego**: gdy etykieta pomieszczenia leży w całości wewnątrz tego pomieszczenia (i w menu magnesu włączone są „Pomieszczenia”), przyciąga się wyłącznie do jego krawędzi / środka i do własnych części. Wysunięta poza pomieszczenie przyciąga się do innych obiektów jak zwykle.
- **Tylko obiekty widoczne na ekranie** (na stałe): przy przybliżonym widoku elementy, etykiety, pomieszczenia i krawędzie tła poza ekranem nie są już celami przyciągania.

## 0.4.1-beta.360

- **Etykieta pomieszczenia = etykieta przy przyciąganiu**: krawędzie i środek własnego pomieszczenia przyciągają jego etykietę tylko przy włączonym „Pomieszczenia” w menu magnesu (wcześniej zawsze, nawet gdy włączone były same etykiety).
- **Linie pomieszczeń tylko w jego obrębie**: linia pomocnicza od pomieszczenia sięga przez to pomieszczenie, a nie przez całe tło (także przy przeciąganiu wskaźników i Flow).
- **Podświetlenie celu**: obiekt, do którego przyciąga się przeciągany element (etykieta, pomieszczenie, wskaźnik, Flow), dostaje delikatną ramkę z poświatą w kolorze swojego rodzaju.

## 0.4.1-beta.359

Przyciąganie etykiety do etykiety (przy przeciąganiu etykiety / grupy pomieszczenia):
- **Ta sama krawędź ma pierwszeństwo**: góra do góry, dół do dołu, środek do środka, lewa do lewej; styk krawędzi (obok siebie) ma niższy priorytet. Etykiety w tym samym rzędzie / kolumnie liczą się bardziej niż odległe.
- **Odstęp „obok”**: etykieta przyciąga się też 8 px od krawędzi sąsiedniej etykiety w rzędzie.
- **Równe odstępy**: trzecia etykieta przyciąga się do takiego samego odstępu, jaki mają dwie sąsiednie, albo dokładnie pośrodku między dwiema — z małymi znacznikami odstępów.
- **Linie od etykiety do etykiety** zamiast przez cały plan; złapana linia puszcza, gdy inna jest wyraźnie bliżej (np. przejście z „8 px obok” do styku).
- Wskaźniki, Flow, pomieszczenia i krawędzie tła nadal przyciągają, z niższym priorytetem.

## 0.4.1-beta.358

- **Dokładniejsze przyciąganie etykiet do siebie**: krawędzie przeciąganej etykiety były liczone od jej punktu zaczepienia, a nie od rzeczywistej ramki — w grupie o swobodnym układzie (np. po rozgrupowaniu i ponownym zgrupowaniu) ramka jest przesunięta względem punktu, więc etykieta „przyklejała się” kilka pikseli obok krawędzi drugiej. Teraz liczy się rzeczywista ramka (w teście: przyleganie dokładnie 0 px). Na telefonie promień przyciągania etykiet jest nieco większy (10 px zamiast 7).

## 0.4.1-beta.357

- **Integracje → „+” otwiera „Dodaj do widoku”**: zamiast od razu tworzyć etykietę, otwiera się menu wyboru (Etykieta, Pomieszczenie, Wskaźnik, Przepływ, Tekst) z tą encją już wybraną. Etykieta przechodzi do kreatora bez kroku encji, pomieszczenie do rysowania z tą encją, wskaźnik i przepływ dostają ją od razu.

## 0.4.1-beta.356

- **Integracje → „+” przy encji dodaje Etykietę**: zamiast starego badge otwiera się plan w trybie edycji i kreator etykiety z tą encją już wybraną — tylko nadanie nazwy (domyślnie nazwa encji) i wybór części (ikona / nazwa / stan), bez kroku wyboru encji. Encja użyta w etykiecie jest na liście oznaczona jako dodana.
- **Lista „Dodane”**: etykiety mają własną grupę „Etykiety” (wcześniej były wśród pomieszczeń).

## 0.4.1-beta.355

- **Przywracanie ukrytych części bez nachodzenia**: element, który rozgrupował się sam (bo została jedna widoczna część), po ponownym włączeniu nazwy / stanu znów staje się tą samą grupą (z jej układem), w miejscu, gdzie stoi widoczna część. W ręcznie rozgrupowanym elemencie włączona część jest odsuwana od pozostałych, żeby na nie nie nachodziła.

## 0.4.1-beta.354

- **Jedna widoczna część = automatyczne rozgrupowanie**: gdy w zgrupowanej etykiecie / pomieszczeniu wyłączysz widoczność tak, że zostaje tylko jedna część (np. sama ikona), grupa rozgrupowuje się sama w miejscu — od razu widać kółeczka do zmiany rozmiaru tej części. Istniejące grupy z jedną widoczną częścią rozgrupowują się przy otwarciu edytora.

## 0.4.1-beta.353

- **Puste kafle na starcie obrotu kostki**: w pierwszej klatce obrotu brakowało kafli planu dokładnie pod etykietami z rozmytym tłem — wyłączanie rozmycia na czas obrotu zmuszało telefon do przerysowania tych kafli. Na urządzeniach dotykowych etykiety i znaczniki na planie nie używają już rozmycia tła wcale (półprzezroczyste tło zostaje), więc na starcie obrotu nic się nie przełącza. Rozmycie było też najdroższym efektem dla telefonu. Na komputerze bez zmian.

## 0.4.1-beta.352

- **Pusta karta w pierwszej klatce obrotu przy zoomie**: na nagraniu przy przybliżonym widoku, gdy przy krawędzi zaczynał się obrót kostki, przez 1–2 klatki karta była pusta (widać było tylko poświatę i żarówkę). Start obrotu usuwał osobną warstwę planu i plan musiał się od nowa narysować w teksturze karty. Od 351 karta zawsze przycina plan do ekranu, więc ta zamiana nie jest już potrzebna — warstwa planu zostaje, a na czas obrotu wyłączane jest tylko rozmycie pod etykietami.

## 0.4.1-beta.351

- **Naprawa regresji z 350 (kostka przy 100%)**: wyłączenie trybu obrotu przy 100% sprawiło, że obracana karta znów nie przycinała planu i miała rozmyte etykiety jako osobne warstwy — telefon rysował ją tylko częściowo, a etykiety znikały. Teraz karta zawsze przycina plan do krawędzi ekranu (na stałe, bez przełączania przy zoomie i obrocie), a tryb obrotu (bez rozmycia pod etykietami na czas obrotu) znów działa także przy 100%. Bez zmiany z 350: dotknięcie przy 100% nie robi z planu osobnej warstwy, więc start obrotu nie przerysowuje karty.

## 0.4.1-beta.350

- **Pusta karta w pierwszej klatce obrotu kostki (100%)**: na nagraniu 90 kl./s w pierwszej klatce obrotu cała karta była pusta, z jednym prostokątnym kawałkiem planu. Przy 100% każde dotknięcie robiło z planu osobną warstwę GPU (choć przy 100% nie ma czego przesuwać), a start obrotu od razu ją usuwał — karta musiała się przerysować w pierwszej klatce ruchu. Teraz przy 100% dotknięcie nie tworzy warstwy (dopiero szczypanie lub przesuwanie, gdy jest możliwe), a specjalny tryb obrotu (z 342) włącza się tylko przy przybliżonym widoku — przy 100% kostka obraca się jak dawniej.

## 0.4.1-beta.349

- **Zapalanie / gaszenie pomieszczeń bez znikających kafli**: na nagraniu przy każdej zmianie światła na klatkę znikały prostokątne fragmenty planu. Poświata na czas płynnego zapalania / gaszenia dostawała chwilową warstwę GPU, a po animacji ją traciła — to za każdym razem przebudowywało warstwy planu. Poświaty mają teraz stałą, własną warstwę (zapalanie to tylko zmiana przezroczystości, bez przerysowania planu), a przy pomieszczeniach z innym kolorem dla OFF obraz poświaty jest podmieniany w tym samym elemencie, gdy nowy jest gotowy (wcześniej element był wymieniany dwa razy).
- Cofnięte synchroniczne dekodowanie tła z 347 (spowalniało rysowanie kafli; właściwą przyczynę usunęła 348).

## 0.4.1-beta.348

- **Plan nie znika przy przejściu przez 100% zoomu**: na nagraniu 60 kl./s przez 2–6 klatek znikało całe tło i poświaty (zostawały same znaczniki) dokładnie wtedy, gdy szczypanie przekraczało 100% w górę lub w dół. W tym momencie widok przełączał tryb „plan może wyjść poza kartę”, co przebudowywało warstwy grafiki w trakcie gestu. Dla planów pionowych ten tryb jest teraz włączony na stałe (przy 100% i tak nic nie wychodzi poza kartę), a zaokrąglone rogi rysuje sam plan — wygląd bez zmian.

## 0.4.1-beta.347

- **Tło nie znika przy szczypaniu**: na nagraniu przy przybliżaniu / oddalaniu palcami była klatka, w której plan rysował się bez obrazu tła (same znaczniki na ciemnym polu) — przeglądarka dekodowała duży obraz w nowej skali „w tle” i przez chwilę pokazywała plan bez niego. Tło, tło nocne, poświaty i podgląd sąsiedniego widoku są teraz dekodowane synchronicznie, więc obraz jest zawsze rysowany razem z resztą planu.

## 0.4.1-beta.346

- **Bez mignięcia przy niedokończonym obrocie kostki**: gdy po dojechaniu do krawędzi przybliżonego planu obrót się zaczął, ale nie przeszedł na sąsiedni widok, plan wracał do zwykłego trybu rysowania w tej samej klatce, w której karta odskakiwała na miejsce — i migał. Teraz wraca dopiero, gdy karta chwilę stoi (ok. 0,3 s) albo przy następnym dotknięciu.

## 0.4.1-beta.345

- **Kostka wraca przy przybliżonym widoku**: przy zoomie karta widoku nie przycina planu (tło może wyjść na całą szerokość ekranu), więc obracana karta zawierała cały, wielokrotnie większy od ekranu plan — telefon rysował go w obrocie tylko częściowo (ucięta dolna część, znikające elementy). Na czas obrotu karta jest teraz przycinana do tego, co widać na ekranie, a rozmycie tła pod etykietami (osobne warstwy, które w 3D znikały) jest na ten moment wyłączane.

## 0.4.1-beta.344

- **Mniej mignięć przy przybliżaniu**: po każdym zoomie plan był przerysowywany dwa razy (zmiana z 341, potrzebna tylko dla kostki — a ta przy zoomie już nie występuje), więc wracamy do jednego przerysowania. Do tego tło, poświaty i znaczniki są teraz jedną warstwą: wcześniej tło było osobną warstwą i telefon potrafił pokazać je już gotowe, zanim dorysował poświaty / znaczniki (krótkie zniknięcie). Teraz plan jest pokazywany w całości albo wcale.

## 0.4.1-beta.343

- **Przybliżony widok przechodzi przesunięciem zamiast kostką**: telefon nie potrafi narysować przybliżonego planu (wielokrotnie większego od ekranu) w obrocie 3D — znikały poświaty, znaczniki, a nawet dolna część planu. Gdy widok jest przybliżony, przejście do sąsiedniego widoku jest więc zwykłym płaskim przesunięciem (płynnym jak przesuwanie planu); bez przybliżenia nadal działa kostka.

## 0.4.1-beta.342

- **Kostka przy przybliżonym widoku — właściwa przyczyna**: przy zoomie plan jest ogromną warstwą (kilka razy większą od ekranu). Gdy karta obraca się w 3D, telefon nie potrafi policzyć, który jej fragment jest widoczny, i rysuje ją tylko częściowo — stąd znikające / do połowy zapalone poświaty. Na czas obrotu kostki plan nie jest już osobną warstwą: jest rysowany do tekstury samej karty (rozmiaru ekranu), która jest zawsze narysowana w całości i tylko się obraca. Po obrocie wszystko wraca do zwykłego trybu.

## 0.4.1-beta.341

- **Kostka przy przybliżonym widoku bez mrugania**: po zmianie zoomu plan tracił swoją warstwę GPU (żeby przerysować się ostro) i tworzył ją dopiero przy następnym dotknięciu — czyli dokładnie w chwili startu obrotu kostki, gdy telefon musiał narysować ogromną, przybliżoną warstwę. Teraz warstwa jest odtwarzana w nowej, ostrej skali od razu po przybliżeniu, w spoczynku, więc obrót startuje z gotowym obrazem. Przy wpisywaniu tekstu (klawiatura) warstwa nadal jest wyłączana.

## 0.4.1-beta.340

- **Płynne poświaty na telefonie**: na nagraniu przy dużym przybliżeniu poświata była dorysowywana kawałkami (połowa pomieszczenia oświetlona, połowa nie), a przy obrocie kostki znikała. Powodem było mieszanie kolorów „rozjaśnij”, przez które telefon musi składać plan w drogich kafelkach. Na urządzeniach dotykowych poświata jest teraz zwykłym półprzezroczystym obrazem z „rozjaśnieniem” wypieczonym na podstawie średniego koloru tła pod pomieszczeniem (z jasnością dnia / nocy i przyciemnieniem od słońca) — wygląda praktycznie tak samo, ale ma własną, małą warstwę GPU rysowaną raz, więc przy przesuwaniu, zoomie i kostce tylko się przesuwa.
- Nowa opcja w ustawieniach: **Poświata pomieszczeń** — Automatycznie (płynna na telefonie, dokładna z myszą) / Płynna / Dokładna.

## 0.4.1-beta.339

- **Poświaty przy obrocie kostki (ciąg dalszy)**: każda poświata miała własną warstwę GPU z mieszaniem „rozjaśnij”; gdy karta widoku zaczynała obrót 3D, telefon przez kilka klatek składał je źle i znikały (także na wjeżdżającym widoku). Poświaty — już jako małe, gotowe obrazy — są teraz częścią samego planu, więc obracana karta jest jedną gotową teksturą.

## 0.4.1-beta.338

- **Poświaty pomieszczeń przy obrocie kostki**: podgląd sąsiedniego widoku (to, co wjeżdża podczas przewijania) rysował poświaty rozmyciem na żywo, którego telefon nie nadążał narysować w obrocie 3D — pomieszczenia zapalały się dopiero na końcu animacji. Podgląd używa teraz tych samych gotowych obrazów poświat co sam widok, przygotowanych zawczasu.

## 0.4.1-beta.337

- **Mniej przerysowań planu przy dotyku**: plan dostawał osobną warstwę GPU przy każdym dotknięciu i tracił ją 350 ms po puszczeniu — każde takie przełączenie przerysowuje cały plan i mogło mignąć. Po zwykłym przesuwaniu (bez zmiany zoomu) warstwa teraz zostaje, więc kolejne przesunięcia już nic nie przełączają. Jest zdejmowana tylko wtedy, gdy byłaby nieaktualna: po zmianie zoomu (żeby plan znów był ostry), po zmianie rozmiaru okna i przy wpisywaniu tekstu (klawiatura).

## 0.4.1-beta.336

- **Poprawka mrugania poświat (beta 335 pogorszyła sprawę)**: na początku gestu przesuwania / przybliżania telefon przerysowywał cały plan razem z pełnoekranowymi obrazami poświat i przez kilka klatek ich nie pokazywał. Teraz każda poświata jest przycięta do swojego pomieszczenia (dużo mniejszy obraz) i ma własną, stałą warstwę GPU — przy gestach jest tylko przesuwana / skalowana, bez przerysowywania.

## 0.4.1-beta.335

- **Podświetlone pomieszczenia nie mrugają przy przesuwaniu planu palcem**: miękka poświata pomieszczenia była rozmywana na żywo i telefon przeliczał ją od nowa na początku / końcu każdego gestu, przez co potrafiła zniknąć na jedną klatkę. Teraz poświata jest rysowana raz (po każdej zmianie wyglądu) do gotowego obrazu, który przesuwa się i skaluje bez przeliczania. Wygląd bez zmian; pomieszczenia z ostrą krawędzią (bez wtapiania) zostają rysowane jak dotąd.

## 0.4.1-beta.334

- **Ikona etykiety / pomieszczenia rysowana jako SVG**: zamiast znaku z czcionki ikon (którego położenie zależy od silnika przeglądarki — w aplikacji HA na telefonie był przesunięty w prawo i w dół) ikona jest teraz rysowana jako wektor 24×24, zawsze dokładnie na środku kółka / ramki. Kolor, przezroczystość, wypełnienie, obrys i cień działają jak dotąd. Przez ułamek sekundy po pierwszym wyświetleniu nowej ikony może być widoczny stary znak z czcionki.

## 0.4.1-beta.333

- **Ikona etykiety / pomieszczenia na środku także na telefonie**: aplikacja mierzy (raz na ikonę), gdzie przeglądarka danego urządzenia faktycznie rysuje kształt ikony, i dosuwa go dokładnie na środek kółka / ramki. Dotyczy wszystkich ikon MDI, także niesymetrycznych (dom, termometr, garaż…).

## 0.4.1-beta.332

- **Ikona etykiety / pomieszczenia dokładnie na środku swojej ramki**: glif ikony był ustawiany względem linii pisma czcionki systemowej, co na telefonie (inna czcionka niż na komputerze) potrafiło przesunąć dużą ikonę w dół i w bok wewnątrz tła / ramki. Teraz glif ma własny kwadrat 1 em, wyśrodkowany niezależnie od czcionki systemu.

## 0.4.1-beta.331

Edycja na telefonie — **najpierw zaznacz, potem przesuwaj**:
- Palec na **niezaznaczonym** elemencie (etykieta, marker / wskaźnik, Flow) go nie przesuwa: przeciąganie przesuwa plan, a krótkie dotknięcie zaznacza element. Przesuwać da się tylko zaznaczony element — koniec z przypadkowym przesuwaniem sąsiednich obiektów przy przewijaniu planu.
- **Pomieszczenie** (zaznaczone) przesuwa się dopiero po krótkim przytrzymaniu palca (~0,35 s, krótka wibracja); szybki ruch palcem po pomieszczeniu przesuwa plan. Narożniki działają jak dotąd.
- Na komputerze (mysz) bez zmian.

## 0.4.1-beta.330

- **Nowa etykieta / pomieszczenie: ikona domyślnie szara** (zamiast żółtej) dla encji, które się nie włączają i nie wyłączają (np. czujnik temperatury). Światła i przełączniki dalej mają kolor ON (bursztynowy) i OFF (szary). Miniatura „Etykieta” w oknie dodawania też ma szarą ikonę. Istniejące etykiety się nie zmieniają.

## 0.4.1-beta.329

- **Punkty kształtu pomieszczenia**: po najechaniu kursor zmienia się na strzałki przesuwania (narożniki) albo plus (punkty środkowe — dodają narożnik), a punkt powiększa się i podświetla; przy przeciąganiu kursor „zaciśniętej dłoni”.

## 0.4.1-beta.328

- **Etykieta / pomieszczenie → Stan → Format**: własne „Tekst ON” / „Tekst OFF” działają też dla bram, rolet, zamków, czujników binarnych itp. (np. `cover` „closed” → Twój tekst OFF, „open” → tekst ON). Wcześniej działały tylko dla świateł i przełączników, a dla pozostałych widać było surowy stan z HA. Puste pola zostawiają stan z HA.

## 0.4.1-beta.327

**Wskaźnik (gauge / podkowa) — nowy panel, jak panel etykiety:**
- **Ogólne**: nazwa, **Typ** (gauge / podkowa jako dwie ikony — zamiast zakładek u góry), dotknięcie w widoku, encja.
- **Wskaźnik** (niebieska sekcja) z przyciskami na pasku: Gradient, Podziałka, Liczby skali, Procent. Podsekcje: Rozmiar, Zakres, Łuk (grubość, tor, wartość albo kolory gradientu), **Kąt** — gotowe łuki jednym kliknięciem (gauge: 180°/240°/270°/300°, podkowa: 240°/270°/300°/320°, symetryczne względem góry) oraz dowolne „Kąt start / Kąt koniec”, skala i pozycja; Podziałka / Liczby skali / Procent tylko gdy włączone.
- **Ikona, Nazwa, Stan** w kolorach jak w etykiecie, z przyciskiem „Pokaż” (i dla ikony: Obrys, Tło, Ramka) na pasku; Rozmiar jako pierwsza podsekcja; Stan → Format (jednostka, zaokrąglenie, teksty ON/OFF tylko dla encji ON/OFF).
- **Grupa** (tło i ramka całego wskaźnika) z przyciskami Tło / Ramka na pasku i podsekcją Kształt.
- Otwarta podsekcja nie zamyka się po zmianie przełącznika.

Ogólnie: wartości suwaków pokazują tyle miejsc po przecinku, ile ma krok (np. „1.09” zamiast „1.0869565…”); przyciski wyboru w popupach mają jednakowy rozmiar 30 px.

## 0.4.1-beta.326

- **Pomieszczenie ma jedną encję** (jak etykieta): w Ogólnych wyszukiwarka jest tylko, gdy nie ma encji; w kreatorze wybranie encji od razu kończy krok. Pomieszczenia z kilkoma encjami z wcześniej je zachowują.
- **Przyciąganie wszystkiego do wszystkiego**: etykiety (grupa albo rozgrupowane części) są znowu celami linii pomocniczych — przy przesuwaniu markerów, Flow, pomieszczeń (całych i narożników) i innych etykiet; przesuwana etykieta łapie też markery, Flow, inne etykiety, pomieszczenia i tło.
- **Kolory linii pomocniczych wg źródła**: etykieta — różowa, pomieszczenie — pomarańczowa, tło (krawędzie i środek ekranu) — zielona, wskaźnik / marker — niebieska, Flow — turkusowa.
- **Menu magnesu uporządkowane**: na wierzchu Siatka, Linie pomocnicze, Przyciągaj do (etykiety, wskaźniki, Flow, pomieszczenia, tło) i Punkty (środki, krawędzie); „Granice tła”, „Wyrównaj zaznaczony do tła” i „Obróć zaznaczony” schowane pod „Więcej”. Usunięto „Tylko elementy widoczne na ekranie” i na razie „Siatkę dashboardu”.
- **Okno dodawania — 5 kafelków**: Etykieta (miniatura z ikoną, nazwą i stanem), Pomieszczenie, Wskaźnik (gauge; podkowę wybierzesz w panelu), Flow, Tekst / przycisk. Badge nie jest już dodawany (istniejące działają); czujnik bez mocy / procentów proponuje Etykietę.

## 0.4.1-beta.325

- **Etykieta nazywa się etykietą wszędzie**: potwierdzenie usuwania („Usunąć etykietę?”), komunikaty (usunięto / kopia), podpowiedzi przycisków w nagłówku (duplikuj / kopiuj / wklej styl / usuń etykietę), lista „Dodane do widoku” (własna ikona), domyślna nazwa przy pustym polu.
- **Popup pomieszczenia jak popup etykiety**:
  - sekcja **„Ogólne”** (zamiast „Pomieszczenie”) w tym samym zwartym układzie: nazwa na całą szerokość, stan i przyciski dotknięcia po prawej, encje bez podpisu (pomieszczenie dalej może mieć kilka encji, wyszukiwarka zostaje);
  - sekcja **„Wygląd”** z własnym kolorem i przyciskiem **Obrys** na pasku; podsekcje **Kolor**, **Światło** (miękkość, efekt światła) i **Obrys** (tylko gdy włączony);
  - Grupa, Ikona, Nazwa i Stan działają tak samo jak w etykiecie (grupowanie, rozgrupowanie, kropki rozmiaru, przyciski na paskach, kolory sekcji).

## 0.4.1-beta.324

- **Grupa po ponownym zgrupowaniu dopasowuje się do widocznych części**: gdy ukryjesz np. ikonę albo stan (Grupa → Pokaż), tło i ramka grupy obejmują tylko to, co zostało — bez pustego miejsca po ukrytej części; pozostałe części nie przesuwają się. Po ponownym pokazaniu części grupa wraca do pełnego rozmiaru.

## 0.4.1-beta.323

- **Siatka dashboardu** (menu magnesu → „Siatka dashboardu”): siatka kolumny × wiersze (np. 3 × 8) z odstępem, ustawiana osobno dla każdego widoku i widoczna w trybie edycji. Przeciągana grupa etykiety pokazuje kratki, na które trafi, a po upuszczeniu przyciąga się do nich i wypełnia je (tło grupy ma rozmiar kratek). W sekcji Grupa: „Szerokość (kratki)”, „Wysokość (kratki)”, przypnij / odepnij od siatki. Zmiana liczby kolumn / wierszy / odstępu przesuwa przypięte grupy razem z siatką; wyłączenie siatki zostawia je na miejscu.
- **Granice tła dla etykiet**: przeciągana grupa (albo rozgrupowana część) zatrzymuje się na krawędzi tła — nie da się nią wyjechać poza tło (gdy „Granice tła” są włączone).
- **Grupa → Rozmiar**: przycisk „Przywróć domyślną wartość” działa (wraca do 1×).
- **Grupa → Tło i Ramka** jako przyciski na pasku sekcji Grupa (jak w Ikonie, Nazwie i Stanie); wyłączone nie pokazują podsekcji.
- Krótko po puszczeniu przeciąganego elementu albo kropki rozmiaru kliknięcie nie jest już „połykane” (wcześniej przez pół sekundy).

## 0.4.1-beta.322

- **Dodawanie etykiety, krok 2/3 (encja)**: wybranie encji od razu przechodzi do kroku 3/3 („Co ma być widać?”) — drugiej encji nie da się dodać (klawiatura się chowa).

## 0.4.1-beta.321

Etykieta / pomieszczenie — sekcje **Ikona, Nazwa, Stan**:
- **Przyciski na pasku sekcji**: Ikona — Obrys, Tło, Ramka; Nazwa i Stan — Tło, Ramka. Kliknięcie włącza / wyłącza element bez otwierania sekcji; podsekcje wyłączonych elementów są ukryte (mniej bałaganu).
- **Każda sekcja ma swój kolor** (Ikona — bursztynowy, Nazwa — zielony, Stan — fioletowy): kolorowy tytuł, pasek z lewej i aktywne przyciski.
- **„Rozmiar” jest pierwszą podsekcją** w Ikonie, Nazwie i Stanie.
- „Treść” zmieniono na **„Źródło”** (ikona) i **„Format”** (stan: tekst ON/OFF albo jednostka i zaokrąglenie).
- Zaokrąglenie i margines ramki są w podsekcji Ramka, a gdy ramka jest wyłączona — w Tle.

## 0.4.1-beta.320

- **Popup na komputerze**: sekcje są szersze i kończą się dokładnie pod ikonami nagłówka i X (wąski, 6-pikselowy pasek przewijania zamiast szerokiego marginesu). Na telefonie sekcje też równo z X.

## 0.4.1-beta.319

- **Nagłówek popupu**: ikony akcji (domyślny wygląd, duplikuj, kopiuj / wklej styl, usuń) są zawsze wyrównane do prawej, równo z X — także gdy nie ma przełącznika podglądu ON/OFF (np. dla czujnika) i w trybie panelu bocznego.

## 0.4.1-beta.318

- **„Przywróć domyślną wartość” działa przy każdym suwaku** etykiety / pomieszczenia — także przy nowych: przezroczystość nazwy i stanu, przezroczystość / grubość ramki, zaokrąglenie i margines ramki (te dwa wracają do wartości automatycznej, rosnącej z tekstem) itd.
- **Tytuły podsekcji** (Treść, Kolor, Rozmiar, Tło, Ramka…) mają własny, jaśniejszy niebieski kolor — nie zlewają się z nazwami głównych sekcji.
- **Usunięto na razie „Kolory wg wartości”** z etykiety / pomieszczenia (sekcja i jej działanie); markery mają je bez zmian.

## 0.4.1-beta.317

- **Wybór koloru w popupach**: po otwarciu palety pole koloru zostaje na swoim miejscu (po prawej), a paleta rozwija się pod nim, wyrównana do prawej krawędzi — wcześniej pole przeskakiwało na lewo.

## 0.4.1-beta.316

Popupy (marker, Flow, pomieszczenie, etykieta) — wszystko równo do prawej krawędzi:
- **Wybór koloru, pola wyboru (ptaszki), przyciski wyboru i pola tekstowe** (np. „Jednostka” w Treści stanu) kończą się na prawej krawędzi, w każdej sekcji i podsekcji.
- **Przyciski wyboru z ikoną** (Źródło, Kształt, Dotknięcie, Kierunek, Efekt światła…) mają ten sam rozmiar 30 px co pozostałe ikony.
- **Grubość czcionki** jako ikony (domyślna / normalna / średnia / pogrubiona); **Obrys pomieszczenia → Linia** też jako ikony.
- **Zaokrąglenie stanu** jako lista rozwijana (mieści się w jednym wierszu).

## 0.4.1-beta.315

- **Grupa**: „Tło” i „Ramka” jako dwa przyciski-ikony w jednym wierszu („Tło i ramka”) zamiast dwóch pól wyboru.
- **Suwaki we wszystkich popupach** (marker, Flow, pomieszczenie, etykieta): nazwa po lewej, wartość (px, %, ×…) między nazwą a suwakiem, suwak dosunięty do prawej krawędzi, przycisk przywracania na końcu.

## 0.4.1-beta.314

Etykieta / pomieszczenie → sekcja **Grupa** (nowy, zwarty układ jak w Ogólnych — wszystko dosunięte do prawej krawędzi):
- Na górze wiersz **„Grupa”** z przyciskiem grupowania w innym (pomarańczowym) kolorze; niżej Rozmiar, **„Pokaż”** (ikona / nazwa / stan), Układ (dla zgrupowanych), Styl, Margines.
- **Włączniki „Tło” i „Ramka” grupy** bezpośrednio w sekcji; podsekcje Tło i Ramka pokazują się tylko, gdy są włączone. Zaokrąglenie jest w Ramce (albo w Tle, gdy ramka jest wyłączona).
- Usunięto **„Wyrównanie”**; **Styl** ma 4 warianty (Ciemne, Jasne, Szkło, Kolor pokoju) — „Bez tła” zastąpił włącznik Tła.
- **Tylko jedna widoczna część** (np. sama ikona): tło, ramka i margines grupy nie są rysowane (nie ma podwójnej ramki), a opcje grupy są ukryte. Ustawienia nie giną — wracają, gdy pokażesz drugą część.

## 0.4.1-beta.313

- **Etykieta → Ogólne, zwarciej**: bez podpisu „Encja” — pole encji jest od razu pod „Dotknięciem w widoku”; pole nazwy, przyciski dotknięcia (wyrównane do prawej) i pole encji kończą się na tej samej prawej krawędzi; pole encji ma tę samą wysokość co pole nazwy.

## 0.4.1-beta.312

- **„Ikona” nazywa się teraz „Etykieta”** (ang. „Label”) — w menu dodawania („Ikona, nazwa i stan w dowolnym miejscu”), w popupie, w kreatorze („Nazwa etykiety”, „Encja etykiety”, „Utwórz etykietę”) i w komunikatach; nowe dostają nazwy „Etykieta 1”, „Etykieta 2”… Zapisane elementy działają bez zmian. Sekcja „Ikona” w popupie zostaje (to część etykiety).
- **Etykieta ma jedną encję**: w kreatorze wybór innej encji zastępuje poprzednią; w sekcji Ogólne pole wyszukiwania jest widoczne tylko, gdy etykieta nie ma encji — po dodaniu znika, po usunięciu encji wraca.

## 0.4.1-beta.311

- **Obrys pomieszczenia** (Wygląd → Obrys): linia wzdłuż kształtu pomieszczenia — ciągła, kreskowana albo kropkowana; kolor, przezroczystość, grubość, opcjonalnie zależne ON/OFF (tylko dla encji ON/OFF). Obrys jest rysowany nad światłem i nie gaśnie razem z nim.
- **Markery**: „Grubość czcionki” dla nazwy i stanu (domyślna / normalna / średnia / pogrubiona).
- **Markery — ikona**: tło ikony, ramka ikony (kolor, przezroczystość, grubość) i kształt (koło / kwadrat / dowolny z zaokrągleniem) z marginesem — tak jak ikona w etykiecie pomieszczenia.

## 0.4.1-beta.310

Ikona / pomieszczenie:
- **Stan → Treść**: dla encji ON/OFF własne „Tekst ON” i „Tekst OFF” (puste = „Wł.” / „Wył.”; jasność dalej dopisywana); dla encji liczbowej „Jednostka” (puste = z encji, „-” = bez jednostki) i „Zaokrąglenie” (automatycznie / 0 / 0,1 / 0,01 / 0,001).
- **Kolory wg wartości** (nowa sekcja, tylko dla encji liczbowej, np. temperatury): dolny i górny próg, kolor poniżej / pomiędzy / od górnego, płynne przejście; do wyboru kolorowanie ikony i/lub tekstu stanu.
- **Grupa → Tło → Cień**: cień pod tłem grupy można wyłączyć.

## 0.4.1-beta.309

- **Opcje ON/OFF tylko dla encji ON/OFF**: gdy encja się nie włącza i nie wyłącza (np. czujnik temperatury), popup nie pokazuje „Zależne ON/OFF”, „Ikona zależna ON/OFF”, kolorów/przezroczystości/grubości ON i OFF ani tekstów ON/OFF — tylko zwykłe ustawienia. Dotyczy ikony, nazwy, stanu, grupy (pomieszczenia i ikony) oraz markerów. Etykieta takiej encji zawsze używa zwykłych kolorów, więc to, co widać w popupie, odpowiada temu, co na planie (ustawienia ON/OFF z wcześniej nie giną — wrócą, gdy dodasz encję ON/OFF).

## 0.4.1-beta.308

- **Zmniejszanie rozgrupowanej części kropkami poniżej rozmiaru treści**: ikona albo tekst (nazwa, stan) zmniejsza się proporcjonalnie razem z ramką — ikona zostaje kwadratowa / okrągła, przeciwna krawędź stoi w miejscu. Rozciągnięcie z powrotem w tym samym ruchu przywraca pierwotny rozmiar treści, a dalej powiększa już tylko ramkę. Nowy rozmiar treści widać potem w suwaku „Rozmiar” danej części.

## 0.4.1-beta.307

Ikona / pomieszczenie — części etykiety:
- **Nazwa i stan mają te same opcje co ikona**: kolor zależny ON/OFF (kolor i przezroczystość osobno dla ON i OFF), przezroczystość tekstu, grubość czcionki (normalna / średnia / pogrubiona), tło i ramka zależne ON/OFF, rozmycie tła, zaokrąglenie i margines wewnętrzny ramki.
- **Jednakowy układ podsekcji** w Ikonie, Nazwie i Stanie: Treść → Kolor (→ Obrys dla ikony) → Rozmiar → Tło → Ramka. Kształt ikony (koło / kwadrat / dowolny), zaokrąglenie i margines są teraz w podsekcji Ramka.
- Usunięto przycisk „Układ grupy” (reset układu) — układ grupy przywraca „Ustaw domyślny” w nagłówku.

Popup:
- Podgląd ON/OFF jest pierwszy po lewej, pozostałe ikony nagłówka — po prawej.
- Encje: zostaje tylko pasek wyszukiwania (bez podpowiedzi); po dodaniu encji tekst wyszukiwania i lista sugestii znikają.

## 0.4.1-beta.306

Popup edycji (marker, Flow, pomieszczenie, ikona) — kompaktowo:
- **X w prawym górnym rogu**, na wysokości nazwy.
- **Jeden zwarty rząd ikon** pod nazwą (bez rozciągania na całą szerokość).
- **Podgląd ON/OFF jako jeden przełącznik** w tym samym rzędzie (żarówka, bez podpisu) — tylko dla elementów, które się włączają i wyłączają. Kliknięcie przełącza podgląd na stan przeciwny do widocznego; podświetlony = podgląd aktywny.
- **„Przenieś panel na drugą stronę”** zniknęło z popupu — teraz w ustawieniach widoku: „Panel edycji: Po prawej / Po lewej”.
- **Wszystkie ikony w popupie mają jeden rozmiar** (30 px): przyciski nagłówka, „Dotknięcie w widoku”, przełączniki i style w sekcji Grupa, zakładki typu markera.

## 0.4.1-beta.305

- **Usunięto „Jednakowe ramki”** (sekcja Grupa przy rozgrupowanej etykiecie). Rozmiar ramek ustawiasz kropkami na bokach.
- **Usunięto „Zablokuj geometrię”** z paneli znacznika, Flow, pomieszczenia i ikony. Elementy zablokowane wcześniej są po aktualizacji znowu odblokowane (blokada wróci później w innej formie).

## 0.4.1-beta.304

Etykieta (ikona / nazwa / stan):
- **Nowy znacznik**: ikona, nazwa i stan mają od początku własne tło i ramkę — także w grupie — i stykają się ze sobą, bez nachodzenia.
- **Części nie nachodzą na siebie**: przesuwana rozgrupowana część zatrzymuje się na krawędzi sąsiedniej (ślizga się wzdłuż niej), a rozciągana kropką krawędź zatrzymuje się na sąsiedniej części.
- **Ponowne zgrupowanie zachowuje wygląd**: tło i ramka nazwy oraz stanu zostają takie, jak były po rozgrupowaniu.
- **Panel**: sekcje Ikona / Nazwa / Stan pokazują się tylko dla widocznych części. W sekcji Grupa „Margines” jest pod „Rozmiarem”, „Zaokrąglenie” przeszło do podsekcji Ramka, a „Odstęp” usunięto (części w grupie stykają się); podsekcja Wymiary zniknęła.

## 0.4.1-beta.303

Zmiana rozmiaru rozgrupowanej części (kropki na bokach):
- **Blokada 1:1**: gdy szerokość zrówna się z wysokością, ramka „przykleja się” do kwadratu (silniej niż do innych linii), więc okrągła ikona zostaje kołem, a nie jajkiem.
- **Widać, kiedy jest symetrycznie**: przy równych bokach obwódka zaznaczenia i kropki zmieniają kolor na zielony — w trakcie rozciągania i po puszczeniu.
- Ikona ma teraz domyślnie idealnie kwadratową ramkę (wcześniej była o 1–3 px wyższa niż szersza).

## 0.4.1-beta.302

Rozgrupowana etykieta (ikona / nazwa / stan):
- **Nazwa i stan dostają tło i ramkę** po rozgrupowaniu (tak jak ikona), jeśli wcześniej ich nie miały; ponowne zgrupowanie zdejmuje tylko to, co zostało dodane automatycznie.
- **Ta sama czcionka stanu** w grupie i osobno (w grupie stan był trochę mniejszy); ramki nazwy i stanu mają też te same odstępy w obu trybach.
- **Tło grupy zostaje po rozgrupowaniu** i obejmuje wszystkie części — także w trakcie przesuwania, nawet gdy są mocno rozrzucone. Można je wyłączyć i ustawić (Tło grupy, Wymiary: zaokrąglenie i margines, Tło, Ramka) w sekcji Grupa.
- Margines tła grupy w swobodnym układzie (po ponownym zgrupowaniu) jest teraz liczony prawidłowo.

## 0.4.1-beta.301

Rozgrupowane części etykiety (ikona / nazwa / stan):
- **Zmiana rozmiaru ramki**: zaznaczona część ma kropki na środkach boków — przeciągając je zmieniasz szerokość lub wysokość ramki; przeciwna krawędź zostaje w miejscu, a ramka nie zmniejszy się poniżej treści.
- **Dopasowanie do sąsiadów**: rozciągana krawędź przyciąga się do krawędzi i środków sąsiednich części, a ramka do ich szerokości/wysokości — z linią pomocniczą.
- **Grupowanie zachowuje ułożenie**: ponowne włączenie grupowania zostawia części tam, gdzie je ustawiłeś (tło grupy obejmuje je w aktualnym układzie).
- **„Domyślny układ grupy”**: nowy przycisk w sekcji Grupa (pod „Pokaż”) przywraca standardowy układ grupy; wybór Układu też go przywraca.

## 0.4.1-beta.300

Linie pomocnicze dla rozgrupowanych części (ikona / nazwa / stan):
- **Łapią w trakcie jednego płynnego ruchu**: przesuwając część obok innej, kolejno dostajesz wyrównanie krawędź-krawędź, środek i drugą krawędź — bez puszczania i ponownego chwytania (wcześniej przy szybszym ruchu linia się nie pojawiała, a złapana linia trzymała za długo).
- **Linia leży dokładnie na krawędzi ramki**: przerywana obwódka edycji przylega teraz do ramki części (wcześniej była 6 px na zewnątrz, przez co linia wyglądała na „niedosuniętą”), a położenie nie jest już zaokrąglane do pełnych pikseli.
- **Cieńsze linie**, bez poświaty. Linie pomieszczenia (pomarańczowe) zostają.

## 0.4.1-beta.299

Sekcja **Grupa** (ikona / pomieszczenie):
- Na górze suwak **„Rozmiar”** (dawny „Rozmiar całości” z podsekcji Wymiary). Dla ikony **1,0× = domyślny rozmiar** nowej ikony, który jest teraz o 20% większy niż wcześniej (stare ikony pokażą ok. 0,85×).
- Podsekcja **Wymiary** jest zaraz pod przyciskami grupy (przed Tłem i Ramką).
- Usunięte suwaki położenia (Grupa → Położenie, a w Nazwie i Stanie „Przesunięcie” / „Lewo-prawo, góra-dół”) — elementy przesuwasz palcem lub myszą na planie.
- Po **rozgrupowaniu**: linie pomocnicze pokazują **krawędzie i środki** pozostałych części (ikona, nazwa, stan), a przeciągana część przyciąga się środkiem albo krawędzią — łatwe równe ustawienie.
- Po rozgrupowaniu nowy przycisk **„Jednakowe ramki”**: ikona, nazwa i stan dostają ten sam rozmiar ramki (największej z nich) — jedno kliknięcie zamiast suwaków szerokości i wysokości.
- Poprawka: suwak przezroczystości ramki nazwy / stanu działał źle (ramka zawsze w pełni widoczna).

## 0.4.1-beta.298

- Popup dodawania na telefonie z otwartą klawiaturą: lista encji zajmuje tylko miejsce, które zostaje nad klawiaturą (mniej wierszy naraz, reszta przewijana), więc przyciski **Pomiń / Dalej** są zawsze widoczne. Przy otwartej klawiaturze opis kroku jest ukryty, żeby popup był niższy.

## 0.4.1-beta.297

- Dodawanie ikony / pomieszczenia na telefonie: **klawiatura nie chowa się między nazwą a wyborem encji** — po Enter albo „Dalej” od razu aktywne jest wyszukiwanie encji. Przyciski i lista w popupie nie zabierają fokusu polu tekstowemu, więc zaznaczanie encji też nie zamyka klawiatury.

## 0.4.1-beta.296

Na podstawie nagrania z telefonu:
- **Mniej mignięć i rozmycia przy klawiaturze i zoomie**: plan (z tłem) był stale osobną warstwą grafiki; przy dużym zoomie i każdej zmianie rozmiaru okna przez klawiaturę telefon nie nadążał jej przerysować — pokazywał puste (granatowe) kafle albo rozmytą kopię. Teraz ta warstwa jest włączana tylko na czas przesuwania / szczypania palcem, a poza tym plan jest rysowany ostro w aktualnej skali.
- Komunikat „Dotknij plan w miejscu, gdzie ma stanąć element” znika od razu po wskazaniu miejsca (wcześniej zasłaniał plan jeszcze kilka sekund).
- Uwaga: biały pas, który przez chwilę widać w miejscu wysuwającej się / chowającej klawiatury, rysuje aplikacja Home Assistant (zmienia wtedy rozmiar całej strony) — HA Views nie ma na to wpływu.

## 0.4.1-beta.295

- **Płynna kamera przy klawiaturze**: centrowanie (zaznaczonego elementu i miejsca dodawanej ikony / pomieszczenia) nie przeskakuje już przy każdej zmianie wysokości wysuwającej się / chowającej klawiatury — kamera łagodnie dojeżdża do celu, a kolejne zmiany tylko przesuwają cel. W teście największy ruch na klatkę spadł z 35 px do 9 px. Dotknięcie planu palcem od razu przerywa ten ruch.
- Tak samo płynnie działa teraz centrowanie po stuknięciu elementu w edycji.

## 0.4.1-beta.294

Dodawanie ikony (i pomieszczenia) na telefonie:
- Po wskazaniu miejsca kamera **centruje się na nim** w wolnym polu pod popupem i **zostaje tam** przez cały popup — także gdy wysuwa się klawiatura (pole liczy się od dołu popupu do górnej krawędzi klawiatury) i przy przejściu do kolejnego kroku.
- Wybrane miejsce oznacza **pulsująca pinezka**, dopóki ikona nie zostanie utworzona.
- Lista encji w popupie ma stałą wysokość, więc nie skacze przy otwieraniu klawiatury.

## 0.4.1-beta.293

- Poprawka: **„Przywróć domyślny wygląd”** ukrywał ikonę (i etykietę pomieszczenia) — kasował też przełączniki Ikona / Nazwa / Stan, a te są domyślnie wyłączone. Teraz przywraca wygląd nowo dodanego elementu: grupa włączona, ikona z obrysem, tłem i ramką, nazwa i stan widoczne (ikona: rozmiar całości ×0,5; pomieszczenie: grupa dopasowana do kształtu). Położenie ikony, kształt pomieszczenia, nazwa i encje zostają. Ikonę niewidoczną po wcześniejszym resecie naprawisz, klikając „Przywróć” jeszcze raz.

## 0.4.1-beta.292

- Włączanie / wyłączanie **grupowania** nie przesuwa już elementów: po rozgrupowaniu ikona, nazwa i stan zostają dokładnie tam, gdzie były w grupie, a po zgrupowaniu grupa staje na środku miejsca, które zajmowały części. Wcześniej oba tryby miały osobne, niezależne położenia.
- „Rozmiar całości” (sekcja Grupa) działa teraz także na części rozgrupowane, więc przełączanie grupowania nie zmienia ich wielkości.

## 0.4.1-beta.291

Panel ikony / pomieszczenia:
- **Podgląd stanu (ON/OFF)** jest widoczny tylko, gdy encja może być włączona / wyłączona (światło, włącznik, czujnik binarny, roleta, klimat, media…). Dla np. czujnika temperatury go nie ma.
- **Ogólne** (ikona): bez wiersza „Stan”. **Dotknięcie w widoku**: kwadratowe przyciski, wyrównane z resztą sekcji (także w panelu markera).
- **Grupa**: na górze rząd 4 kwadratowych przełączników — **Grupuj, Ikona, Nazwa, Stan** (przełączniki „Pokaż” przeniesione tu z sekcji Ikona / Nazwa / Stan; co najmniej jedna część musi zostać widoczna). Wszystkie przyciski w sekcji (Układ, Styl, Wyrównanie) mają ten sam rozmiar i są wyrównane w rzędach.
- **Nazwa** i **Stan** mają podsekcje **Tekst, Tło, Ramka, Położenie**; nowa **ramka** nazwy / stanu (kolor, przezroczystość, grubość — rysowana do środka, nie zmienia rozmiaru).
- **Ramka zaznaczenia markera / Flow** ma tę samą grubość (2 px, przerywana niebieska) co ramka zaznaczonej ikony i obrys pomieszczenia.

## 0.4.1-beta.290

- Przytrzymanie markera (albo ikony, etykiety, Flow) na planie nie zaznacza już tekstu i nie otwiera menu przeglądarki „Kopiuj / Udostępnij”. Tekst na planie nie jest zaznaczalny, a menu kontekstowe na planie jest wyłączone (pola w panelach edycji działają normalnie).

## 0.4.1-beta.289

- Chwycenie i od razu przesunięcie **ikony albo etykiety pomieszczenia** nie otwiera już panelu edycji — panel otwiera się tylko po stuknięciu (puszczenie bez przesuwania). Gdy panel tego elementu był już otwarty, zostaje otwarty także po przesunięciu. Markery i Flow działały już tak wcześniej.

## 0.4.1-beta.288

- **Ołówek (tryb edycji) to już tylko przełącznik** — bez menu „Dodaj / Język”. Gdy edycja jest włączona, ołówek jest podświetlony; dla podglądu (viewer) przycisku nie ma, jak wcześniej. Elementy dodajesz przyciskiem **+** w górnym pasku.
- **Język** jest teraz w menu widoku → **Opcje** (obok „Przełączania palcem”), z nazwami „English” / „Polski”.
- Usunięte nieużywane już ukryte przyciski starego menu (Pomieszczenie / Flow / Tekst) — wszystko dodaje się przez okno „Dodaj”.

## 0.4.1-beta.287

Telefon, edycja pól tekstowych z klawiaturą ekranową:
- **Centrowanie bez opóźnienia** — gdy klawiatura się wysuwa, zaznaczony marker / ikona / pomieszczenie jest centrowany nad panelem od razu, krok w krok z klawiaturą (wcześniej dopiero ~0,3 s po jej ułożeniu).
- **Enter chowa klawiaturę** — w polach panelu edycji klawiatura pokazuje „Gotowe”, a Enter kończy edycję (wcześniej przechodził do następnego pola, np. wyszukiwania encji).
- **Chowanie klawiatury bez szarpania i mrugania** — zmiana wysokości okna wywołana klawiaturą w ogóle nie przelicza już planu (także w trakcie jej chowania, np. po stuknięciu obok pola); po schowaniu jest jedno, czyste wycentrowanie zaznaczonego elementu.

## 0.4.1-beta.286

- Telefon, **otwarta klawiatura**: panel edycji wjeżdża nad klawiaturę i zasłaniał zaznaczoną ikonę / pomieszczenie / marker. Teraz po otwarciu klawiatury (i przy każdej zmianie jej wysokości) zaznaczony element jest centrowany w miejscu, które zostaje między górnym paskiem a panelem.
- Wspólne liczenie wolnego miejsca nad panelem dla pomieszczeń, ikon i markerów (markery wcześniej stawały na stałej wysokości ekranu, niezależnie od wysokości panelu).

## 0.4.1-beta.285

- Telefon: **klawiatura nie rusza już planu**. Przy edycji pola tekstowego (np. nazwy) klawiatura zmniejszała wysokość okna, przez co plan był przeliczany — zmieniał się jego rozmiar i zoom, a na niższych telefonach był nawet uznawany za ustawiony poziomo (reset widoku). Na czas pisania plan zachowuje wysokość sprzed klawiatury.
- Po schowaniu klawiatury zaznaczony element (ikona, pomieszczenie, marker) jest ponownie centrowany nad panelem edycji.

## 0.4.1-beta.284

- **Płynna jazda kamery przy krawędzi** (markery, Flow, pomieszczenia, ikony, etykiety): kamera robiła krok tylko przy ruchu palca, więc gdy palec stał przy krawędzi — stawała, a ruszała przy najmniejszym drgnięciu („zamulanie”). Teraz jedzie sama, równo, dopóki palec jest w strefie krawędzi. W trakcie jazdy kamery nie działa przyciąganie do linii pomocniczych (wcześniej element „łapał się” linii innych pomieszczeń i szarpał); przyciąganie wraca, gdy znów prowadzisz palcem.
- **Centrowanie ikony po stuknięciu** — także ikony już zaznaczonej (wcześniej centrowała się tylko przy pierwszym zaznaczeniu, np. po przewinięciu planu i ponownym stuknięciu nic się nie działo). Centrowanie następuje po puszczeniu palca. To samo dla pomieszczeń: stuknięcie w już zaznaczone pomieszczenie ponownie je centruje.
- **Ramka zaznaczenia**: aktywna ikona (i etykieta zaznaczonego pomieszczenia) ma wyraźną niebieską przerywaną ramkę.

## 0.4.1-beta.283

Ikona (bez kształtu) w edycji działa teraz jak pomieszczenie:
- **Centrowanie na telefonie:** po stuknięciu ikona jest przybliżana i ustawiana na środku widocznego pola (między górnym paskiem a panelem edycji). Wcześniej zaraz po jej zaznaczeniu kliknięcie trafiało w plan i zaznaczało pomieszczenie leżące pod ikoną (z centrowaniem na nim).
- **Przesuwanie:** po przeciągnięciu ikona zapisuje swoje nowe miejsce (zamiast przesunięcia od starego punktu), więc centrowanie, linie pomocnicze, kopia i wyrównanie liczą się od miejsca, gdzie ikona naprawdę jest. Kamera jedzie za ikoną przy krawędzi widocznego pola, a po puszczeniu centruje ją nad panelem; ikona nie mruga w trakcie ruchu.
- **Wyrównanie do tła** (menu magnesu: do lewej / środka / prawej, góry / środka / dołu) działa też dla ikon.
- Poprawka ogólna: stuknięcie w etykietę pomieszczenia leżącą nad innym pomieszczeniem nie zaznacza już tego drugiego.

## 0.4.1-beta.282

- Koniec mrugania ikony **przesuwanego** pomieszczenia: gdy zmienia się tylko położenie etykiety (przesuwanie pomieszczenia albo samej etykiety / grupy), istniejące elementy dostają nowe położenie zamiast być tworzone od nowa — ikona nie jest przeładowywana w trakcie ruchu. Pełne przebudowanie następuje tylko przy zmianie wyglądu lub stanu.

## 0.4.1-beta.281

- Koniec mrugania ikon podczas przesuwania: etykiety (ikona, nazwa, stan) wszystkich pomieszczeń i ikon były budowane od nowa przy każdym ruchu — teraz każda ma własny kontener i jest przebudowywana tylko wtedy, gdy naprawdę się zmieniła. Etykiety innych pomieszczeń w trakcie przesuwania pozostają nietknięte.
- Strefa przy krawędzi, w której kamera zaczyna jechać za przeciąganym elementem, jest liczona od **widocznego pola planu** — pod górnym paskiem i, na telefonie, nad otwartym panelem edycji (marker, Flow, pomieszczenie) — a nie od całego ekranu. Wcześniej dolna strefa leżała pod panelem.

## 0.4.1-beta.280

- Przesuwanie pomieszczenia w edycji:
  - **bez mrugania** — na czas przesuwania efekt światła / stanu pomieszczenia jest ukryty (widać obrys i etykietę), po puszczeniu wraca płynnie. Wcześniej był budowany od nowa przy każdym ruchu i np. włączone pomieszczenie migało;
  - **kamera podąża** za pomieszczeniem przy krawędzi ekranu (jak przy markerach i etykietach), więc można je przeciągnąć poza widoczny obszar.

## 0.4.1-beta.279

- Telefon: po stuknięciu pomieszczenia w edycji kamera dopasowuje je teraz do **rzeczywistego wolnego miejsca** między górnym paskiem a panelem edycji (z małym marginesem), więc całe pomieszczenie jest widoczne. Wcześniej zakładała stałe ~42% wysokości ekranu, a na niższych ekranach (np. w aplikacji HA) panel zasłaniał dół wyższych pomieszczeń o ~30–40 px.

## 0.4.1-beta.278

- Poprawka (właściwa przyczyna): **„Szczegóły” (more info) nie otwierały się dla ikony** — i dla pomieszczenia — gdy jej encja nie miała na planie zwykłego markera. Okno szczegółów wymagało markera tej encji i bez niego po cichu nic nie robiło (zostawało tylko podświetlenie stuknięcia). Teraz otwiera się dla każdej encji: z nazwą, ikoną i stanem z Home Assistanta; w aplikacji HA otwiera się natywne okno HA.

## 0.4.1-beta.277

- Poprawka: stuknięcie w **ikonę** (nową, bez kształtu) na telefonie czasem nic nie robiło — np. „Szczegóły” (more info) się nie otwierały. Stuknięcie jest teraz rozpoznawane po dotknięciu i puszczeniu palca na samej ikonie, więc działa także wtedy, gdy telefon / aplikacja HA nie wyśle zwykłego kliknięcia. Jedno stuknięcie = jedna akcja (bez podwójnego przełączenia), a ikona leżąca na pomieszczeniu nie przełącza też pomieszczenia pod spodem.

## 0.4.1-beta.276

- Nowa ikona: po wyborze encji jest **trzeci krok „Co ma być widać?”** — trzy przyciski: **Ikona, Nazwa, Stan** (domyślnie wszystkie włączone, co najmniej jeden musi zostać). Licznik kroków 1/3 → 3/3, przycisk końcowy **„Utwórz ikonę”**; „Pomiń” zostawia wszystkie trzy.
- Ikona **powstaje dopiero po zakończeniu** popupu (wcześniej pojawiała się na planie od razu po kliknięciu „Ikona”). Esc kończy z tym, co już wybrane. Niedokończona ikona nie jest zapisywana.
- Limit rozmiaru **ikony, nazwy i stanu: 420 px** (wcześniej ikona 360 px, nazwa i stan 120 px) — w pomieszczeniach i ikonach.

## 0.4.1-beta.275

Szybsze i pewniejsze przełączanie ON/OFF:
- **Marker zmienia wygląd od razu** po stuknięciu (wcześniej czekał na odpowiedź Home Assistanta i potwierdzenie stanu — przy wolniejszym urządzeniu to było nawet 1–3 s). Jeśli HA zgłosi błąd, wygląd wraca do poprzedniego.
- **Koniec „martwych” stuknięć**:
  - po przesunięciu planu palcem na markerze zostawała flaga „przeciągnięto”, która połykała następne stuknięcie w ten marker — każde nowe dotknięcie zaczyna się teraz od czysta;
  - kolejne stuknięcie było ignorowane, dopóki trwało potwierdzanie stanu (do ~2–3 s) — teraz blokada trwa tylko na czas wysłania polecenia;
  - pomieszczenie przyjmowało kolejne stuknięcie dopiero ~0,7 s po odpowiedzi HA — teraz od razu po wysłaniu polecenia;
  - dłuższe stuknięcie w pomieszczenie (ponad 0,6 s) nie działało — limit podniesiony do 1,2 s (i 12 px ruchu).

## 0.4.1-beta.274

- Usunięty komunikat **„Dodaj pierwszą encję”** (z przyciskiem „Otwórz integracje”), który pokazywał się na nowym, pustym widoku po wybraniu tła. Elementy dodajesz przyciskiem **+** („Dodaj”) w górnym pasku. Ekran powitalny z wyborem tła zostaje bez zmian.

## 0.4.1-beta.273

- **Nowa „Ikona”** w oknie „Dodaj”: działa jak pomieszczenie, tylko bez rysowania kształtu.
  - Kliknięcie „Ikona” od razu stawia ją na środku widoku (albo w miejscu wskazanym na planie, gdy włączone „Wskaż miejsce na planie”) i otwiera ten sam mały popup: **Nazwa ikony** → **Encje ikony**. Pusta nazwa = nazwa pierwszej wybranej encji (bez encji: „Ikona N”).
  - Ma **te same opcje co pomieszczenie**: sekcje Ogólne, Grupa, Ikona, Nazwa, Stan (bez sekcji Wygląd, bo nie ma obszaru do podświetlenia). Domyślnie: grupa włączona, ikona z obrysem, tłem i ramką, nazwa i stan bez tła, rozmiar całości ×0,5.
  - W edycji przeciągasz ją palcem lub myszą; działa kopia, blokada, kopiuj/wklej styl, usuwanie.
  - W widoku stuknięcie działa jak w pomieszczeniu (przełącza encje albo otwiera szczegóły).
- Dotychczasowe ikony (markery) działają bez zmian; Badge, Gauge i Horseshoe dodaje się jak wcześniej.

## 0.4.1-beta.272

- Domyślny wygląd nowego pomieszczenia: grupa włączona, ikona bez zmian (obrys, tło, ramka), a **nazwa i stan domyślnie bez własnego tła** (stoją na wspólnym tle grupy). Cofnięte domyślne tła nazwy i stanu z 0.4.1-beta.271.

## 0.4.1-beta.271

- Nowe pomieszczenie: **nazwa i stan mają domyślnie tło** takie samo jak ikona (ten sam kolor i przezroczystość).
- Po popupie z wybranymi encjami panel pomieszczenia otwiera się ze **zwiniętymi sekcjami** (sekcja „Pomieszczenie” jest zwinięta). Gdy encje pominięto, sekcja „Pomieszczenie” dalej otwiera się z podpowiedzią.

## 0.4.1-beta.270

- Nowe pomieszczenie ma ikonę, nazwę i stan od razu w **trybie grupy** („Grupuj ikonę, nazwę i stan” włączone): wspólne tło i ramka grupy, ikona z obrysem, tłem i ramką.
- Grupa **dopasowuje się do narysowanego kształtu**: „Rozmiar całości” jest ustawiany tak, by grupa zajmowała najwyżej ~70% szerokości i ~60% wysokości pomieszczenia (od ×0,3 do domyślnego ×1 — w dużych pomieszczeniach nie rośnie ponad domyślny rozmiar). Dopasowanie liczy się po narysowaniu i ponownie po popupie (nazwa i stan zmieniają rozmiar). Potem możesz to zmienić suwakiem w sekcji Grupa.

## 0.4.1-beta.269

- Nowo narysowane pomieszczenie ma od razu widoczne **ikonę, nazwę i stan** w domyślnym układzie (jedno pod drugim, bez nachodzenia), z włączonymi opcjami: **obrys ikony, tło i ramka ikony, tło nazwy i stanu**. Wszystko można potem zmienić albo wyłączyć w sekcjach Ikona / Nazwa / Stan.
- Uniwersalne nazewnictwo encji pomieszczenia (to nie musi być światło — może to być włącznik, czujnik itd.):
  - krok 2 popupu: **„Encje pomieszczenia”** — „Zaznacz encje, od których zależy stan pomieszczenia — światło, włącznik, czujnik…”;
  - w panelu: „Zapalają je encje” → **„Encje pomieszczenia”**, podpowiedź też bez „zapalania”;
  - podpowiadane encje: najpierw z obszaru o tej samej nazwie (dowolny typ), potem światła, włączniki, czujniki binarne, rolety, klimat, media, zamki, odkurzacze.
  - Kafelek w oknie „Dodaj”: „Obszar ze stanem encji”.
- Poprawka: podczas rysowania pomieszczenia stuknięcie w etykietę innego pomieszczenia otwierało jego panel zamiast postawić punkt. Etykiety są teraz „przezroczyste” dla kliknięć w trakcie rysowania.

## 0.4.1-beta.268

- Po narysowaniu pomieszczenia pojawia się **mały popup w dwóch krokach**:
  1. **Nazwa** — pole od razu aktywne; zostaw puste, a pomieszczenie dostanie nazwę automatyczną (np. „Pomieszczenie 6”). Enter = Dalej.
  2. **Co zapala to pomieszczenie?** — lista encji z polami do zaznaczenia (można kilka). Na górze encje z obszaru o tej samej nazwie co pomieszczenie, potem światła; wyszukiwarka po nazwie, obszarze i entity_id. Wybrane widać jako chipy, przycisk „Gotowe (n)”.
- Każdy krok można pominąć („Pomiń”), Esc zamyka popup z tym, co już wpisane. Potem otwiera się panel pomieszczenia na sekcji „Pomieszczenie”.
- Na telefonie popup jest pod górnym paskiem, żeby klawiatura go nie zasłaniała.

## 0.4.1-beta.267

- Okno **„Dodaj”** ma teraz dwa kroki. Najpierw wybierasz tylko, **co** dodać (Ikona, Badge, Gauge, Horseshoe, Pomieszczenie, Flow, Tekst) — bez listy encji.
  - **Pomieszczenie** od razu przechodzi do rysowania.
  - **Tekst** i **Flow** dodają się od razu (encję Flow wybierasz potem w jego panelu).
  - Ikona, Badge, Gauge i Horseshoe przechodzą do drugiego kroku: wybór encji, z przyciskiem **„Zmień typ”**.
- Po narysowaniu pomieszczenia otwiera się jego panel z rozwiniętą sekcją **„Pomieszczenie”** i małą podpowiedzią, żeby wybrać encje, które je zapalają (na telefonie bez dymka, który zasłaniał wyszukiwarkę).

## 0.4.1-beta.266

- Sekcja „Etykieta” w edytorze pomieszczenia nazywa się teraz **„Grupa”** — mniej myląco, bo chodzi o połączenie ikony, nazwy i stanu w jeden element.
- Przełącznik „Wspólne tło” → **„Grupuj ikonę, nazwę i stan”**.
- W sekcjach Nazwa i Stan: „Przesunięcie w karcie” → **„Przesunięcie w grupie”**. Opisy zaktualizowane (PL i EN).

## 0.4.1-beta.265

- Włączenie „Wspólnego tła” nie wyłącza już osobnych teł ikony, nazwy i stanu — zostają takie, jak były ustawione.
- Wspólne tło (karta) ma teraz podsekcje: **Tło, Ramka, Wymiary, Położenie**.
  - **Tło** i **Ramka** mają przełącznik **„Zależne ON/OFF”**: kolor i przezroczystość (a dla ramki także grubość) osobno dla ON i OFF; tło ma też rozmycie.
  - Wymiary: zaokrąglenie, margines, odstęp, rozmiar całości. Położenie: lewo / prawo, góra / dół.
- Poprawka: karta zmieniała rozmiar, gdy ramka ikony (albo karty) miała inną grubość dla ON i OFF. Ramki ikony i karty są teraz rysowane do środka, więc grubość ramki nie zmienia rozmiaru — karta ma stały rozmiar przy każdym stanie.

## 0.4.1-beta.264

- Poprawka: zmniejszanie przezroczystości wypełnienia ikony etykiety zmieniało też obrys. Obrys ma teraz **własną przezroczystość** (podsekcja Obrys → „Przezrocz. obrysu”, a przy „Zależne ON/OFF” osobno ON i OFF) i nie zależy od wypełnienia. Cień ikony ma stałą siłę i sam dopasowuje się do tego, co jest widoczne.

## 0.4.1-beta.263

- Ikona etykiety: usunięte suwaki położenia (lewo / prawo, góra / dół i przesunięcie w karcie) — ikonę ustawia się przeciągając ją na planie.
- Poprawka: przezroczystość wypełnienia ikony robiła ikonę czarną, a wyłączenie wypełnienia dawało czarną ikonę. Przyczyną był cień tekstu, który rysował cały kształt ikony pod przezroczystym wypełnieniem. Teraz cień idzie za faktyczną przezroczystością: przezroczysta ikona jest przezroczysta, a bez wypełnienia widać tylko obrys (albo nic, gdy obrys też jest wyłączony).
- Pasek **Podgląd stanu ON / OFF** jest przypięty na górze edytora — zostaje widoczny przy przewijaniu w dół.
- Podsekcje działają jak akordeon: otwarcie jednej zamyka poprzednią. Po otwarciu sekcji (np. Ikona) wszystkie jej podsekcje są zwinięte. Zmiana ustawienia nadal nie zamyka otwartej podsekcji.
- Tło ikony: nowa opcja **„Rozmycie”** — rozmywa to, co jest pod tłem ikony.

## 0.4.1-beta.262

- Nowe pomieszczenie ma domyślnie większą etykietę: **ikona 120 px, nazwa 60 px, stan 50 px**, rozstawione jedno pod drugim tak, żeby na siebie nie nachodziły. „Przywróć domyślny” też wraca do tych wartości. Pomieszczenia, które miały już widoczną etykietę, zachowują dotychczasowy rozmiar i położenie.
- Ikona etykiety: w każdej podsekcji jest przełącznik **„Zależne ON/OFF”**:
  - **Wypełnienie** — włączony: kolor i przezroczystość ON / OFF; wyłączony: jeden kolor i jedna przezroczystość;
  - **Obrys** — kolor i grubość ON / OFF albo jedne wspólne;
  - **Tło** — kolor i przezroczystość ON / OFF albo jedne wspólne;
  - **Ramka** — kolor, przezroczystość i grubość ON / OFF albo jedne wspólne.
- Podgląd stanu ON / OFF w nagłówku edytora pokazuje te różnice od razu.

## 0.4.1-beta.261

### Ikona etykiety pomieszczenia
- **Źródło ikony** (3 przyciski z ikonami): **Z encji** — domyślnie, ikona taka, jak pokazuje ją Home Assistant dla pierwszej encji pomieszczenia (bez wymyślonych zamienników i bez zmiany przy ON/OFF, o ile sama encja jej nie zmienia); **Logo integracji**; **Własna ikona MDI** — tylko wtedy pojawia się pole do wpisania ikony i opcja „Ikona zależna ON/OFF” (osobna ikona ON i OFF).
- Sekcja Ikona jest podzielona na podsekcje: **Źródło, Wypełnienie, Obrys, Tło, Ramka, Kształt**. Otwarte podsekcje zostają otwarte po zmianie ustawień.
- Nowa **ramka ikony** (kolor, przezroczystość, grubość) obok tła ikony (kolor, przezroczystość). **Kształt** tła i ramki: **Kwadrat, Koło, Dowolny** — suwak zaokrąglenia pojawia się dopiero przy „Dowolny”; do tego margines wokół ikony.
- **Rozmiar ikony do 360 px** (wcześniej 120).
- Pomieszczenia z wpisaną wcześniej własną ikoną są automatycznie przestawiane na źródło „Własna ikona MDI”, więc nic się nie zmienia w ich wyglądzie.

### Wszędzie przyciski zamiast list rozwijanych
- W edytorach markerów, Flow i pomieszczeń krótkie listy wyboru (do 8 pozycji) są teraz rzędem przycisków — z ikoną, gdy pasuje (np. akcja dotknięcia, kierunek, kształt, efekt światła, typ animacji, źródło ikony, akcja linku), albo z krótkim tekstem (np. zaokrąglenie 0 / 1 / 2 / 3, czcionka). Nazwa opcji jest w podpowiedzi. Długie listy (np. ponad 8 widoków) zostają listą.

## 0.4.1-beta.260

- Etykieta → Wspólne tło: **Układ** to teraz 4 przyciski z samymi ikonami w jednym rzędzie, **Styl** — 5 próbek kolorów w jednym rzędzie, a **Wyrównanie** — 3 ikony (do lewej / do środka / do prawej) zamiast listy. Nazwa każdego przycisku jest w podpowiedzi.
- Poprawka: po zmianie czegoś w sekcji Ikona, Nazwa albo Stan edytor nie przeskakuje już na sekcję Etykieta — otwarta zostaje ta sekcja, w której była zmiana.
- Nagłówek edytorów (pomieszczenie, marker, Flow): przyciski (Przywróć domyślny, Blokada, Duplikuj, Kopiuj, Wklej, Usuń, Zamknij) są zawsze w jednym rzędzie pod tytułem, także na telefonie.
- Pod nimi nowy mały pasek **„Podgląd stanu” z przyciskami ON / OFF** — symuluje stan podczas ustawiania wyglądu (nie zmienia encji). Jest w edytorze pomieszczenia i markera i zastępuje dotychczasowe przyciski podglądu rozrzucone po sekcjach. W pomieszczeniu podgląd zmienia też tekst stanu w etykiecie.
- Włączenie „Wspólnego tła” wyłącza osobne tła ikony, nazwy i stanu (żeby nie było tła na tle); każde z nich można potem włączyć z powrotem.

## 0.4.1-beta.259

- Etykieta pomieszczenia → przełącznik **„Wspólne tło”**: ikona, nazwa i stan stają się jedną **kartą** ze wspólnym tłem (zamiast trzech osobnych elementów).
- **Gotowe układy** (przyciski z podglądem): **Jedno pod drugim**, **Obok siebie**, **Ikona z lewej** (nazwa nad stanem obok ikony), **Ikona z prawej**.
- **Gotowe style** jednym kliknięciem: **Bez tła**, **Ciemne**, **Jasne** (ciemny tekst), **Szkło** (półprzezroczyste tło z rozmyciem pod spodem i jasną ramką), **Kolor pokoju** (tło i ramka w kolorze światła pomieszczenia). Po wybraniu stylu wszystko da się dalej zmieniać ręcznie.
- Ustawienia karty: wyrównanie (do lewej / środka / prawej), tło (kolor, przezroczystość, rozmycie pod spodem), ramka (kolor, przezroczystość, grubość), zaokrąglenie, margines, odstęp między częściami, rozmiar całości oraz położenie lewo / prawo, góra / dół.
- **Wewnątrz karty**: w sekcjach Ikona, Nazwa i Stan każdą część można przesunąć w karcie („Przesunięcie w karcie: poziomo / pionowo”), a także zmienić jej rozmiar, kolor i własne tło.
- Kartę przeciąga się palcem / myszą w trybie edycji jako całość (z siatką i liniami pomocniczymi tylko tego pomieszczenia).
- Z wyłączonym „Wspólnym tłem” ikona, nazwa i stan działają jak dotąd — osobno, z osobnym położeniem. Przełączanie między trybami nie gubi ustawień żadnego z nich.

## 0.4.1-beta.258

### Etykieta pomieszczenia
- Nowa sekcja **„Etykieta”** z przełącznikiem **„Ikona, nazwa i stan jako jeden element”**. Włączony: przeciągnięcie dowolnej części przesuwa całą etykietę (części mają wtedy pomarańczową przerywaną ramkę). Wyłączony: każdą część przesuwasz osobno.
- **Linie pomocnicze przy przeciąganiu etykiety — tylko dla tego pomieszczenia:** krawędzie i środek jego obrysu, środek etykiety oraz pozostałe (nieprzesuwane) części jego etykiety. Działają jak przy markerach: pojawiają się, gdy ruch zwalnia, przyciągają, a włącza je przełącznik linii w menu magnesu. Siatka działa jak wcześniej.
- W trybie edycji części etykiety są nad markerami, więc zawsze da się je chwycić; w widoku zostają pod markerami.
- **Ikona — pełne ustawienia jak w Ikonie:** ikona zależna ON/OFF (osobna ikona ON i OFF), kolor ON / OFF, przezroczystość ON / OFF, wypełnienie, obrys (kolor i grubość), rozmiar, tło i położenie.
- Ikona, Nazwa i Stan: tło ma teraz także **kolor** (oprócz przezroczystości).

### Wygląd pomieszczenia — efekty światła
- Nowa opcja **„Efekt światła”** jak w tle Badge / Ikony: **Jednolity** (jak dotąd), **Centralny**, **Róg**, **Od ściany**, **Ambient**.
- Ustawienia: pozycja pozioma i pionowa (Centralny / Róg / Ambient), kierunek i pozycja na ścianie (Od ściany), **Rozproszenie** i **Wypełnienie**. Efekt działa z kolorem ON / OFF, intensywnością i miękkością krawędzi pomieszczenia, a przy włączaniu / wyłączaniu kolor zmienia się płynnie.
- Efekty światła i wszystkie nowe ustawienia etykiety są kopiowane razem ze stylem pomieszczenia.

## 0.4.1-beta.257

- Etykieta pomieszczenia jest teraz podzielona na trzy niezależne części: **ikonę, nazwę i stan**. W edytorze pomieszczenia każda ma własną sekcję („Ikona”, „Nazwa”, „Stan”) z ustawieniami:
  - Pokaż;
  - Ikona: własna ikona MDI albo automatyczna oraz kolor ON / OFF; Nazwa i Stan: kolor;
  - Rozmiar (px);
  - Tło (z przezroczystością) — dla ikony okrągłe, dla tekstu zaokrąglony prostokąt;
  - Lewo / prawo, Góra / dół (px od środka pomieszczenia).
- **Przeciąganie palcem / myszą:** w trybie edycji każdą część etykiety można złapać i przesunąć na planie (części są wtedy oznaczone przerywaną ramką). Przeciąganie zaznacza pomieszczenie, trzyma się siatki, gdy siatka jest włączona, kamera podąża przy krawędzi ekranu, a po puszczeniu (telefon) element jest wyśrodkowany nad edytorem. Suwaki położenia w edytorze odświeżają się po puszczeniu.
- Ustawienia z bety 256 (wspólny kolor, rozmiar, układ pionowy / poziomy, przesunięcie i tło) są automatycznie przeliczane na trzy części, więc etykiety stoją tam, gdzie stały.
- Ustawienia wszystkich trzech części są kopiowane razem ze stylem pomieszczenia.

## 0.4.1-beta.256

- Pomieszczenie → nowa sekcja **„Etykieta”**: ikona, nazwa i stan rysowane na środku pomieszczenia, jako jego część (nie osobny marker).
  - **Pokaż ikonę** — automatyczna z encji (np. żarówka zapalona / zgaszona, gniazdko, wentylator) albo własna ikona MDI z listy; osobny kolor ON i OFF.
  - **Pokaż nazwę** — nazwa pomieszczenia.
  - **Pokaż stan** — jedna lampa: „Wł. · 80%” (z jasnością) albo „Wył.”; kilka świateł / przełączników: „Wł. 2/3”; czujnik: wartość z jednostką.
  - Kolor tekstu, **tło etykiety** z przezroczystością, układ **pionowy / poziomy**, **rozmiar** oraz przesunięcie **lewo / prawo** i **góra / dół** od środka pomieszczenia.
- Etykieta stoi w środku ciężkości kształtu pomieszczenia, skaluje się razem z planem, zmienia się na żywo razem ze stanem encji i ma przejście koloru przy włączaniu / wyłączaniu.
- Dotknięcie etykiety działa jak dotknięcie pomieszczenia (np. przełącza światło). Etykieta jest widoczna także w podglądzie sąsiedniego widoku przy przesuwaniu palcem.
- Ustawienia etykiety są kopiowane razem ze stylem pomieszczenia („Kopiuj styl” / „Wklej styl”). Domyślnie etykieta jest wyłączona, więc istniejące pomieszczenia wyglądają jak dotąd.

## 0.4.1-beta.255

- Edycja pomieszczenia: usunięty czerwony przycisk × przy zaznaczonym narożniku. Narożnik usuwa się podwójnym dotknięciem / dwuklikiem, a na komputerze także klawiszem Delete / Backspace po zaznaczeniu albo prawym przyciskiem myszy.
- Wskaźniki kątów przy narożnikach zaznaczonego pomieszczenia i pomieszczenia w trakcie rysowania (także dla linii do kursora):
  - **kąt prosty (90°)** — mały zielony kwadracik w rogu, jak na rysunku technicznym;
  - **45° i 135°** — zielony łuk z etykietą „45°” / „135°”.
- Kąty są liczone na planie w pikselach (z uwzględnieniem proporcji tła), z tolerancją ±1,5°. Znaczniki zmieniają się na żywo przy przeciąganiu narożnika i mają stały rozmiar niezależnie od powiększenia.

## 0.4.1-beta.254

- Poprawka (telefon): podwójne dotknięcie narożnika pomieszczenia usuwa narożnik, ale przeglądarka zamieniała te dwa dotknięcia także w „podwójne kliknięcie” na planie, które przełącza powiększenie. Widok wracał wtedy do 100% i trzeba było wychodzić z edycji. Teraz podwójne dotknięcie uchwytu pomieszczenia nie zmienia powiększenia ani położenia widoku.
- To samo przy rysowaniu nowego pomieszczenia: szybkie stawianie kolejnych narożników nie przełącza już powiększenia.

## 0.4.1-beta.253

- Menu magnesu → Linie pomocnicze: nowy przełącznik **„Tylko elementy widoczne na ekranie”** (ikona oka, domyślnie włączony). Przesuwany marker, Flow albo pomieszczenie przyciąga się wtedy tylko do markerów, Flow i pomieszczeń widocznych na ekranie, a nie do elementów z całego planu. Najbardziej pomaga na telefonie przy powiększeniu. Gdy kamera przesuwa się za elementem, lista celów odświeża się z nowym widokiem. Wyłączenie przywraca przyciąganie do wszystkich elementów.
- Linie pomocnicze są cieńsze: ok. 0,8 px na ekranie niezależnie od powiększenia (wcześniej na powiększonym widoku telefonu miały ok. 2 px) i bez ciemnej obwódki, tylko z delikatną poświatą.

## 0.4.1-beta.252

- Kamera przy krawędzi jedzie wolniej i łagodniej: maksymalna prędkość jest mniej więcej o połowę mniejsza, rośnie łagodnie z głębokością wejścia w strefę przy krawędzi i rozpędza się stopniowo przez ok. 0,8 s, zamiast od razu ruszać pełną prędkością.
- Linie pomocnicze przy wielu markerach migają dużo mniej:
  - przy szybkim przeciąganiu element niczego nie łapie i nie pokazuje linii — linie pojawiają się dopiero, gdy ruch zwalnia przy linii (czyli kiedy faktycznie celujesz);
  - złapana linia „trzyma” element, dopóki nie odsuniesz go wyraźnie dalej, więc linia nie miga na granicy;
  - gdy szybko przeciągniesz i zatrzymasz się dokładnie na linii, pojawia się ona po ok. 0,1 s bezruchu.
- Dotyczy markerów, Flow i przesuwania całych pomieszczeń. W teście szybkiego przeciągania przez plan linie świeciły w 3 klatkach z 60 zamiast w 54.

## 0.4.1-beta.251

- Przesuwanie markera albo Flow w trybie edycji: kamera podąża za elementem. Gdy palec (albo kursor) zbliży się do krawędzi widoku, plan płynnie przesuwa się w tę stronę, a element razem z nim. Im bliżej krawędzi, tym szybciej. Nie trzeba już puszczać elementu i ręcznie przesuwać ekranu.
- Telefon: po puszczeniu kamera płynnie centruje przesunięty element w widocznej części planu nad edytorem, więc okienko edytora go nie zasłania.
- Pozycja przeciąganego elementu jest teraz liczona względem miejsca, w którym palec trzyma go na planie, więc zostaje pod palcem także wtedy, gdy kamera się przesuwa.

## 0.4.1-beta.250

### Nowe okno „Dodaj do widoku”
- W trybie edycji w pasku górnym jest nowy przycisk **„+”**, obok magnesu. To samo okno otwiera „Dodaj” w menu ołówka. Osobne pozycje „Pomieszczenie”, „Flow” i „Tekst / przycisk” z menu ołówka trafiły do tego okna.
- U góry są kafelki: **Ikona, Badge, Gauge, Horseshoe, Pomieszczenie, Flow, Tekst / przycisk**. Każdy ma miniaturę narysowaną prawdziwym markerem na tle w stylu planu.
- Pod kafelkami jest wyszukiwarka **wszystkich encji Home Assistanta**, także tych bez integracji (sensory szablonowe, encje z YAML). Szuka po nazwie, `entity_id`, obszarze i integracji. Każde słowo zawęża wynik, np. „salon lampa”.
- Filtry: Wszystkie, Ostatnie (ostatnio dodane na tym urządzeniu) i **obszary z Home Assistanta**. Przycisk po prawej przełącza na grupowanie po typach: Światła, Przełączniki, Czujniki, Czujniki binarne, Rolety, Klimat, Media, Inne.
- Przy każdej encji widać jej stan oraz dopisek „na widoku: Ikona, Pomieszczenie…”, jeśli już jest użyta na tym widoku.
- Kolejność jest dowolna:
  - **Najpierw encja:** miniatury przerysowują się z jej prawdziwym stanem, pasujący typ dostaje etykietę **★ Polecane** i jest od razu wybrany, a typy niepasujące są wyszarzone (Gauge, Horseshoe i Flow wymagają wartości liczbowej).
  - **Najpierw typ:** dla Gauge, Horseshoe i Flow lista pokazuje tylko encje liczbowe.
- Pomieszczenie, Flow i Tekst / przycisk można dodać bez encji. Pomieszczenie z encją od razu przechodzi w rysowanie narożników, dostaje tę encję oraz nazwę jej obszaru (np. „Kuchnia”).
- Przycisk na dole mówi, co się stanie, np. „Dodaj: Ikona”. Ikona światła, gniazdka lub przełącznika dostaje od razu akcję „Przełącz”.
- Przełącznik **„Wskaż miejsce na planie”** (zapamiętywany): po dodaniu dotykasz plan w miejscu, gdzie ma stanąć element. Bez niego element pojawia się na środku widocznej części planu. Esc anuluje.
- Po dodaniu element jest zaznaczony, a jego edytor otwarty.
- Na telefonie okno wysuwa się od dołu, a kafelki są w dwóch kolumnach.

### Ta sama encja wiele razy
- Każdy marker ma teraz własny identyfikator, a encja jest jego ustawieniem. Na jednym widoku może być np. Ikona i Badge tej samej lampy albo kilka Ikon tej samej encji.
- Wszystkie markery tej encji odświeżają się na żywo, przełączanie działa z każdego z nich, a usunięcie jednego zostawia pozostałe.
- Nowy przycisk **„Duplikuj marker”** w nagłówku edytora markera robi kopię z całym wyglądem obok oryginału. Tekst / przycisk dostaje przy tym własny identyfikator.

### Migracja układu i kopia zapasowa
- Układ przechodzi automatycznie na wersję 3 przy pierwszym wczytaniu. Istniejące markery zachowują dotychczasowe identyfikatory, więc nic się nie przesuwa ani nie znika.
- Przed pierwszym zapisem w wersji 3 serwer zapisuje jednorazowo kopię poprzedniego układu jako `rewrite_state_beta.v2-backup.json` (w `/config/ha_views`).

### Serwer
- Nowe zapytanie `api/entity_catalog`: wszystkie encje z nazwą, obszarem (własnym lub urządzenia), integracją, stanem i jednostką w jednej odpowiedzi. Encje wyłączone są pomijane. Gdy HA nie odpowie, okno korzysta z dotychczasowej listy encji z integracji.

## 0.4.1-beta.249

- Poprawka: przycisk magnesu (Przyciąganie i siatka) znowu działa jak przełącznik — pierwsze kliknięcie otwiera menu, drugie je zamyka. Wcześniej dotknięcie przycisku najpierw zamykało menu jako „kliknięcie obok”, a zaraz potem otwierało je ponownie, więc nie dało się go schować tym samym przyciskiem.

## 0.4.1-beta.248

- Rysowanie pomieszczenia na telefonie: pasek z podpowiedzią jest teraz niski i jednowierszowy. „Cofnij punkt” i „Anuluj” mają same ikony, a podpowiedź zajmuje najwyżej dwie małe linie, więc pasek nie zawija się już w wysokie okienko zasłaniające plan.
- Pasek sam ustępuje miejsca: po postawieniu narożnika w dolnej części ekranu przeskakuje pod górny pasek, a po postawieniu narożnika w górnej części wraca na dół. Na komputerze działa tak samo przy ruchu myszy.
- Dotknięcie wolnego miejsca na pasku (poza przyciskami) przenosi go na drugą krawędź ekranu.

## 0.4.1-beta.247

- Nowy suwak „Oba wymiary” (ikona łańcucha) nad suwakami szerokości i wysokości. Zmienia oba wymiary naraz z zachowaniem proporcji, a obok pokazuje rozmiar „szer.×wys.”. Jest w:
  - Ikona: Rozmiar → Szerokość / Wysokość,
  - Badge, Gauge, Horseshoe i Tekst / przycisk: Rozmiar → Szerokość / Wysokość,
  - Flow: Ramka i pozycja → Długość ramki / Szerokość ramki.
- Suwak ma skalę logarytmiczną, więc małe elementy da się ustawić równie dokładnie jak duże. Proporcję wyznaczają aktualne suwaki szerokości i wysokości — po zmianie jednego z nich suwak „Oba wymiary” od razu przyjmuje nową proporcję. Zakres jest ograniczony tak, by żaden z wymiarów nie wyszedł poza swoje granice.
- Przy zablokowanej geometrii suwak jest wyłączony, tak jak suwaki szerokości i wysokości.

## 0.4.1-beta.246

- Poprawka: po przejściu na widok ze ściemnionym tłem (ściemnianie wg słońca lub ustawiona jasność tła) przez chwilę było widać tło w normalnej jasności, które dopiero potem ciemniało. Jasność i odcień nowego widoku są teraz ustawiane od razu, jeszcze przed pokazaniem obrazu i bez przejścia. Płynne przejście (2,5 s) zostaje tylko wtedy, gdy na żywo zmienia się wysokość słońca.
- Podgląd sąsiedniego widoku przy przesuwaniu palcem pokazuje teraz także chłodny odcień nocy, więc nie różni się od widoku po puszczeniu.

## 0.4.1-beta.245

- Widok → Tło → Tło nocne: nowa opcja „Ściemniaj tło wg słońca” dla widoków z jednym tłem (bez obrazu nocnego). Tło płynnie ciemnieje o zmierzchu i rozjaśnia się o świcie według wysokości słońca (atrybut `elevation` encji `sun.sun` lub encji ustawionej w polu „Przełącza encja”).
- Regulowany zakres: „Zaczyna ściemniać, gdy słońce na” (domyślnie 6°) i „Pełna noc, gdy słońce na” (domyślnie −6°). Przesunięcie jednego suwaka za drugi przesuwa także ten drugi.
- „Jasność w nocy” (10–100%, domyślnie 45%) i opcjonalny „Chłodny odcień nocą” (lekko niebieski, mniej nasycony obraz; domyślnie włączony).
- Przyciski Auto / Zawsze dzień / Zawsze noc działają także dla ściemniania. Encja bez atrybutu `elevation` przełącza od razu między dniem a pełnym ściemnieniem.
- Zmiana na żywo przechodzi płynnie (2,5 s). Markery, pomieszczenia i Flow nie są ściemniane. Pod ustawieniami widać bieżący stan, np. „Ściemnienie: 50% · słońce −3.0°”.

## 0.4.1-beta.244

- Naprawa panelu bocznego z 243: zasłaniał rozwijane menu górnego paska (menu edycji z „Pomieszczenie / Flow / Tekst”, menu magnesu), więc nie dało się w nie kliknąć. Menu otwierają się teraz nad panelem.

## 0.4.1-beta.243

- Komputer, tryb edycji: edytory markera, Flow i pomieszczenia otwierają się w stałym panelu przy prawej krawędzi ekranu zamiast unosić się przy elemencie. Scena w trybie edycji zwęża się o szerokość panelu, więc panel nigdy nie zasłania edytowanego elementu. Gdy nic nie jest zaznaczone, panel pokazuje krótką podpowiedź.
- Przycisk w nagłówku panelu przenosi go na lewą stronę i z powrotem (zapamiętywane na danym urządzeniu).
- Telefon bez zmian — edytor dalej wysuwa się od dołu.

## 0.4.1-beta.242

- Pomieszczenia — nowy, pewny sposób usuwania narożników (PC i telefon):
  - kliknięcie / stuknięcie narożnika zaznacza go (czerwona obwódka), a obok pojawia się czerwony przycisk **×**, który go usuwa;
  - na komputerze zaznaczony narożnik usuwa też klawisz **Delete** / **Backspace**;
  - **prawy przycisk myszy** na narożniku usuwa go od razu, bez menu kontekstowego przeglądarki;
  - szybki dwuklik / podwójne stuknięcie nadal działa.
- Pomieszczenie musi mieć co najmniej 3 narożniki.

## 0.4.1-beta.241

- Pomieszczenia: narożnik usuwa się podwójnym stuknięciem (telefon) albo dwuklikiem (komputer). Od bety 222 nie działało to nigdzie, bo narożnik przekazuje palec/kursor scenie, żeby płynnie się przesuwał, a wtedy przeglądarka nie wysyła dwukliku do kropki. Edytor pomieszczenia zostaje otwarty po usunięciu narożnika.
- Kropki narożników są mniejsze i mają stały rozmiar na ekranie niezależnie od przybliżenia (wcześniej na telefonie po przybliżeniu rosły nawet do ok. 50 px). Obszar dotyku wokół nich pozostał duży.

## 0.4.1-beta.240

- Tło nocne: przy wejściu na widok, gdy jest noc (przesunięciem palcem, zakładką albo przy starcie), nie widać już przez chwilę tła dziennego. Obraz nocny pokazuje się od razu, a przełączenie czeka, aż będzie gotowy. Płynne przenikanie zostało tylko dla zmiany dzień ↔ noc na otwartym widoku.
- Okno szczegółów po angielsku: „Last changed” z datą w formacie angielskim oraz „7 days”.

## 0.4.1-beta.239

- Tryb podglądu (użytkownik HA bez uprawnień administratora) może teraz przełączać światła i gniazdka, tak jak ustawił administrator. Działa dotknięcie markera z akcją „Przełącz ON/OFF” oraz pomieszczenia (lub jego ikony) z tą akcją. Serwer pozwala takiemu użytkownikowi przełączać wyłącznie encje ustawione na widoku z tą akcją, nic innego w Home Assistant. Edycja nadal jest zablokowana.
- Naprawa: nazwa ostatniego widoku na pasku zakładek była ucinana (widoczne w trybie podglądu, szczególnie w Firefoksie). Pasek zakładek zajmuje tyle miejsca, ile potrzebuje, a przewija się dopiero, gdy naprawdę się nie mieści.

## 0.4.1-beta.238

- Nowy element **Tekst / przycisk** (menu edycji). Nie jest powiązany z żadną encją.
  - Służy do napisów, etykiet i opisów na planie, zmienianych bez ruszania obrazu tła, oraz do przycisków nawigacji.
  - Ma pełny styl Badge albo Ikony: tekst, podpis, ikona, tło, ramka, obrót, linie pomocnicze.
  - „Dotknięcie w widoku”: Brak akcji, Przejdź do widoku (HA Views), Otwórz stronę Home Assistant (np. `/lovelace/energy`, `/config/areas`) albo Otwórz link (http/https, opcjonalnie w nowej karcie). Działa też w trybie podglądu.
- **Link do widoku**:
  - adres HA Views z `?view=<nazwa widoku>` (np. `…/app/<slug>?view=parter`) otwiera od razu ten widok. Działa z zakładki w przeglądarce, z bezpośredniego linku i z akcji „navigate” w innych dashboardach HA;
  - w menu widoku → Opcje jest „Kopiuj link do widoku”.

## 0.4.1-beta.237

- Przygotowanie wydania stabilnego 0.5.0: beta i wersja stabilna mają teraz ten sam kod, różniący się jednym ustawieniem kanału. Każda wersja zapisuje swój plik układu. „Pliki tła” chronią tła drugiej wersji i podają, której (w becie „Stabilna”, w wersji stabilnej „Beta”). Dla bety nic się nie zmienia.

## 0.4.1-beta.236

- Jasność tła: w menu Tło jest suwak jasności osobno dla obrazu dziennego i nocnego (30–200%, przycisk przywraca 100%). Zmiana działa na żywo i zapisuje się dla widoku. To filtr na samym obrazie tła, więc markery, Flow i animacje nie zwalniają, a przy 100% nie ma żadnego filtra. Podgląd przy przesuwaniu między widokami też ma ustawioną jasność.

## 0.4.1-beta.235

- Nowe menu widoku, dopasowane do telefonu (dolny panel) i PC (rozwijane okno):
  - główna strona: 4 ikony w rzędzie (Dodaj widok, Zmień nazwę, Duplikuj, Ustaw jako startowy) oraz dwa kafelki: „Tło” i „Opcje”. Strzałki przesuwania widoku usunięte, bo kolejność zmienia się przeciąganiem nazw;
  - „Tło” ma trzy strefy. **Obraz**: wybór tła i 4 ikony (Wgraj, Pobierz, Zmień nazwę pliku, Pliki tła). **Tło nocne**: wybór obrazu i 4 ikony (Wgraj, Auto, Zawsze dzień, Zawsze noc) oraz encja. **Kolor**: kolor z palety, formaty 16:9 / 4:3 / 1:1 / 3:4 / 9:16 / 21:9, własny rozmiar (szerokość × wysokość) i ustawianie rozmiaru kółkami na ekranie;
  - „Opcje”: przełączanie palcem, domyślny panel Home Assistant, Usuń widok;
  - „Diagnostyka przesuwania” usunięta.
- Tło w kolorze mieści się teraz w całości na ekranie w wybranym formacie, tak samo jak obraz.
- „Pliki tła”: miniatury pokazują cały obraz (pion i poziom). Przy każdym pliku: ustaw jako tło widoku, ustaw jako tło nocne, zmień nazwę, pobierz, usuń. Usuwanie tła jest tylko tutaj. Zamknięcie okna wraca do menu Tło zamiast zamykać menu.
- Zmiana nazwy pliku tła (zachowuje rozszerzenie i poprawia odwołania we wszystkich widokach bety). Nazwa zajęta = komunikat. Tło wersji stabilnej wymaga potwierdzenia.

## 0.4.1-beta.234

- „Pliki tła”: tło używane przez stabilną wersję HA Views można teraz usunąć (pomarańczowy kosz). Najpierw pojawia się ostrzeżenie z nazwami widoków stabilnej wersji, które zostaną bez tła, i przycisk „Usuń mimo to”. „Usuń nieużywane” nadal nie rusza takich plików.

## 0.4.1-beta.233

- Tło nocne: zamiast podglądu Dzień / Noc jest tryb zapisywany dla widoku: „Auto” (wg encji), „Zawsze dzień”, „Zawsze noc”.
- Nowe okno „Pliki tła” (w panelu Tło): lista wszystkich wgranych obrazów z miniaturą, rozmiarem i miejscem użycia (widok · dzień / noc, wersja stabilna). Pojedyncze pliki można usuwać, a „Usuń nieużywane” czyści wszystkie nieużyte naraz. Pliki używane przez stabilną wersję HA Views (wspólny folder) są zablokowane, serwer też odmawia ich usunięcia.
- Wgrywane tło zachowuje oryginalną nazwę pliku (z polskimi znakami i spacjami), bez dopisywania cyferek. Gdy nazwa jest zajęta, dopisuje się „(2)”, „(3)”…, więc istniejący plik nigdy nie jest nadpisywany.

## 0.4.1-beta.232

- Tło nocne dla widoku (opcjonalne). W „Zarządzaj widokiem → Tło” jest nowa sekcja „Tło nocne”: wybierz obraz z listy albo wgraj nowy. Obraz nocny powinien mieć ten sam rozmiar co dzienny, bo leży dokładnie na nim, a markery, Flow i pomieszczenia zostają na swoich miejscach.
- Tło przełącza się samo i płynnie przenika. Domyślnie decyduje `sun.sun` (noc = `below_horizon`). W polu „Przełącza encja” można podać inną encję, np. `input_boolean.noc` albo `binary_sensor.…`: noc, gdy ma stan `on`.
- Przyciski „Dzień” / „Noc” pokazują podgląd bez czekania na zachód słońca. Podgląd znika po wyjściu z trybu edycji albo po zmianie widoku.

## 0.4.1-beta.231

- Pomieszczenia: w sekcji „Wygląd” jest „Kolor zależny ON/OFF”, tak jak w markerach. Po zaznaczeniu pojawiają się „Kolor ON”, „Kolor OFF”, „Intensywność ON” i „Intensywność OFF”, więc wyłączone pomieszczenie może mieć własny kolor zamiast znikać. Podgląd ON/OFF pokazuje oba stany, a kopiuj / wklej styl przenosi też te ustawienia.
- Bez zaznaczenia wszystko działa jak dotąd (wyłączone pomieszczenie jest niewidoczne).

## 0.4.1-beta.230

- Linie przyciągania działają tak samo dla markerów, Flow i pomieszczeń. Przeciągany element przyciąga się do wszystkich pomieszczeń na widoku (krawędzie, środek i narożniki nieregularnych ścian), a nie tylko do tego, w którym stał na początku przeciągania.
- Przesuwane pomieszczenie przyciąga się do markerów, Flow, innych pomieszczeń i tła, z liniami pomocniczymi.
- Przeciągane narożniki pomieszczenia (i rysowanie nowego) przyciągają się też do markerów, Flow i tła, z liniami pomocniczymi.

## 0.4.1-beta.229

- Obrót markerów i Flow. W menu magnesu jest nowa grupa „Obróć zaznaczony”: ikonki obracają o 90° i 15° w lewo / prawo, ikonka przywracania ustawia 0°, a suwak obraca płynnie co 1° (−180…180°).
- W edytorze markera w sekcji „Rozmiar” jest suwak „Obrót”. W Flow dotychczasowa „Korekta obrotu” nazywa się teraz „Obrót” i jest tą samą wartością co w menu.
- Zablokowana geometria blokuje też obrót. Istniejące widoki wyglądają bez zmian.

## 0.4.1-beta.228

- Badge, Ikona, Gauge i Podkowa: tekst „Nazwa” i „Stan” można przesuwać także w lewo / prawo. Suwaki nazywają się teraz „Lewo / prawo” i „Góra / dół”, tak jak w sekcji Ikona. Istniejące widoki wyglądają bez zmian.

## 0.4.1-beta.227

- Kopiuj / wklej styl markera przenosi też wybór ikony (źródło, własna ikona MDI, ikony ON/OFF) oraz „Dotknięcie w widoku”. Jeśli skopiowana akcja to „Przełącz ON/OFF”, a docelowej encji nie da się przełączyć, ustawia się „Więcej informacji”.

## 0.4.1-beta.226

- Flow: „Ostrość” strzałek do 300% (było do 100%). Powyżej 100% szpic jest głębszy niż długość strzałki i wychodzi poza jej pole (nie jest obcinany) — rozmiar ramki, odstęp i liczba się nie zmieniają.

## 0.4.1-beta.225

- Nowe menu „Przyciąganie i siatka” (ikona magnesu obok ołówka, widoczna w trybie edycji), przeniesione z menu edycji i rozbudowane, na ikonach:
  - Siatka (z rozmiarem S/M/L) i Granice tła.
  - Linie pomocnicze włącz/wyłącz.
  - Przyciągaj do: markerów, Flow, pomieszczeń, tła (środek i krawędzie tła — zielone linie).
  - Punkty: środki i/lub krawędzie elementów.
  - Wyrównaj zaznaczony element (marker, Flow, pomieszczenie) do tła: do lewej/prawej/górnej/dolnej krawędzi albo wyśrodkuj w poziomie/pionie.
- Flow dodaje się teraz jak pomieszczenie: menu edycji → „Flow”. Może być bez encji; encję wybiera się (albo zmienia/usuwa) w popupie Flow, w sekcji „Encja i kierunek”, wyszukiwarką. Przyciski dodawania Flow zniknęły z Integracji.

## 0.4.1-beta.224

- Tryb edycji: przerywane linie elementów, których akurat nie edytujesz, też mają kolor swojego rodzaju — obrysy pomieszczeń bursztynowe, ramki ukrytych Flow (i zablokowanych) fioletowe; słabsze niż przy zaznaczeniu.

## 0.4.1-beta.223

- Kolory zaznaczenia w trybie edycji zależne od rodzaju elementu: marker — niebieski, Flow — fioletowy, pomieszczenie — bursztynowy (ramka i uchwyty).
- Podgląd stanu to teraz dwa przyciski ON i OFF (zamiast listy) — w markerach i pomieszczeniach; ponowne kliknięcie aktywnego wraca do stanu rzeczywistego.
- Wyjście z trybu edycji: podgląd wraca do stanu rzeczywistego, a widok do pełnego (zoom 100%).
- Pomieszczenie: w sekcji encji tylko dodane encje i wyszukiwarka (bez listy podpowiedzi z widoku).
- Popupy bez podpowiedzi i komentarzy (na razie ukryte).

## 0.4.1-beta.222

- Telefon: narożniki pomieszczeń dają się złapać palcem i płynnie przesuwać. Uchwyt był przerysowywany przy każdym ruchu, przez co telefon gubił palec; teraz palec trzyma scena. Większy obszar dotyku kropek.
- Popup pomieszczenia uproszczony: zostały sekcje „Pomieszczenie” i „Wygląd” (podgląd, kolor, intensywność, miękkość krawędzi). Usunięte: sekcje „Kształt” i „Ikona”, kolor i jasność ze światła, mieszanie (poświata zawsze „rozjaśnia”). Istniejące ikony pomieszczeń działają dalej jak zwykłe markery.
- Linie pomocnicze pomieszczeń: przeciągany marker, Flow lub ikona wewnątrz pomieszczenia przyciąga się też do środka i krawędzi tego pomieszczenia — te linie są bursztynowe, żeby odróżnić je od niebieskich (względem innych elementów).

## 0.4.1-beta.221

- Flow: odstęp może być ujemny — strzałki wsuwają się jedna w drugą, więc da się je ułożyć dużo gęściej (do 2 px między kolejnymi). Działa w każdej animacji i przy zmianie rozmiaru uchwytami.
- Flow: animacja „Przepływ” dwa razy szybsza przy tym samym tempie — 1× = 150 px/s (było 75 px/s).

## 0.4.1-beta.220

- Flow, animacja „Przepływ”: tempo to teraz stała prędkość strzałek (1× = 75 px/s). Nie zależy od liczby, długości strzałki, odstępu ani rozmiaru ramki — zmiana liczby nie zwalnia/nie przyspiesza animacji, a dwa Flow z tym samym tempem (np. dla tej samej encji, o różnej szerokości) jadą identycznie. Uwaga: Flow o niestandardowych rozmiarach mogą jechać trochę inaczej niż wcześniej — wystarczy poprawić Tempo.
- W sekcji Animacja nowy przycisk „Ustaw tę animację w pozostałych Flow tej encji (N)” — kopiuje typ, tempo i tempo od wartości do innych Flow tej samej encji.
- Edytor Flow uporządkowany: „Ramka i pozycja” (długość ramki, szerokość ramki, korekta obrotu) oraz „Strzałki” (rodzaj, ostrość, grubość, długość strzałki, odstęp, liczba). W animacji „Przepływ” suwak liczby jest ukryty, bo strzałki i tak wypełniają całą ramkę.

## 0.4.1-beta.219

- Nowa opcja w menu edycji: „Granice tła” (domyślnie włączona). Marker i Flow nie dają się wyciągnąć poza tło — cały element (nie tylko jego środek) zatrzymuje się na krawędzi obrazu przy przeciąganiu i przy zmianie rozmiaru. Pomieszczenia i tak nie mogą wyjść poza tło. Wyłączenie opcji przywraca swobodne przesuwanie.

## 0.4.1-beta.218

- Telefon, tryb edycji: przy przeciąganiu markera (gdy popup chowa się na czas ruchu) pod tłem nie widać już ramki karty — karta sceny w trybie edycji na telefonie nie ma obramowania, tła ani cienia, więc odsłonięty pas to zwykłe tło aplikacji.

## 0.4.1-beta.217

- Telefon, tryb edycji: widok nie wyjeżdża już poza dolną krawędź tła, pokazując pustą ramkę. Przesunięcie poza tło jest dozwolone tylko o tyle, ile zasłania popup na dole — puste miejsce zawsze chowa się pod popupem, a marker/Flow/pomieszczenie nisko na tle nadal ląduje nad popupem. Po zamknięciu popupu widok wraca do krawędzi tła.

## 0.4.1-beta.216

- Telefon, tryb edycji: kliknięcie pomieszczenia centruje je i przybliża tak jak marker i Flow — całe pomieszczenie mieści się nad popupem (małe są przybliżane, duże zostają w całości widoczne).

## 0.4.1-beta.215

- Naprawa dla dużych instalacji HA: lista integracji/encji nie ładowała się z błędem „Błąd encji: Received message 258: WebSocketError(MESSAGE_TOO_BIG) … exceeds limit 4194304”. Rejestry encji/urządzeń większe niż 4 MB przekraczały domyślny limit wiadomości WebSocket w serwerze dodatku; limit podniesiony do 128 MB.

## 0.4.1-beta.214

- Cofnięto zmianę z 0.4.1-beta.213 (ukrywanie paska Home Assistant nad widokiem na telefonie i własny przycisk ☰) — nie działała w aplikacji HA. Pasek HA jest znów widoczny jak wcześniej.

## 0.4.1-beta.213

- Telefon: HA Views chowa biały pasek Home Assistant („☰ HA Views Beta”) nad widokiem i zajmuje jego miejsce. Boczne menu HA otwiera się teraz przyciskiem ☰ po lewej stronie górnego paska HA Views. Można to wyłączyć w menu widoku: „Ukryj pasek Home Assistant nad widokiem (telefon)” (ustawienie na urządzenie, domyślnie włączone).

## 0.4.1-beta.212

- Ikona pomieszczenia: w popupie pomieszczenia nowa sekcja „Ikona” → „Dodaj ikonę”. Ikona to zwykły marker typu Ikona z pełnym edytorem (kolory ON/OFF, obrys, tło, ramka, rozmiar, kolory wg wartości, kopiuj/wklej styl, blokada), przeciąganiem i liniami pomocniczymi. Pojawia się na środku pomieszczenia.
  - Świeci (stan ON), gdy pomieszczenie jest zapalone — czyli gdy dowolna z jego encji jest włączona; domyślnie ikona „grupa świateł” / „grupa świateł zgaszona”.
  - Dotknięcie ikony wykonuje akcję pomieszczenia (Przełącz ON/OFF przełącza wszystkie jego światła/gniazdka, Więcej informacji, Brak akcji).
  - Zmiana nazwy pomieszczenia zmienia nazwę ikony; usunięcie pomieszczenia usuwa też ikonę. „Edytuj ikonę” / „Usuń ikonę” w tej samej sekcji.

## 0.4.1-beta.211

- Integracje mają własny przycisk w górnym pasku (ikona puzzla obok ołówka) zamiast pozycji w menu edycji; ponowne kliknięcie wraca do widoku.
- „Dodane do widoku” podzielone na grupy: Markery, Flow i Pomieszczenia (z licznikami). Każdy element ma „Pokaż” (przechodzi do widoku, włącza edycję i otwiera jego popup) oraz „Usuń z widoku” z potwierdzeniem.

## 0.4.1-beta.210

- Pomieszczenia: usunięty efekt „Zapalony obraz” — zostaje tylko poświata kolorem (pomieszczenia ustawione wcześniej na obraz świecą teraz kolorem).
- Naprawa „Mieszanie”: tryby nie działały (warstwa pomieszczeń mieszała się tylko sama ze sobą, nie z planem). Teraz Rozjaśnij / Miękkie światło / Nakładka / Zwykłe dają wyraźnie różny efekt, a pod wyborem jest opis, co robi wybrany tryb.
- Otwarcie popupu markera lub Flow zamyka popup pomieszczenia.
- Kliknięcie ikon w nagłówku popupu pomieszczenia nie blokuje już jego ustawiania obok pomieszczenia.

## 0.4.1-beta.209

- Siatka w trybie edycji jest dużo rzadsza i delikatniejsza (linie co 10%) — precyzyjne wyrównanie robią teraz linie pomocnicze. Przyciąganie do siatki działa jak wcześniej.
- Blokada geometrii przeniesiona na górę każdego popupu (marker, Flow, pomieszczenie) jako kłódka obok „Ustaw domyślny”.
- Badge / ikona: podgląd stanu ON/OFF jest teraz w każdej sekcji, której wygląd zależy od stanu (Encja, Stan, Ikona, Tło, Ramka) jako „Podgląd: Rzeczywisty stan / Włączony / Wyłączony” zamiast przycisku u góry.
- Popup pomieszczenia jak pozostałe: sekcje domyślnie zwinięte, ten sam nagłówek (Ustaw domyślny, Blokada, Duplikuj, Kopiuj styl, Wklej styl, Usuń, Zamknij).
- Encje pomieszczenia: lista dodanych encji na górze (z usuwaniem) i dynamiczna wyszukiwarka wszystkich encji HA jak w Integracjach; bez wpisywania podpowiada encje z bieżącego widoku.
- „Podgląd” w pomieszczeniu też ma trzy stany: Rzeczywisty stan / Włączony / Wyłączony.

## 0.4.1-beta.208

- Naprawa „Domyślny panel Home Assistant”: w nowym HA panele dodatków mają adres /app/<slug>, a 207 zapisywało „app” zamiast nazwy panelu HA Views, przez co HA po starcie kręcił kółkiem. Panel jest teraz brany z listy paneli HA (panel dodatku, config.addon), a nie z adresu; gdy nie da się go ustalić, opcja jest ukryta.
- Automatyczna naprawa: jeśli w koncie zapisany jest domyślny panel, który nie istnieje, HA Views usuwa go przy otwarciu.

## 0.4.1-beta.207

- „Domyślny panel Home Assistant” w menu widoku (zamiast przełącznika z 206): Bez zmian / HA Views — moje konto / HA Views — tylko to urządzenie. „Moje konto” zapisuje HA Views jako Panel w preferencjach użytkownika HA (to samo ustawienie co Profil → Panel, działa na wszystkich urządzeniach tego konta), choć lista HA pokazuje tylko dashboardy. „Bez zmian” przywraca Auto (ustawienia systemowe).

## 0.4.1-beta.206

- Nowa opcja w menu widoku: „Otwieraj HA Views po starcie Home Assistant (to urządzenie)”. Ustawia HA Views jako stronę startową HA na tym urządzeniu (przeglądarka / aplikacja HA), czego nie da się wybrać w ustawieniach HA, bo lista pokazuje tylko dashboardy. Gdy w HA jest ustawiony domyślny dashboard użytkownika lub systemu (ma pierwszeństwo), aplikacja o tym ostrzega.

## 0.4.1-beta.205

- „Dotknięcie w widoku” ujednolicone dla markerów i pomieszczeń: te same nazwy i kolejność — Więcej informacji / Przełącz ON/OFF / Brak akcji. „Przełącz ON/OFF” pojawia się tylko tam, gdzie jest co przełączyć.
- Markery: nowa opcja „Brak akcji” (dotknięcie nic nie robi). Wybór akcji jest teraz dostępny dla każdego markera, także czujników (Więcej informacji / Brak akcji).

## 0.4.1-beta.204

- Pomieszczenia: dotknięcie pomieszczenia w widoku przełącza jego światła/gniazdka (gdy któreś świeci — gasi wszystkie, inaczej zapala). Zmiana jest widoczna od razu, bez czekania na HA. W ustawieniach pomieszczenia „Dotknięcie w widoku”: Przełącz światło / Więcej informacji / Nic.
- Widok, który ma tylko pomieszczenia (bez markerów), nie pokazuje już komunikatu „Dodaj pierwszą encję” zasłaniającego plan.

## 0.4.1-beta.203

- Nowość: pomieszczenia. W trybie edycji menu → „Pomieszczenie”: klikasz kolejne narożniki (dowolny kształt — L, schody, skosy), zamykasz klikając pierwszy punkt albo „Gotowe”. Narożniki przyciągają się do ścian innych pomieszczeń i do siatki (Alt wyłącza).
  - Pomieszczenie świeci, gdy włączona jest dowolna z wybranych encji (światło, gniazdko, ruch, drzwi…); płynnie się zapala i gaśnie.
  - Efekt „Poświata kolorem”: kolor (lub kolor ze światła RGB), intensywność, jasność ze światła, miękkość krawędzi, tryb mieszania (Rozjaśnij / Miękkie światło / Nakładka / Zwykłe).
  - Efekt „Zapalony obraz”: odsłania w kształcie pomieszczenia drugą wersję planu (np. render z włączonymi światłami) wgraną jako tło.
  - Edycja kształtu: przeciąganie narożników, dodawanie punktu na krawędzi, dwuklik usuwa narożnik, przeciągnięcie wnętrza przesuwa całe pomieszczenie. „Podgląd włączonego” pokazuje efekt w edycji.
  - Pomieszczenia są też widoczne w podglądzie przy przesuwaniu palcem między widokami.

## 0.4.1-beta.202

- Linie pomocnicze przy przeciąganiu w trybie edycji: marker lub Flow przyciąga się do krawędzi i środków innych elementów widoku (próg 6 px), a niebieska linia pokazuje wyrównanie. Na komputerze przytrzymanie Alt wyłącza przyciąganie.
- Nowa sekcja markera „Kolory wg wartości” (opcjonalna): dwa progi dzielą wartość na trzy zakresy z własnym kolorem, opcjonalnie płynne przejście. Można kolorować ikonę, wartość, tło, ramkę i łuk Gauge/Podkowy oraz ustawić osobną ikonę dla każdego zakresu. Kopiuj/wklej styl przenosi też te ustawienia.

## 0.4.1-beta.201

- Naprawa losowego zatrzymywania przesuwania między widokami. Przyczyna (z diagnostyki): aktualizacja stanu z HA przebudowywała marker pod palcem, a przeglądarka wysyłała resztę dotyku do usuniętego elementu — strona nie widziała już ruchu ani puszczenia palca.
  - Podczas gestu markery i Flow nie są przebudowywane; zaległe aktualizacje rysują się zaraz po puszczeniu palca.
  - Po starcie przesuwania gest jest przechwytywany przez scenę, więc nie zależy od elementu, na którym zaczął się dotyk.

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
