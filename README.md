# 11F-Gy2-C# FELADATOK

## Feladat 1

Az egyik digitális játékok megvételére szolgáló rendszer a játékok értékelésére bevezetett egy rendszert, ahol "ajánlott" és "nem ajánlott" értékelést lehet adni. Az ajánlott-nem ajánlott értékek százalékai alapján (a százalékot egész értékre kell kerekíteni) a következő összesített értékelések lehetnek:

-	"Nagyon pozitív" 90% felett
-	"Pozitív" 75%-89%
-	"Többnyire pozitív" 55%-74%
-	"Vegyes" 45%-54%
-	"Többnyire negatív" 25%-44%
-	"Negatív" 10%-24%
-	"Nagyon negatív" 0%-9%

A program olvassa be azt, hogy mennyien értékelték összesen a játékot (n), és azt, hogy ebből mennyien értékelték pozitívan (p). A program számolja ki a százalékos értéket!
A kapott eredmény alapján írd ki a játék értékelését!
Az első három kategória jelenjen meg zöld színnel, a "Vegyes" sárgával, a többi három pedig piros színnel!

## Feladat 2

Készíts programot, amely kő-papír-olló játékot valósít meg a következőképpen:
A gép generáljon egy véletlen számot pl. 1-3 között, és a megfelelő értékek jelentsék a kő, papír, ollót.
A játékos olvasson be egy számot, majd a kő-papír olló szabályaival értékelje ki, hogy a játékos vagy a gép nyert!
Szabályok:
-	Kő nyer az olló ellen, de veszít a papír ellen.
-	Papír nyer a kő ellen, de veszít az olló ellen.
-	Olló nyer a papír ellen, de veszít a kő ellen.

## Feladat 3

Valaki megkért arra, hogy segítsél neki edzéstervet összeállítani a (nem szökőév) év 365 napjára a láb és kéz erősítésére. Azt találtad ki, hogy naponta megmondod neki, hogy mennyiszer végezzen kisebb súlyemelést, és mennyi guggolást végezzen.
Készíts programot, amely az év 365 napjára összeállít egy edzéstervet neki a következők figyelembe vételével:
-	Az év 1-30. napján a guggolások száma 80-100 közötti legyen, a súlyemelések száma 60-80 közötti. (Az ünnepek utáni időszak)
-	Az év 31-130. napján a guggolások száma 60-80 közötti legyen, a súlyemelések száma 40-60 közötti.
-	Az év 140-160. napjáig a guggolások száma 80-100 közötti legyen, a súlyemelések száma 60-80 közötti. (Nyár előtt, és nagyjából húsvét utáni időszak)
-	Az összes többi napon a guggolások száma 60-80 közötti legyen, a súlyemelések száma 40-60 közötti.
-	MINDEN 7. nap pihenőnap!
	
A formátum lehet pl. a következő:
```
1. nap: 90 guggolás, 75 súlyemelés
2. nap: 85 guggolás, 70 súlyemelés
```

## Feladat 4

Készíts programot, amely pénznyerő gép játékot szimulál véletlen számok generálásával. Az automata úgy működik, hogy két számot generál egyszerre, és a következő összegeket lehet nyerni:
-	Ha a két szám egyenlő, akkor 4000 Ft
-	Ha mindkét szám a felső határral egyenlő, akkor 8000 Ft a nyeremény.
-	Ha mind a két szám páros, nem vesztesz, és nem nyersz semmit.
-	Minden más esetben 1000 Ft-ot veszítesz.
A program olvassa be, hogy mennyiszer legyen a generálás elvégezve (n), valamint olvasson be egy alsó határt (1 és 5 között lehet), és egy felső határt (6 és 9 között lehet). A határok beolvasását ellenőrizd, hogy tényleg a határok között van-e!

A program bevitel után elvégzi n-szer a véletlen szám generálását. A generálás közben írja ki a generált számpárok eredményét, és az aktuális összeget, ahol tartunk, ha tudjuk azt, hogy 10 000 Ft-ról indulunk.
Pl. a kiírás egy lehetséges eredménye 5 db generálás esetén 2-8 számok között:

```
Induló összeg: 10 000 Ft
2 2	Aktuális összeg: 14000 Ft
2 3 Aktuális összeg: 13000 Ft
5 7	Aktuális összeg: 12000 Ft
1 6	Aktuális összeg: 11000 Ft
8 8 Aktuális összeg: 19000 Ft
```