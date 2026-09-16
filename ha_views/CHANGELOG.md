# Changelog

## 0.3.0-beta.56

- marker positions remain exact when entering or leaving Edit mode on desktop and mobile;
- added a global 40–250% Scale slider in Size for Badge and Gauge;
- replaced the grid-size slider with three compact Small / Medium / Large buttons.


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
