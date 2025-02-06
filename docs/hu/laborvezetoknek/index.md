# Laborvezetőknek

Laborvezető/demonstrátor lennél? Az alábbiakat érdemes tudnod.

A tárgy alapképzés (BSc) 6. félévében specializációs tárgy. Ezt azt jelenti, hogy a hallgatók szoftverfejlesztési alapismeretekkel és adatbázis alapismeretekkel rendelkeznek, valamint a megelőző félévben teljesítették az _Adatvezérelt rendszerek_ c. tárgyat, amelynek jelen tárgy a laborja. A tárgyunk célja a tudás elmélyítése és az önálló munka gyakorlása. A laborok során -egy kivételtől eltekintve- már ismert technológiákkal foglalkozunk.

## Laborvezető feladatai

A laborvezető a tárgy oktatásában segít a beadott megoldások értékelésében és hallgatók konzultálásában. A feladat **2025 tavasszal** az alábbiakból áll.

Korábban az 1. és 2. feladat jelenléti formában folyt, **viszont 2025-től a tárgy oktatása teljesen aszinkron/online formában történik.**

**Otthon teljesített laborok során segítségnyújtás.** Csoportonként van 5 darab otthon elvégzett labor, amit a hallgatók házi feladatként önállóan teljesítenek a megadott határidőig. Ennek során, ha szükséges, a laborvezető segítséget nyújt a hallgatóknak kérdés és probléma esetén.

**Labor feladatok értékelése.** A félév során csoportonként összesen 5 labor van, mindegyiket jeggyel értékeljük. A laborok beadása az adatvezérelt rendszerek házi feladataival analóg, GitHub pull request-ek formájában történik. A laborok kiértékelése részben automatikusan történik: egy szoftver lefuttatja és ellenőrzi a beadott munkát (3., 4., 5., labor), ahol ez lehetséges. A laborvezető feladata a beadott házi feladat formai és tartalmi ellenőrzése a beadás után:

* kért képernyőképek megfelelnek-e az előírásoknak és konzisztensek-e a beadott forráskóddal
* code-review a PR-ben, ahol visszajelzést tudunk adni a megoldással kapcsolatban pl.: miért nem adott pontot a kiértékelő, esetleg egy szebb megoldási javaslat

## Demonstrátorság

Hallgató vagy de szeretnél bekapcsolódni az oktatásba? Elvégezted ezt a tárgyat ötössel? Várunk demonstrátorként!

A TVSZ pár követelményt szab demonstrátoroknak: (lásd [aktuális TVSZ](https://www.kth.bme.hu/document/2376/original/BME_TVSZ_2016%20elfogadott_mod_20200131-T.pdf) 165.§):

!!! quote ""
    (5) A demonstrátori pályázat benyújtásának feltétele, hogy a pályázó

    a) a demonstrátori jogviszonnyal érintett félévben rendelkezzen aktív hallgatói jogviszonnyal;

    b) rendelkezzen alapképzésben vagy osztatlan képzésben szerzett oklevéllel;

    c) alapképzésben vagy osztatlan képzésben szerzett oklevél hiányában rendelkezzen legalább annyiszor huszonöt teljesített kredittel, ahány lezárt aktív féléve van és halmozott súlyozott tanulmányi átlageredménye haladja meg a 3,50 értéket; és

    d) ne álljon fegyelmi büntetés hatálya alatt.

Ha érdekel a lehetőség, megfelelsz a fenti követelményeknek, és az órarendedbe belefér a labor (lásd az időpontokat fentebb), keresd a [tárgyfelelőst](mailto:albert.istvan@vik.bme.hu).

### Anyagok elérhetősége

- A tárgy minden anyaga ezen az oldalon érhető el. Ha hibát, elgépelést találsz benne, arra kérünk, hogy javítsd: minden anyag jobb felső sarkában van egy kis ceruza ikon, javítsd a hibát, és küldj PR-t.

## Beadott labor megoldás értékelése

A laborok megoldását adott határidőig kell beadni GitHub-on. Ennek pontos menete a hallgató szemszögéből [itt](../GitHub.md) elolvasható.

Ahhoz, hogy hozzáférj a GitHub-on a beadott megoldásokhoz (és ahhoz, hogy a hallgatók ezt hozzád tudják rendelni), kell egy GitHub account. A GitHub nevedet írd meg a tárgyfelelősnek, és felvesz GitHub-on a <https://www.github.com/bmeviauac01> organization-be.

### Mikor kell értékelni a labort?

A laborokat a határidő lejárta után kell értékelni. A határidő előtt a megoldásokra nem kell ránézni, kivéve, ha ezt a hallgató kéri. Kérdéssel a hallgató direktben kell megkeressen (pl. emailben vagy [GitHub-on](../GitHub.md#kapott-eredmennyel-kapcsolatban-kerdes-vagy-reklamacio)).

### Hol kell értékelni a labort?

A határidő lejárta után a feladatod a **hozzád rendelt** pull request-ek értékelése. A hallgató azzal adja be a labort, hogy a pull request-et a laborvezetőjéhez rendeli. Ezeket a GitHub keresőjével a legegyszerűbb megtalálni: <https://github.com/pulls?q=is%3Aopen+is%3Apr+org%3Abmeviauac01+assignee%3A%40me+>.

Alternatívaként a GitHub értesítő felületét is lehet használni a <https://github.com/notifications> címen, itt minden hozzád rendelt, vagy review-ra váró PR megjelenik.

### Hogyan kell értékelni a labort?

A PR-eket egyesével kell megnyitni, és meg kell nézni a PR komment felületén az eredményt. Itt látható lesz a lefuttatott értékelés eredménye, valamint a képernyőképek. Emellett meg kell nézni a forráskódot is.

![](images/hazi-github-pr-conversation-changes.png)

Automatikus értékelés esetén (ami nem minden labornál van) a forráskódot nem szükséges betűről betűre megnézni - a részletes ellenőrzést elvégzi az automata. A laborvezető feladata a képernyőképek ellenőrzése, valamint annak eldöntése, hogy a forráskód konzisztens-e a kapott eredménnyel, és nincs-e benne olyan kódrészlet, amely ugyan működik, de kifezetetten rosszul oldja meg a problémát. Amely labornál nincs automata értékelés, ott több munka hárul a laborvezetőre, alaposabban meg kell nézni a megoldást.

A konkrét laborok és értékelésük:

- Reporting: képernyőképek alapján kell kiértékelni a megoldást, diszkrepancia esetén meg lehet nézni a PowerBI projektet is
- Lekérdezés optimalizálás: szöveges magyarázatot és képeket kérünk markdown fogmájában, értékelni kell feladatonként a helyes magyarázatot
- MSSQL: van automata értékelés, a kódot ránézésre kell ellenőrizni (nincs-e benne pl. beégetett eredmény valós megoldás helyett, vagy nem nagyon hatékonytalan-e), valamint a képek és a kód konzisztenciáját kell ellenőrizni
- MongoDB: u.a.
- REST & Entity Framework: u.a.

A feladatok minta megoldása itt érhető el: <https://github.com/bmeviauac01?q=labor-megoldas>. Ezek csak lehetséges megoldások, a hallgató megoldása nem kell ezzel egyezzen.

Az értékelés végeztével:

- Ha az automata értékelés helyénvaló volt, akkor le kell zárni a PR-t a `/ahk ok` parancs beírásával egy kommentbe. Ennek hatására a PR jóváhagyásra kerül és merge-elve lesz.
- Ha az automata értékelést felülbírálod pontszámban, akkor a `/ahk ok 20 3` parancsot kell kiadni, ahol is az első szám az összes nem iMSc feladatra kapott pontszám **összege**, a második szám pedig az iMsc feladatra kapott pontszám. Az utóbbi szám elhagyható, ha nincs megoldva az iMsc feladat.
- Ha nincs automata értékelés, akkor az előbbi szintaktika szerint ki kell adni a `/ahk ok 20 3` parancsot a megfelelő pontszámokkal.
- Ha a beadott megoldás nem fogadható el (határidőn túl érkezett, a képek nem támasztják alá a megoldást, a forráskód elfogadhatatlan, stb.), akkor ki **kell** adni a `/ahk ok 0 0` parancsot. Ezzel fogjuk rögzíteni, hogy az automata értékelő által adott pontszámokat felülírjuk.

A fenti parancs egy kommentben tetszőleges helyen szerepelhet, amennyiben egy sorban csak ez a parancs szerepel. Írhatunk tehát a hallgatónak megjegyzést, majd utolsó sorba írjuk ezt a parancsot. Érdemes a hallgatónak legalább egy mondatot írni, hogy lássa, elfogadtuk a megoldást. Ha még sincs megjegyzésünk a hallgató felé, akkor csak egysoros komment kell ezzel a paranccsal.

![](images/hazi-github-pr-ahkcommand.png)

A parancs többször is kiadható, tehát elrontott pontszámot lehet javítani az újbóli kiadással.

A parancs hatását látjuk is utána PR-ben:

- a kommentre a parancs felismerésének megerősítésére érkezik egy reakció,
- a PR változtatásai jóváhagyásra kerülnek (ez szükséges a mergeléshez a protected branch miatt),
- a a PR mergelésre kerül - ezzel lezárt állapotba kerül a PR és így eltűnik a teendők listájáról,
- és végül elmentésre kerül az eredmény a háttérben - ezt már közvetlenül nem látjuk.

![](images/hazi-github-pr-ahkmerge.png)

### Problémák és megoldásuk

**Nem futott le az automata értékelés.**

- Lehet, hogy a hallgató _draft_ módban hagyta a PR-t, ezt vissza kell állítani. A PR alján megjelenik ilyenkor egy _Ready for review_ gomb.
- Ha sikertelen volt a kiértékelés, meg lehet ismételni. Ez segít a tranziens hibákon (ritka eset). Ehhez tegyél egy _eval_ nevű labelt-t a PR-re (lehet hogy új label-ként kell létrehozni).

**Több, mint 5-ször futott a kiértékelés.** Ezt pontlevonással szankcionáljuk. Első alkalommal eltekinthetünk tőle, de mindenképpen tájékoztassuk a hallgatót.

**Hiba van a kiértékelő alkalmazásban.** Előfordulhat. Keresd a tárgyfelelőst, vagy javítsd a hibát (a kiértékelő programok itt vannak: <https://github.com/bmeviauac01/laborok-ahk/>).
