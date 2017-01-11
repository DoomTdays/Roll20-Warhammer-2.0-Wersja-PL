# Roll20 - Warhammer-2.0 - Wersja-PL
Tłumaczenie kart postaci do platformy Roll20.

Są to przetłumaczone karty postaci przeznaczone do użytku na platformię roll20. 
Orginalną wersję angielską kart można znaleźć pod tym linkiem: https://github.com/Roll20/roll20-character-sheets/tree/master/Warhammer-Fantasy-Roleplay-2nd-Edition

<b>Instalacja Kart Postaci</b>

1. Aby móc zainstalować kartę postaci na swojej sesji, osoba zakładając sesję musi posiadać konto Premium (5$ - koszt miesięczny) albo Pro(10$ - koszt miesięczny). 
2a. W przypadku nowych sesji należy. Założyc nową sesję i w opcji "Optional: Choose a Character Sheet", wybrać "Custom".
2b. Jeżeli chcemy dodać karty postaci do instniejącej już sesji należy. Wejśc w opcję sesji a nastepnie w opcji "Character Sheet Template" wybrać "Custom".
3. Niezależnie czy w punkcie 2 wybraliśmy opcję a czy b dalsze kroki są takie same. 
4. Otwieramy opcję naszej sesji i następnie do zakładki HTML kopiujemy zwartość HTML-Warhammer2.0-PL
5. Następnie przechodzimy do sekcji CSS i wklejamy tam zawartość CSS-Warhammer2.0-PL
6. I gotowe możemy już bez problemu korzystać z naszych kart postaci. Nawet po utracie statusu Premium lub Pro karty pozostaną na naszej sesji.


<b>Instalacja Makr (Opcjonalne)</b>


1. Kod do makr znajduje się już w kodzie źródłowym tak więc nie musicie juz zajmować się bebechami a wszystko możecie już bezpośrednio zrobic na stronie swojej sesji.
2. Niestety każdy gracz uczestniczący w sesji musi samodzielnie wkleic makra. Nie jest to jednak trudne ale polecam zamieści na swojej sesji handout zawierający instrukcję instalacji makr.
3. Po wejści do sesji wchodzimy w zakładkę "Collection" (czwarta z kolei zakładka, po prawej stronie).
4. Otworzy nam się zakładka o nazwie "Macros".
5. Klikamy na przycisk "+ Add".
6. Otworzy na się edytor Makr.
7. Wpisujemy nazwę (Program nie uwzględnia spacji w nazwie zamiast tego stosuje "-" jako spację), na przykład: Rzut-Kostką-100 albo po prostu 100, nie ma to większego znaczenia.
8. W polu akcji wklejamy jedno z poniższych makr.
9. W polu Actions zmieniamy tylko {{character_name=Puste}} na {{character_name=Nazwa Mojej Postaci}} gdzie wyrażenie Nazwa Mojej Postaci zamieniamy na imię swojej postaci.
10. Klikamy przycisk "Save Changes".
11. Na zakładce "macros" pojawi się nasze nowe makro. Należy zaznaczyć opcję "In Bar" (Każdorazowo przy dodawaniu makr) oraz zaznaczyć hitboxa "Show macro quick bar?" (Wystarczy raz, Roll20 zapamięta nasze ustawienia.
12. I to wszystko. Od tego momentu wygodnie możecie dokonywać rzutów przy pomocy jednego przycisku.


<b>Lista dostępnych makr:</b>


Możecie stworzyć swoją własna kostkę zmieniając tylko dwa parametry Title -wpisując wartość kostki oraz DiceRollTest - określając jakiego rzutu ma dokonać system, np 2d20. Pamiętacie aby przypadkiem nie usunąć żadnego z nawiasów bo makro przestanie działać.


<b>Rzut Kostką 100.</b>

&{template:whfrp2e} {{title=100}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d100]]}}

<b>Rzut Kostką 20.</b>

&{template:whfrp2e} {{title=20}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d20]]}}

<b>Rzut Kostką 12.</b>

&{template:whfrp2e} {{title=12}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d12]]}}

<b>Rzut Kostką 10.</b>

&{template:whfrp2e} {{title=10}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d10]]}}

<b>Rzut Kostką 8.</b>

&{template:whfrp2e} {{title=8}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d8]]}}

<b>Rzut Kostką 6.</b>

&{template:whfrp2e} {{title=6}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d6]]}}

<b>Rzut Kostką 4.</b>

&{template:whfrp2e} {{title=4}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d6]]}}

<b>Rzut Kostką 20 dwa razy.</b>

&{template:whfrp2e} {{title=2k20}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d20]]}}

<b>Rzut Kostką 15 dwa razy.</b>

&{template:whfrp2e} {{title=2k15}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d15]]}}

<b>Rzut Kostką 12 dwa razy.</b>

&{template:whfrp2e} {{title=2k12}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d12]]}}

<b>Rzut Kostką 10 dwa razy.</b>

&{template:whfrp2e} {{title=2k10}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d10]]}}

<b>Rzut Kostką 8 dwa razy.</b>

&{template:whfrp2e} {{title=2k8}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d8]]}}

<b>Rzut Kostką 6 dwa razy.</b>

&{template:whfrp2e} {{title=2k6}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d6]]}}

<b>Rzut Kostką 4 dwa razy.</b>

&{template:whfrp2e} {{title=2k4}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d4]]}}

<b>Pomniejsza Manifestacja Chaosu - Makro przydatne dla postaci czarujących</b>

&{template:whfrp2e} {{title=Pomniejsza }} {{character_name=Nazwa Mojej Postaci}} {{ChaosManifestation=Manifestacja Chaosu}} {{MinorChaosManifestation=[[1d100]]}}"

<b>Poważna Manifestacja Chaos - Makro przydatne dla postaci czarujących</b> 

&{template:whfrp2e} {{title=Poważna}} {{character_name=Tzeentch - Pan Przemiany}} {{ChaosManifestation=Manifestacja Chaosu}} {{MajorChaosManifestation=[[1d100]]}}"

<b>Katastrofalna MAnifestacja Chaosu - Makro przydatne dla postaci czarujących</b>

&{template:whfrp2e} {{title=Katastrofalna}} {{character_name=Tzeentch - Pan Przemiany}} {{ChaosManifestation=Manifestacja Chaosu}} {{DisastrousChaosManifestation=[[1d100]]}}"


Z pewnością pojawią się nowe makra.

<b>Lista Zmian</b>

1.0

1.Kart postaci w całości przetłumaczone

2.Dodano podstawowe makra

