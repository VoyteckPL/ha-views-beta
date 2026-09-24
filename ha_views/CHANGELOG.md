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
