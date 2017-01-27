<font size="5">Warhammer Druga Edycja
Tłumaczenie Kart Postaci na Platformę Roll20</font>

Są to przetłumaczone karty postaci przeznaczone do użytku na platformie Roll20. Tłumaczenie jest kompletnie darmowe i można je swobodnie rozpowszechniać. Proszę tylko o wzmiankę o autorstwie tłumaczenia oraz niepobierania jakichkolwiek opłat za rozpowszechnianie tłumaczenie. Możecie swobodnie modyfikować kod źródłowy, jeżeli umiecie posługiwać się językiem tajemnym HTML oraz CSS. Jeżeli masz jakieś pytanie na temat kart postaci albo propozycję proszę o kontakt ze mną po przez e-maila. Może uda mi się Ci pomóc. E-mail znajduje się na końcu dokumentu.

Oryginalną wersja Kart Postaci: https://github.com/Roll20/roll20-character-sheets/tree/master/Warhammer-Fantasy-Roleplay-2nd-Edition
Tłumaczenie Kart Postaci: https://github.com/DoomTdays/Roll20-Warhammer-2.0-Wersja-PL

Uwaga! Aby moc używać przetłumaczonych kart postaci należy koniecznie posiadać konto Pro lub Premium na platformie Roll20. Konto takie musi posiadać osoba, która założyła sesje reszta graczy może posiadać konto darmowe. 

<b>Instalacja Kart Postaci</b>

Instalacja kart postaci jest niezwykle prosta i szybka. Nie powinna zająć ci więcej niż 3-5 minuty. Poniżej wstawiam krótką instrukcję, która z pewnością ułatwi wam sprawę.

1.	Otwieramy stronę Roll20 i w zależności od tego czy mamy już założona sesje czy też nie postępujemy według opcji A albo B.
a)	W przypadku nowych sesji należy. Założyć nową sesję i w opcji Optional: Choose a Character Sheet, wybrać Custom.
b)	Jeżeli chcemy dodać karty postaci do istniejącej już sesji należy. Wejść w opcję sesji a następnie w opcji Character Sheet Template wybrać Custom.
2.	Niezależnie czy w punkcie pierwszym wybraliśmy opcję A czy B  dalsze kroki są takie same.
3.	Otwieramy opcję naszej sesji i przechodzimy do zakładki HTML. Kopiujemy tam zwartość HTML-Warhammer2.0-PL z podanego linku, gdzie znajduje się tłumaczenie.
4.	Następnie przechodzimy do sekcji CSS. Kopiujemy tam zwartość CSS-Warhammer2.0-PL z podanego linku, gdzie znajduje się tłumaczenie.
5.	I gotowe możemy już bez problemu korzystać z naszych kart postaci. Nawet po utracie statusu Premium lub Pro karty pozostaną na naszej sesji. Zachęcam jednak do dalszego opłacania konta, gdyż wspierasz tym samy twórców platformy i pozwalasz im ją rozwijać.

<b>Instalacja Makr – Opcjonalne</b>

Pamiętaj, że makra będą działać tylko jeżeli poprawnie zainstalujesz Karty Postaci. Cały kod źródłowy znajduje się właśnie tam i bez tego makra nie będą funkcjonować.

1.	Kod do makr znajduje się już w kodzie źródłowym, tak więc nie musicie już zajmować się bebechami a wszystko możecie już bezpośrednio zrobić na stronie swojej sesji.
2.	Niestety każdy gracz uczestniczący w sesji musi samodzielnie wkleić makra. Nie jest to jednak trudne, ale polecam zamieści na swojej sesji handout zawierający instrukcję instalacji makr.
3.	Po wejściu do sesji wchodzimy w zakładkę Collection (czwarta z kolei zakładka, po prawej stronie).
4.	Otworzy nam się zakładka o nazwie Macros.
5.	Klikamy na przycisk + Add.
6.	Otworzy na się edytor Makr.
7.	Wpisujemy nazwę ( program nie uwzględnia spacji w nazwie zamiast tego stosuje  "-" jako spację ). Na przykład: Rzut-Kostką-100 albo po prostu 100, nie ma to większego znaczenia, gdyż nazwę widzicie wyłącznie Wy.
8.	W polu akcji wklejamy jedno z poniższych makr.
9.	W polu Actions zmieniamy tylko znajdujące się w rubryce {{character_name=”Nazwa Mojej Postaci”}}, ”Nazwa Mojej Postaci” na rzeczywistą nazwę naszej postaci jaką gramy w sesji. Klikamy przycisk Save Changes.
10.	Na zakładce Macros pojawi się nasze nowe makro. Należy zaznaczyć opcję In Bar  ( Każdorazowo przy dodawaniu makr ) oraz zaznaczyć hitbox’a Show macro quick bar?  ( Wystarczy raz, Roll20 zapamięta nasze ustawienia ).
11.	I to wszystko. Od tego momentu wygodnie możecie dokonywać rzutów przy pomocy jednego przycisku.

<b>Lista dostępnych makr:</b>

Możecie stworzyć swoją własną kostkę zmieniając tylko dwa parametry Title - wpisując wartość kostki oraz DiceRollTest - określając jakiego rzutu ma dokonać system, np. 2d20. Pamiętajcie aby przypadkiem nie usunąć żadnego z nawiasów, bo makro przestanie działać.
Dla waszej wygody zamieszczam jednak listę wszystkich najprzydatniejszych makr. Wystarczy je tylko przekopiować zgodnie z powyższą instrukcją.

<b>Rzut Kostką 100 – 1k100.</b>

&{template:whfrp2e} {{title=100}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d100]]}}

<b>Rzut Kostką 20 – 1k20.</b>

&{template:whfrp2e} {{title=20}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d20]]}}

<b>Rzut Kostką 12 – 1k12.</b>

&{template:whfrp2e} {{title=12}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d12]]}} 

<b>Rzut Kostką 10 – 1k10.</b>

&{template:whfrp2e} {{title=10}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d10]]}}

<b>Rzut Kostką 8 – 1k8.</b>

&{template:whfrp2e} {{title=8}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d8]]}}

<b>Rzut Kostką 6 – 1k6.</b>

&{template:whfrp2e} {{title=6}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d6]]}}

<b>Rzut Kostką 4 – 1k4.</b>

&{template:whfrp2e} {{title=4}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[1d6]]}}

<b>Rzut Kostką 20 dwa razy – 2k20.</b>

&{template:whfrp2e} {{title=2k20}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d20]]}}

<b>Rzut Kostką 15 dwa razy – 2k15.</b>

&{template:whfrp2e} {{title=2k15}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d15]]}}

<b>Rzut Kostką 12 dwa razy – 2k12.</b>

&{template:whfrp2e} {{title=2k12}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d12]]}}

<b>Rzut Kostką 10 dwa razy – 2k10.</b>

&{template:whfrp2e} {{title=2k10}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d10]]}}

<b>Rzut Kostką 8 dwa razy – 2k8.</b>

&{template:whfrp2e} {{title=2k8}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d8]]}}

<b>Rzut Kostką 6 dwa razy – 2k6.</b>

&{template:whfrp2e} {{title=2k6}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d6]]}}

<b>Rzut Kostką 4 dwa razy – 2k4.</b>

&{template:whfrp2e} {{title=2k4}} {{character_name=Nazwa Mojej Postaci}} {{DiceRollTest=[[2d4]]}}

<b>Pomniejsza Manifestacja Chaosu - Makro przydatne dla postaci czarujących</b>

&{template:whfrp2e} {{title=Pomniejsza }} {{character_name=Nazwa Mojej Postaci}} {{ChaosManifestation=Manifestacja Chaosu}} {{MinorChaosManifestation=[[1d100]]}}"

<b>Poważna Manifestacja Chaos - Makro przydatne dla postaci czarujących</b>

&{template:whfrp2e} {{title=Poważna}} {{character_name=Tzeentch - Pan Przemiany}} {{ChaosManifestation=Manifestacja Chaosu}} {{MajorChaosManifestation=[[1d100]]}}"

<b>Katastrofalna Manifestacja Chaosu - Makro przydatne dla postaci czarujących</b>

&{template:whfrp2e} {{title=Katastrofalna}} {{character_name=Tzeentch - Pan Przemiany}} {{ChaosManifestation=Manifestacja Chaosu}} {{DisastrousChaosManifestation=[[1d100]]}}"

<b>Lista Zmian oraz Plany</b>

<b>Wersja - 1.0 - 11.01.2017</b>

1.	Kart postaci w całości przetłumaczone.
2.	Dodano przycisk do rzutów na obrażenia przy zaklęciach. 
3.	Dodano rubrykę Pochodzenie i Rodzina w zakładce Historia.
4.	Dodano makra do rzutów kościami oraz Manifestacji Chaosu.

<b>Wersja - 1.1 - 11.01.2017 - Plany</b>

1.	Dodać następujące makra:

	Trafienia Krytyczne
	Śmierdzący Ochlapus
	Choroby Umysłowe
	Leczenie Obłędu
	Efekty nieudanej operacji
	Medykamenty

2.	Poprawić parę błędów w tłumaczeniu.
3. Rozdział na wersję podstawową oraz wersję roszerzoną.

<b>Kontakt oraz Post Scriptum</b>

Autor Tłumaczenia Kart Postaci: Doom_days
Kontakt: Devil.doom.days@gmail.com

Jeżeli wyłapiesz jakiś błąd w kartach bądź wpadniesz na ciekawy pomysł, który chciałbyś zaimplementować nie omieszkaj dać mi znać o tym po przez e-maila. 

<b>Podziękowania</b>

Baniakowi, za udostępnienie publicznie kart postaci. Link do kanału na YouTube: http://www.youtube.com/baniakbaniaka

Społeczność polskiej frakcji graczy „The Winged Hussars” skupiającej się wokół gry Elite: Dangerous za pokazania platformy Roll.20, wciągnięcie w RPG oraz wspólną rozgrywkę.

Oraz wszystkim, którzy w jakimiś stopni przyczynili się do tłumaczenia niniejszych kart postaci.

