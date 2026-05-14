---
Title:vid
---

- Have a thesis
- Learn the context
- Unearth all the details

## Intro

TLDR. Nie jestem fizjoterapełtą ale długo siedzę w temacie budowy ergonomycznych
klawiatur i dam consensus community tego jak zbudować najwygodniejszą klawiaturę
dla więkrzości osób. # TODO: Rephrase

## Materiały

### PCB vs No PCB

TODO:

### Obudowa

Chara corder, Ręka Klawiatura : TODO

Najważniejszą decyzją podczas budowy kawiatury będzie obudowa którą wybierzemy.\
Na podstawie tej decyzji będziemy wybierać wszystkie inne komponenty.

#### FORMAT

Najpierw musimy zadecydować czy chcemy klawiaturę w klasycznym formacie czy
rozdzieloną na dwie połówki. Osobiście jestem zwolennikiem podzielonej
konstrukcji ponieważ jest o wiele bardziej wygodna - możemy położyć klawiaturę w
idealnej pozycji dla naszych ramion i nadgarstków. Jeżeli umiesz dobrze touch
type-ować to nie poczujesz rzadnej różnicy jeżeli chodzi o pisanie.

#### Ile switch-y

Następnie musimy zadecydować ile switch-ów chcemy zamątować na klawiatórze. Im
mniej switchów tym mniej nasze ręce będą musiały się ruszać podczas pisania co
sprawi że:

- Będziemy popełniać mniej błędów: Palce pozostają zawsze na bazowej
  pozycji(home row) lub są oddalone o mały dystans od niej co zmniejsza szanse,
  że się pomylimy i w ciśniemy nie ten przycisk który chcieliśmy.
- Pisanie będzie bardziej ergonomiczne: Nie musimy sięgać do oddalonych
  przycisków.

Jednak mniejsza ilość przycisków wiąże się z koniecznościom nauki bardziej
skomplikowanych ustawień klawiatruy, między innymi:

- Kilka warstw: zwykły, symbole, liczby, etc.
- Przyciski które po przytrzymaniu lub kilkukrotnym pełnią inną funkcję- zmiana
  warstwy czy modyfikator(shift, ctlr,alt).

#### Layout

Ułożenie klawyszy to temat rzeka. Każda osoba będzie preferowała inny styl
klawiatury.

Pierwszą decyzją będzie ułożenie kolumn:

- Klasyczny(skośny):
- Ortoliniowy/Prosty/whatever: Bardziej ergonomyczny, najczęściej spotykany w
  ergonomicznych klawiaturach. Przeżucenie się na niego nie jest takie ciężkie.

https://spacehop.com/ortholinear-keyboard/
https://akkogear.eu/blogs/news/ortholinear-keyboards

##### Thumb cluster

Jeżeli chcesz bardziej ergonomiczną klawiatórę to bardzo polecam design-y które
posiadają wyodrębnione przyciski dla kciuków- np. corne Kciuk jest
najsilniejszym z naszych palców a standardowy layout klawiatury marnuje jego
potencjał na samą spację. Ja osobiście jestem zwolennikiem 3 dedykowanych
przycisków na kciuk

#### Tilt

Kiedy trzymasz dłonie ustawione płasko do stołu, to mięśnie w twoich rękach są
pod stałym napięciem. Dlatego coraz bardziej popularne stają się kierownice do
rowerów szosowych/gravelów które mają tak zwaną flarę.

https://bikepacking.com/wp-content/uploads/2020/01/gravel-drop-bars-geometry-diagram-1.png

Jeżeli chcesz zbudować klawiatórę podzieloną to polecam pomyśleć nad wybraniem
konstrukcji, która pozwala na dodanie tejże flary. Polecam zacząć od mniej
agresywnego kąta np. 10-20 stopni. Na samym początku może się to wydawać dziwne,
jednak po dłuższym czasie przyzwyczajisz się do pochylenia klawiatury. Puźniej
możesz eksperymentować z agresywnym pochyleniem np. 45 stopni.

#### Palmrest

Podpórka pod nadgarstki ogólnie nie powinna nigdy być stosowana. Powinieneś
zawsze opierać ręce na podłokietnikach swojego krzesła(jeżeli pracujesz na
siedząco) a same nadgarstki powinny być w powietrzu. Sama podpurka pod
nadgarstki może naciskać na nerwy dlatego lepiej z niej nie korzystać. Jeżeli
korzystasz z klawiatury z flarą opieranie boków nadgarstków o stół powinno być
ok.

#### chock vs mx

Ma rynku są dwa 'formaty' switchów- chock i mx.

- mx-y to klasyczne switche które mają długi zakres ruchu.
- natomiast mx-y to są switche nisko profilowe które pozwalają na stworzenie
  znacząco niższej klawiatóry jednak oczywiście posiadają mnijeszy zakres ruchu.

Podczas wyboru obudowy należy wybrać który format switcha chcemy użyć ponieważ o
ile oba formaty powinny pasować to niektóre mogą nie wyglądać dobrze z innym
formatem.

#### Wireless vs Wired

Konstrukcaj bezprzewodowa ma oczywiste plusy jednak trzeba pamiętać o tym że:

1. Wyższa cena- musisz kupić odpowiednie mikro kontrolery oraz baterię.
2. Trzeba pamiętać o ładowaniu- pomaga w tym dodanie wyświetlacza lecz to wiąże
   się z więkrzą, droższą i bardziej skąplikowaną klawiaturą.
3. Jeżeli masz zaszyfrowany dysk(a powinieneś mieć) to przed zalogowaniem się do
   niego nie możesz wykorzystać użądzeń diałających po blue-toothie, co jest
   najprostrzym rozwiązaniem. W takim wypadku musiał byś użyć klawiatóry z
   dedykowanym dongl-em / użyć osobnego mikro kontrolera który będzie działał
   jako dongle.

#### Trackball/Trackpad/ Trackpin

Posiadanie dedykowanej myszki obok klawiatury w wielu przypadkach jest uciążliwe
oraz jeżeli szukamy najleprzej ergonomi to nie jest to najleprze rozwiązanie.
Jest to jeden z powodów dlaczego klawiatóry thinkpad-ów mają tak wiele
zwolenników W softwarze klawiatóry można sprawić aby klawiatóra symulowała
myszkę podczas wciskania danej kombinacji przycisków, jednak nie jest to
najwygodniejsze rozwiązanie. aby to rozwiązać można użyć:

- track point-a z klawiatóry starego think pad-a.
- Trackada.
- Trackball z specjalnym sensorem.

Trackball będzie najłatwiejszym do zrobienia i najwygodniejszym, jednak wiąże
się ze sporym kosztem. Naj łatweijszą opcją na dodanie trackballa będzie
kupienie dedykowanego modułu do myszek z sensorem PMW3360 na aliexpress lub
zrobienie jakiejś opensourceowego pcb z tym sensorem-
https://github.com/Ariamelon/Ogen.

#### Produkcja Obudowy

Jednak jeżeli chcecie klawiatury w standardowy formacie z pcb to polecam wybrać
obudowę z pcg od znanego producenta np. keychron akko - jest wiele innych
producentów jednak nie znam się na gotowcach ponieważ wole budować własne
klawiatury.\
Jeżeli chcesz ergonomiczną klawiatórę która będzie odrazu złożona to możesz
sprawdzić produkty zsa, moergo czy kinesis. Jednak tego typu klawiatóry
zazwyczaj są bardzo drogie i mają kompromisy, których opensourceowe klawiatóry
nie mają. Budowa własnej klawiatury ma najwięcej sęsu jeżeli macie drukarkę 3D
lub znacie osobę, która ją posiada. Możecie wtedy bardzo tanio wydrukować
obudowę do dowolnego projektu w dowolnym kolorze jaki chcecie.\
Jeżeli nie masz dostępu do drukarki 3D, możesz zkorzystać z sklepów które
sprzedają zestawy do budowy/ zbudowane wersje najpopularniejszych
opensourceow-ych klawiatur. Jednak nic nie pobije ceny, wygody i satysfakcji
własnoręcznie zbudowanej klawiatury.

#### Wybór designu

Jest bardzo wiele możliwych designów opensourceow-ych klawiatur. Jeżeli czujesz
się na siłach możesz nawet zaprojektować swoją własną. W opisie zostawie dwie
najpopularniejsze listy designów klawiatór.

https://github.com/topics/mechanical-keyboards
https://yal-tools.github.io/ergo-keyboards/

#### Valkyrie

#### Socket-y na switch-e

#### Switche

#### Keycapy

Pamiętaj aby patrzyć na keycapy które będą dobrze pasować i wyglądać z formatem
switchów który wybrałeś - mx lub chock.

#### Micro Controller Options

WIRELESS, PINS.

#### Additional

- TRRS
- TRRS Brakeout board
- Usb-c

#### QMK vs ZMK vs etc

### Nażędzia

- lutownica precyzyjna
- okulary ochronne
- multimetr(opcjonalnie)
- BOCZKI SZCZYPCE BOCZNE PRECYZYJNE TNĄCE OBCINAKI CĄŻKI DO KABLI ??????
- pęseta (opcjonalnie)
- wyciąg / wiatrak

## Setup QMK

## Test Micro Controlera

## Łączenie dwóch micro controlerów

## Test Track Ball-a

## Lutowanie Switchów

## Ustawianie Layoutu w QMK

https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fpreview.redd.it%2Fd1sr9ymrgn591.png%3Fwidth%3D1175%26format%3Dpng%26auto%3Dwebp%26s%3D9736698e5a8e913284dc4423c5712698bbc52519&f=1&nofb=1&ipt=c5ecf89e7171cdfc3c3c2dadf6c37dab2177c0eb28fd4eb45b734ec5b0402cd4

## Końcowy efekt

## Type Test
