&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

# Praca semstralna Cykl Życia i narzędzia DevOps
### Dr inż Mirosław Bobrowski
&nbsp;

##### Wykonalli: 
- Filip Borowy
- Mikołaj Liszka
- Bartosz Łukaszek
- Jakub Mizera
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

# Spis treści
- [[#Zespół]]]
- [[#CELE]]
- [[#Wizja]]
- [[#Wymagania niefunkcjonalne]]
- [[#Wymagania niefunkcjonalne]]
- [[#User stories]]
- 


## Temat pracy: Edytor tekstu markdown
#### Grupa lab 3

## Zespół
- Mikołaj Liszka 13569
- Filip Borowy 12956
- Bartosz Łukaszek 13468
- Jakub Mizera 13544

Wersja | Treść zmiany | Miejsce zmiany | Wprowadził | Obowiązuje od
---|---|---|---|---
1.0 | Określenie SMART1 | Cele | M. Bobrowski | 22-03-2022

#### CELE
Celem naszej aplikacji jest utworzenie aplikacji z notatkami, która jest jak najbardziej minimalistyczna i przejrzysta, a zarazem pełna różnorodnych opcji pomagających stworzyć użytkownikowi jak najbardziej trafną notatkę. Nasz zespół składa się z osób, które lubią sobie pomagać oraz korzystają z rad od każdego, aby aplikacja, którą kreują była jak najbardziej przyjazna użytkownikowi.

#### Wizja
Produkt ma służyć użytkownikom technicznym/zorientowanym na produktywność do wykonywania efektywnej pracy dokumentacyjnej, planowania, tworzenia notatek ma wspomóc między innymi produktywność developerów, project managerów, devops specialistów

## Wymagnia funkcjonalne
1.  Edycja tekstu
2.  Headings
3.  Lists (bulleted, numbered, togglable)
4.  Code blocks with syntax highlighting 
5.  Checkboxes
6.  Tables
7.  Quotes
8.  Visual dividers (jak hr tag w htmlu    
9.  Indeksowanie zapisków i szybkie ich przeszukiwanie (system Tagów)
10.  Minimal but beautiful ui and user experience
11.  Kategoryzacja danych i tworzenie własnych kategorii, możliwe dodanie emotek i tytułu kategorii
12.  Słownik
13.  Zabezpieczenia notatek hasłem, szyfrowanie notatek
14.  Tłumaczenie słów na tekst
15.  Czytanie tekstu pisanego (TTS)
16.  language detection -> tłumaczenie na wykryty język
17.  User friendly command system
18.  Custom emojis
19.  For texts saved with tag notes or similar create a checkbox for REVIEWED
20.  Nie działanie na urządzeniach apple
21.  Dark and light mode
22.  Przełożenie obrazka na słowa
23.  Zmiana czcionek na zaakceptowane przez nasz zespół
24.  Embedding np. google calendar czy inne gówno które można embedować bish idk
25.  Vcs
26.  Pliki w cloud
27.  Edytowanie plików PDF
28.  Spotlight page -> spełnia takie same warunki jak obsidian publish
29.  Permisje plików (private, readonly, public, team edit ?!?)
30.  Tagi dla notatek
31.  Multiple users live editing
32.  Ease of use helpers (high contrast view, dyslexia specific font, colorblind mode)
33.  File stats i.e num of characters, num of words
34.  Read time
35.  Focus mode
36.  Export to word, pdf, html
37.  Print
38.  Canvas for drawing or handwriting
39.  Embedding images, sound files
40.  User profiles
41.  Settings changes saved per profile

## Wymagania niefunkcjonalne
1. Działanie aplikacji powinno być szybkie, płynne, nie posiadać zacięć, nawet jeśli aplikacja straci połączenie z siecią lub jakimś zasobem, powinna w spokojny sposób zatrzymać animację i wyświetlić komunikat
2.  Aplikacja powinna być intuicyjna i łatwa w użytku już od pierwszego kontaktu użytkownika, nie znaczy to że użytkownik musi korzystać ze wszystkich zaawansowanych opcji, jednak powinien być w stanie sporządzić notatkę z łatwością 
3.  Dostępność aplikacji przez 24h/7dni/cały rok  
4.  Sposób zgłaszania błędów i ułatwienie użytkownikowi ich rozwiązania  
5.  Aplikacja powinna być bezpieczna dla użytkownika, zasoby użytkownika powinny być szyfrowane  
6.  Aplikacja powinna posiadać swojego rodzaju tutorial, który pokazałby użytkownikowi wszelkie funkcje aplikacji  
7.  Dostępność apki na innych systemach   
8.  Kompatybilność z innymi aplikacjami

# User stories 
Story *Id* | As a ``type of user`` | I want to `perform some task` |So that `I can achieve some goal`| isDone 
--|--|--|--
4 | *user* (programmer) | be able to add *code blocks* to my notes | take notes of code from my classes
9 | user | index my notes | Find my related notes quickly
12 | user | easily correct my grammatical errors | write sentences without grammatical errors  
