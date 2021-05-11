Developer:  Loginform Kft.
Programer:  Nagykékesi Árpád
Partnet:    Komax Thonauer Kft.
Trekker:    54839
NAVVer:     NAV2015
TAG:        LI_NA_20210430 T54839 LIAI
Date:       20210430
Subscript:  Cikk import feldolgozási táblába
Description: 

A KOMAX-ban, a Thonauer_Test20200109 adatbázisban kellene egy betöltést írni ami a mellékelt excel adatait tölti be a 50003 Item Import táblába.
(A betöltésbe bele kellene tenni, hogy a mező hosszabb, mint a tábla mezőjének hossza, akkor vágja le a tábla mezőjének hosszára.)

A tábla kulcsa Entry No., No.

Az Entry No. folyamatosan növekvő szám, az No. a cikkszám. (Egy cikkszám többször szerepelhet.)

A

Enabled Field No.Field Name Data Type Length Description
Yes 190 Processed Boolean
Yes 200 Error Description Text 250
Yes 210 Processed Date DateTime

mezőket a feldolgozás fogja majd kitölteni, ezekkel nem kell foglalkoznod.

Ha a betöltés megvan, akkor kellene egy riportot írni, ami ütemezve meghívja ezt a betöltést, és betöltés után átmozgatja a file-t egy másik könyvtárba. (A Pannonban van már kész ilyen riport, azt kellene áthozni erre.)

A jövő hét elején kellene. 
Megbeszélés:

Work:
2021.05.11
  50003-as tábla kialakítása
  majd a Robi megoldását kiegészíteni az paraméterekkel
  5004-es page-re új ACTION
  Az excel betöltő elkészítése.
  - file kezelés (serverre feltöltés)
  - rekord feltöltés
  - Text2Decimal 
  Teszt, ok. 