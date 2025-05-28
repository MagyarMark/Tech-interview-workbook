# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
A tesztelés célja a hiba keresés, nem pedig a hiba készítés. 
A tesztelés nem az, hogy a programozók hibáit fedezzük fel, hanem az, hogy a szoftver minél jobb legyen.

#### ✅ Mik a tesztelési alapelvek?
- A tesztelés célja a hiba meg keresése.
- A tesztelés nem az, hogy a programozók hibáit fedezzük fel, hanem az, hogy a szoftver minél jobb legyen.
- A tesztelés egy folyamatos folyamat.

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Az egységtesztelés a szoftver egyes részeinek tesztelése. 
Az egységtesztek írásáért a programozók felelősek.

#### ✅ Mik a tesztszintek, és mi a különbség köztük?
- Egységtesztelés
- Komponens tesztelés
- Integrációs tesztelés
- Rendszertesztelés
- Elfogadási tesztelés

A különbség köztük az, hogy milyen szinten teszteljük a szoftvert.

#### ✅ Mi a különbség a verifikáció és a validáció között?
A verifikáció a szoftver egyes részeinek tesztelése, míg a validáció a szoftver teljes tesztelése.

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
- Funkcionális tesztelés
- Nem funkcionális tesztelés

A különbség köztük az, hogy a funkcionális tesztelés a szoftver funkcióinak tesztelését jelenti.
A nem funkcionális tesztelés a szoftver egyéb jellemzőinek tesztelését jelenti.

#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
A fehér doboz tesztelés a szoftver forráskódjának tesztelését jelenti.
A szürke doboz tesztelés a szoftver részleges tesztelését jelenti.
A fekete doboz tesztelés a szoftver teljes tesztelését jelenti.

#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
A felhasználói elfogadási teszt a szoftver felhasználóinak tesztelését jelenti.
A rendszerteszt a szoftver teljes tesztelését jelenti.

#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
A regressziós tesztelés a szoftver változásai miatt szükséges tesztelés
    - A füsttesztelés a szoftver részleges tesztelését jelenti.
    - Az újratesztelés a szoftver teljes tesztelését jelenti.

#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
A statikus tesztelés a szoftver forráskódjának tesztelését jelenti.
A dinamikus tesztelés a szoftver futás közbeni tesztelését jelenti.

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
A V-modell a tesztelési folyamatot egy V-alakban ábrázolja, ahol a tesztelés a fejlesztési folyamatban a legutolsó lépés. A vízesés modell a tesztelési folyamatot egy vízeséshez hasonlítja, ahol a tesztelés a fejlesztési folyamatban egy folytonos folyamat. Az Agile megközelítés a tesztelési folyamatot egy iteratív folyamatként ábrázolja, ahol a tesztelés a fejlesztési folyamatban egy folytonos folyamat.

<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">

<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">

<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">

## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?
- A hibajelentés
- A hibajelentés megfogadása
- A hibajelentés megjegyzései
- A hibajelentés megoldásai

#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!
- Tesztelési cél
- Tesztelési folyamat
- Tesztelési szempontok
- Tesztelési környezet
- Tesztelési eredmények
- Tesztelési eredmények
- Tesztelési hibák és hiányosságok
- Javaslatok

#### ✅ Mit tartalmaz egy hibajelentés?
- Hibaüzenet
- Várható eredmény
- Hibáig eljutó lépések
- Tesztelési környezet

#### ✅ Hogyan rangsorolnál egy hibát?
- Kritikus
- Magas
- Közepes
- Alacsony

## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?
Amelyek:
- Gyakran futnak
- Sok időt igényelnek
- Nehézkesek vagy unalmasak a kézi tesztelésekkel
- Sokszor ismétlődnek
- Kritikus fontosságúak

#### ✅ Írj le egy jó automatizált tesztet!
- Egyértelmű célja van
- Jól meghatározott feltételei vannak
- Megfelelően paraméterezett
- Gyorsan fut
- Jó hibakeresési lehetőségekkel rendelkezik(Fel vannak cimkézve a dolgok)

#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?
- Selenium: egy nyílt forráskódú, webes automatizálási eszköz, amely lehetővé teszi a webes alkalmazások tesztelését.
- Selenium IDE: egy Seleniumhoz kapcsolódó eszköz, amely lehetővé teszi a tesztesetek létrehozását és futtatását a böngészőben.
- Selenium WebDriver: egy Seleniumhoz kapcsolódó eszköz, amely lehetővé teszi a webes alkalmazások automatizálását a böngészőben.
(Windsurf AI válasz)

#### ✅ Hogyan lehet azonosítani a webes elemeket?
- ID
- Name
- CSS
- XPath

#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!
- Explicit 
- Implicit 


#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!
- POM
- Keyword Driven Testing

#### ✅ Mi a különbség a TDD és BDD között?
- Fejlesztők írnak teszteket a kód előtt
- A megrendelő és fejlesztő együtt teszteli

#### ✅ Mi az API tesztelés és miért hasznos?
- Biztosítja az API-k megbízhatóságát
- Csökkenti a hibák számát
- Növeli a fejlesztési sebességet

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
- Növeli a tesztek hatékonyságát
- Csökkenti a tesztek írásának idejét
- Lehetővé teszi a tesztek futtatását különböző környezetekben

#### ✅ Mik a kihívások és ajánlott eljárások a dinamikusan betöltött webes elemekkel?
- Az elemek betöltésének ideje változhat
- Az elemek nem mindig elérhetőek
- Az elemek tulajdonságai változhatnak
- A Selenium WebDriver nem mindig képes az elemekre várni
- A Selenium WebDriver nem mindig képes az elemek tulajdonságait értelmezni
- A Selenium WebDriver nem mindig képes az elemekre kattintani
- A Selenium WebDriver nem mindig képes az elemekre rákattintani
- A Selenium WebDriver nem mindig képes az elemekre feliratkozni
- A Selenium WebDriver nem mindig képes az elemekre leiratkozni
(WindSurf AI válasz, kivéve az első 3db)

#### ✅ Mik a mobil tesztautomatizálás kihívásai?
- készülék és op rendszerhez való igazodás
- összeszedni mit és hogyan teszteljünk illetve az környezet megteremtése
- alkalmazás és szoftverfrissítéshhez való igazodás

## Haladó témák
<img src="https://www.softwaretestinghelp.com/wp-content/qa/uploads/2020/05/DevOps-in-a-Selenium-Testing.png" alt="image" width="320" height="220">

#### ✅ Mi a különbség a CI és CD között?
A CI a kód folyamatos integrálását, míg a CD a folyamatos szállítást jelenti.
#### ✅ Írj le egy Continuous Delivery folyamatot!
A kód automatikus tesztelése és szállítása a fejlesztéstől a termelésig.
#### ✅ Hasonlítsd össze két népszerű CI rendszert, ezek közül az egyik legyen a Jenkins!
A Jenkins könnyen konfigurálható és bővíthető, míg a GitLab CI integráltabb és egyszerűbb felületet kínál.
(Ai válasz)
#### ✅ Mi a Docker és miért hasznos?
A docker egy virtualizált környezetet létesít és ott tudjuk futtatni különböző programjainkat
