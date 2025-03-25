# Python

1. A Python lefordított nyelv vagy értelmezett nyelv?
A Python lefordítottnak és értelmezettnek is tekinthető, de a végrehajtási folyamatának különböző szakaszaiban.

Fordítás : Amikor Python kódot ír és futtat, a Python értelmező először a forráskódot (.py fájlok) egy köztes formába, az úgynevezett bájtkódba (.pyc fájlok) fordítja le. Ez a bájtkód a kód alacsonyabb szintű reprezentációja, de még mindig nem közvetlenül gépi kód. Ezt a Python Virtual Machine (PVM) képes megérteni és végrehajtani.
Értelmezés : Miután a Python kódot bájtkódba fordították, a Python Virtual Machine (PVM) hajtja végre, amely egy tolmács. A PVM beolvassa a bájtkódot és futás közben soronként végrehajtja, ezért a Python a gyakorlatban értelmezett nyelvnek számít.
Egyes megvalósítások, például a PyPy , Just-In-Time (JIT) fordítást használnak, ahol a Python-kódot futás közben gépi kódba fordítják a gyorsabb végrehajtás érdekében, elmosva az értelmezés és a fordítás közötti határvonalakat.

2. Mi az a dinamikusan tipizált nyelv?
A programozási nyelvek a következő két típusra oszthatók.

Statikusan beírt nyelvek: Ennél a nyelvtípusnál a változó adattípusa a fordításkor ismert, ami azt jelenti, hogy a programozónak meg kell adnia egy változó adattípusát a deklarációkor. Ilyen például a C, C++, Java és C#
Dinamikusan beírt nyelvek: Ezek azok a nyelvek, amelyek nem igényelnek előre meghatározott adattípust egyetlen változóhoz sem, mivel azt futás közben a gép maga értelmezi. Ezeken a nyelveken a tolmácsok futás közben hozzárendelik az adattípust egy változóhoz annak értékétől függően. Ilyen például a Python és a JavaScript
A statikusan gépelt nyelvek általában gyorsabbak, mint a dinamikusan gépelt nyelvek, a dinamikusan gépelt nyelvek pedig általában könnyen kódolhatók. A Python egy dinamikusan tipizált nyelv.

3. Szükséges a behúzás a Pythonban?
Igen, a Pythonban behúzás szükséges. A Python-tolmács Python behúzással tájékoztathatja, hogy egy utasításcsoport egy adott kódblokkhoz tartozik. A behúzások megkönnyítik a kód olvashatóságát a fejlesztők számára minden programozási nyelven, de a Pythonban nagyon fontos, hogy a kódot meghatározott sorrendben behúzzák.

Behúzás a pythonban
Python behúzás

4. Mik azok a beépített adattípusok a Pythonban?
A Python szabványos vagy beépített adattípusai a következők :

Numerikus: A Python numerikus adattípusa azokat az adatokat jelöli, amelyek számértékkel rendelkeznek. A numerikus érték lehet egész szám, lebegő szám, logikai szám vagy akár komplex szám is.
Sorozattípus: A szekvencia adattípusa a Pythonban hasonló vagy eltérő adattípusok rendezett gyűjteménye. A Pythonban több sorozattípus létezik:
Python karakterlánc
Python lista
Python Tuple
Python tartomány
Leképezési típusok: A Pythonban a hashálható adatok véletlenszerű objektumokra képezhetők le egy leképezési objektum segítségével. Jelenleg csak egy általános leképezési típus létezik, a szótár és a leképezési objektumok változtathatók.
Python szótár
Halmaztípusok: A Pythonban a készlet adattípusok rendezetlen gyűjteménye, amely iterálható, változtatható és nem tartalmaz ismétlődő elemeket. Az elemek sorrendje egy halmazban nem definiált, bár különböző elemekből állhat.
5. Mi a különbség a Mutable adattípus és az Immutable adattípus között?
A változtatható adattípusok szerkeszthetők, azaz futás közben változhatnak. Pl. – Lista, szótár stb.
A megváltoztathatatlan adattípusok nem szerkeszthetők, azaz nem változhatnak futás közben. Pl. – String, Tuple, stb.
6. Mi az a változó hatókör a Pythonban?
A változó hatókörének nevezzük azt a helyet, ahol egy változót találhatunk, és szükség esetén hozzá is érhetünk .

Python helyi változó: A helyi változók azok, amelyek egy függvényen belül vannak inicializálva, és egyediek az adott függvényre. A lokális változó nem érhető el a függvényen kívül.
Python globális változók: A globális változók azok, amelyek bármely függvényen kívül vannak definiálva és deklarálva, és nincsenek megadva egyetlen függvényhez sem.
Modulszintű hatókör: Az aktuális modul programban elérhető globális objektumaira vonatkozik.
Legkülső hatókör: Minden olyan beépített névre vonatkozik, amelyet a program hívhat. A hivatkozott név az utolsó helyen található a hatókör objektumai között.
7. Hogyan lehet számot padlózni Pythonban?
A Pythonban egy szám lefedéséhez használhatja a math.floor() függvényt, amely a megadott számnál kisebb vagy azzal egyenlő legnagyobb egész számot adja vissza.

A Python floor() metódusa az x alsó szintjét adja vissza, azaz a legnagyobb, x-nél nem nagyobb egész számot. 
Ezenkívül a Python ceil(x) metódusa egy x felső határértéket ad vissza, azaz a legkisebb egész szám, amely nagyobb vagy egyenlő, mint x.



import math

n = 3.7
F_num = math.floor(n)

print(F_num) 

Kimenet
3
8. Mi a különbség a / és a // között Pythonban?
/ a pontos osztást jelöli (az eredmény egy lebegőpontos szám), míg a // a padlóosztást (az eredmény egy egész szám). Például:


5//2 = 2 
5/2 = 2,5 


9. Különbség a for ciklus és a while ciklus között a Pythonban
A „for” ciklust általában különféle gyűjteménytípusok elemeinek iterálására használják, mint például a Lista , Tuple , Set és Dictionary . A fejlesztők „for” ciklust használnak, ahol a feltételeknek mind a kezdete, mind a vége van. Míg a „while” ciklus a tényleges hurkolási funkció, amelyet bármely más programozási nyelvben használnak. A programozók Python while ciklust használnak, ahol csak a végfeltételek vannak.

10. Átadhatunk-e egy függvényt argumentumként Pythonban?
Igen, több argumentum is átadható egy függvénynek, beleértve objektumokat, változókat (azonos vagy eltérő adattípusú) és függvényeket. A függvények paraméterként átadhatók más függvényeknek, mivel ezek objektumok. A magasabb rendű függvények olyan függvények, amelyek más függvényeket is felvehetnek argumentumként.

11. Mit jelent a pass a Pythonban?
A Pass utasítás a Pythonban egy null művelet vagy egy helyőrző. Akkor használatos, ha egy utasítás szintaktikailag szükséges, de nem akarunk kódot végrehajtani. Nem tesz mást, csak lehetővé teszi programunk szerkezetének fenntartását.

Példa a jelszavas használatára egy függvényben:

A kulcsszó átadása egy függvényben akkor használatos, ha definiálunk egy függvényt, de nem akarjuk azonnal megvalósítani a logikáját. Lehetővé teszi, hogy a függvény szintaktikailag érvényes legyen, még akkor is, ha még nem hajt végre műveleteket.




def fun():
    pass  # Placeholder, no functionality yet

# Call the function
fun()
12. Mit jelent a szünet, folytatás és átadás Pythonban? 
A break utasítás arra szolgál, hogy lezárja azt a ciklust vagy utasítást, amelyben jelen van. Ezt követően a vezérlés átmegy a break utasítás utáni utasításokra, ha elérhető.
A Continue szintén egy ciklusvezérlő utasítás, csakúgy, mint a break utasítás. A turpināt utasítás ellentétes a break utasítással, a ciklus befejezése helyett a ciklus következő iterációjának végrehajtására kényszerít.
A Pass azt jelenti, hogy nem hajtunk végre műveletet, vagyis egy helyőrző az összetett utasításban, ahol üresnek kell maradnia, és nem kell oda írni semmit.
13. Hogyan kerülnek átadásra az argumentumok érték vagy hivatkozás alapján a Pythonban?
A Python argumentumátadási modellje  sem nem „Érték szerinti átadás”, sem „Referencia átadása”, hanem „Objektumreferencia átadása”. 

A függvényben átadott objektum típusától függően a függvény eltérően viselkedik. A megváltoztathatatlan objektumok „érték szerinti áthaladást” mutatnak, míg a változtatható objektumok „referencia szerint áthaladnak”.

Az alábbi példában ellenőrizheti az áthaladási érték és az áthaladási referencia közötti különbséget:




def call_by_value(x):
    x = x * 2
    print("in function value updated to", x)
    return

def call_by_reference(list):
    list.append("D")
    print("in function list updated to", list)
    return

my_list = ["E"]
num = 6
print("number before=", num)
call_by_value(num)
print("after function num value=", num)
print("list before",my_list)
call_by_reference(my_list)
print("after function list is ",my_list)

Kimenet
előtti szám = 6
a függvényértékben 12-re frissítve
függvény után num value= 6
lista az ['E'] előtt
a függvénylistában frissítve ['E', 'D']
a függvénylista után ['E', 'D']
1 4. Mi a lambda függvény?
A lambda függvény egy névtelen függvény. Ennek a függvénynek tetszőleges számú paramétere lehet, de csak egy utasítása lehet.

A példában definiáltunk egy lambda függvényt ( felső ), hogy egy karakterláncot nagybetűvé alakítsunk a felső( ) segítségével.




s1 = 'GeeksforGeeks'

s2 = lambda func: func.upper()
print(s2(s1))

Kimenet
GEEKSFORGEEKS
15. Miben különbözik a szótár a listától?
A lista az indexük által elért elemek rendezett gyűjteménye, míg a szótár kulcs-érték párok rendezetlen gyűjteménye, amelyekhez egyedi kulcsokkal lehet hozzáférni. A listák ideálisak a szekvenciális adatokhoz, míg a szótárak jobbak az asszociatív adatokhoz. Például egy lista tárolhatja a [10, 20, 30] értéket, míg a szótárban az {"a": 10, "b": 20, "c": 30}.

16. Mi az a listaértés? Adj egy példát.
A listaértelmezés  egy módja annak, hogy tömör szintaxist használva listákat hozzunk létre. Lehetővé teszi, hogy új listát állítsunk elő úgy, hogy egy  kifejezést  alkalmazunk egy létező  iterálható  elem (például  lista  vagy  tartomány ) minden elemére. Ez segít nekünk tisztább, olvashatóbb kódot írni a hagyományos hurkolási technikákhoz képest.

Például , ha van egy listánk egész számokból, és szeretnénk létrehozni egy új listát, amely tartalmazza az egyes elemek négyzetét, akkor ezt könnyen elérhetjük a lista megértésével.




a = [2,3,4,5]
res = [val ** 2 for val in a]
print(res)

Kimenet
[4, 9, 16, 25]
17. Mik azok az *argok és **kwargok?
*args: A  függvénydefiníciók speciális  *args szintaxisa változó számú argumentum átadására szolgál egy függvénynek. Python program változó számú argumentum *args illusztrálására: 




def myFun(*argv):
    for arg in argv:
        print(arg)

myFun('Hello', 'Welcome', 'to', 'GeeksforGeeks')

Kimenet
Helló
Üdvözöljük
hogy
GeeksforGeeks
**kwargs: A **kwargs speciális szintaxis a függvénydefiníciókban változó hosszúságú argumentumlista átadására szolgál. A kwargs nevet a kettős csillaggal ** használjuk.




def fun(**kwargs):
    for k, val in kwargs.items():
        print("%s == %s" % (k, val))


# Driver code
fun(s1='Geeks', s2='for', s3='Geeks')

Kimenet
s1 == Geeks
s2 == for
s3 == Geeks
18. Mi a különbség a halmaz és a szótár között?
A  Python Set  egy rendezetlen adatgyűjtési adattípus, amely iterálható, változtatható, és nem tartalmaz ismétlődő elemeket. A Python halmazosztálya a halmaz matematikai fogalmát reprezentálja.

Szintaxis : Kapcsos zárójelekkel {} vagy a set() függvénnyel határozható meg.

saját_készlet = {1, 2, 3}


A Python szótár  az adatértékek rendezett (Py 3.7 óta) [rendezetlen (Py 3.6 és korábbi)] gyűjteménye, amely adatértékek, például térkép tárolására szolgál, amely más adattípusokkal ellentétben, amelyek csak egyetlen értéket tartalmaznak elemként, a szótár  kulcs:érték  párost tartalmaz. A kulcsértékek szerepelnek a szótárban az optimalizáltabbá tétel érdekében.

Szintaxis : Határozva: kapcsos zárójelek {} kulcs-érték párokkal.

my_dict = {"a": 1, "b": 2, "c": 3}


19. Hogyan lehet két listát összefűzni Pythonban?
Két listát összefűzhetünk a Pythonban az +operátor vagy az extend() metódus használatával.

1. A + operátor használatával:

Ez új listát hoz létre két lista összekapcsolásával.




list1 = [1, 2, 3]
list2 = [4, 5, 6]
result = list1 + list2
print(result) 

Kimenet
[1, 2, 3, 4, 5, 6]
2. Az extend() metódus használatával:

Ezzel a helyben hozzáadja a második lista összes elemét az első listához.




list1 = [1, 2, 3]
list2 = [4, 5, 6]
list1.extend(list2)
print(list1) 

Kimenet
[1, 2, 3, 4, 5, 6]
20. Mi a docstring a Pythonban?
A Python dokumentációs karakterláncai (vagy docstringek ) kényelmes módot kínálnak a dokumentáció Python modulokhoz, függvényekhez, osztályokhoz és metódusokhoz való társítására.

Dokumentumkarakterláncok deklarálása: A docstringek deklarálása „háromszoros idézőjelek” vagy „””háromszoros idézőjelek”” használatával történik, közvetlenül az osztály-, metódus- vagy függvénydeklaráció alatt. Minden függvénynek rendelkeznie kell egy docstringgel.
Docsstringek elérése: A docstringek az objektum __doc__ metódusával vagy a súgó funkcióval érhetők el.
21. Hogyan történik a kivételes kezelés Pythonban?
Három fő kulcsszó van, azaz try, kivéve és végül, amelyek a kivételek elkapására és a helyreállítási mechanizmus megfelelő kezelésére szolgálnak. A Try egy kód blokkja, amely hibákat figyel. Kivéve, hogy hiba esetén a blokk végrehajtásra kerül.

Az utolsó blokk szépsége abban rejlik, hogy hibapróbálkozás után végrehajtja a kódot. Ez a blokk végrehajtásra kerül, függetlenül attól, hogy hiba történt-e vagy sem. Végül a blokk az objektumok/változók szükséges tisztítási tevékenységeinek elvégzésére szolgál.

Példa: Ha megpróbál egy számot nullával osztani, az kivételt okoz.




n = 10
try:
    res = n / 0  # This will raise a ZeroDivisionError
    
except ZeroDivisionError:
    print("Can't be divided by zero!")

Kimenet
Nem osztható nullával!
Magyarázat:  Ebben a példában a szám 0-val való elosztása  ZeroDivisionError- t eredményez . A try blokk tartalmazza azt a kódot, amely kivételt okozhat, és a kivétel blokk kezeli a kivételt, és hibaüzenetet nyomtat a program leállítása helyett.

Python-Exception-Handling-1.webpPython-Exception-Handling-1.webp
22. Mi a különbség a Python tömbök és a listák között?
A tömbök (ha a Python moduljáról beszélünk array) kifejezetten olyan numerikus elemek gyűjteményének tárolására szolgálnak, amelyek mindegyike azonos típusú. Ez hatékonyabbá teszi nagy mennyiségű adat tárolását és numerikus számítások végrehajtását, ahol a típuskonzisztencia megmarad.

Szintaxis: A tömbök használatához importálni kell a modult.array

Példa:




from array import array
arr = array('i', [1, 2, 3, 4])  # Array of integers
A listák  rugalmasabbak, mint a tömbök, mivel különböző típusú elemeket (egész számokat, karakterláncokat, objektumokat stb.) tartalmazhatnak. Beépítettek a Pythonba, és nem igényelnek további modulok importálását.

A listák számos műveletet támogatnak, amelyek módosíthatják a listát.

Példa:




lst = [1, 'hello', 3.14, [1, 2, 3]]
További információ a Lista és a tömb közötti különbségekről a Pythonban


23. Mik azok a modulok és csomagok a Pythonban?
A modul egy olyan fájl, amely Python kódot (függvényeket, változókat, osztályokat) tartalmaz, amely más programokban újra felhasználható. Felfoghatja úgy, mint egy kódkönyvtárat. Például: a math egy beépített modul, amely olyan matematikai függvényeket biztosít, mint az sqrt(), a pi stb.




import math
print(math.sqrt(16))  
A csomag egy könyvtárban tárolt kapcsolódó modulok gyűjteménye. Segít a modulok rendszerezésében és csoportosításában a könnyebb kezelés érdekében. Például: A numpy csomag több modult tartalmaz numerikus műveletekhez.

Csomag létrehozásához a könyvtárnak tartalmaznia kell egy speciális __init__.py nevű fájlt .

Középhaladó Python interjúkérdések
24. Mi a különbség az xrange és a range függvények között?
A range() és az xrange() két függvény, amely felhasználható bizonyos számú ismétlésre a for ciklusokban a Pythonban. 

A Python 3-ban nincs xrange, de a range függvény úgy viselkedik, mint az xrange.
Python 2-ben
range() – Ez egy tartományobjektumot ad vissza, amely egy megváltoztathatatlan sorozattípus, amely igény szerint generálja a számokat. 
xrange() – Ez a függvény azt a generátor objektumot adja vissza, amely csak hurkolással használható számok megjelenítésére. Az egyetlen konkrét tartomány igény szerint jelenik meg, ezért lusta értékelésnek nevezik.
25. Mi az a szótári megértés? Adj egy példát
A Dictionary Comprehension egy szintaktikai konstrukció, amely megkönnyíti a szótár létrehozását a meglévő iterálhatóság alapján.




# Python code to demonstrate dictionary 
# comprehension

# Lists to represent keys and values
keys = ['a','b','c','d','e']
values = [1,2,3,4,5]  

# but this line shows dict comprehension here  
myDict = { k:v for (k,v) in zip(keys, values)}  

# We can use below too
# myDict = dict(zip(keys, values))  

print (myDict)

Kimenet
{'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}
26. Lehetséges a Tuple Comprehension Pythonban? Ha igen, hogyan és ha nem, miért?
A sorok értelmezése közvetlenül nem támogatott, a Python meglévő szolgáltatásai, például a generátor kifejezések és a tuple() függvény rugalmas alternatívákat kínálnak az iterálható adatokból sorok létrehozására.

(i az i-hez (1, 2, 3))


A sorok értelmezése nem lehetséges a Pythonban, mert az generátorba kerül, nem pedig a sorok értelmezésébe.

27. Különbséget tesz a lista és a Tuple között?
Elemezzük a Lista és a Tuple közötti különbségeket :

Lista

A listák változó adattípusúak.
A listák több memóriát fogyasztanak
A lista jobb műveletek, például beszúrás és törlés végrehajtására.
Az iterációk következményei időigényesek
Tuple

A sorok megváltoztathatatlan adattípusok.
A Tuple kevesebb memóriát fogyaszt a listához képest
A Tuple adattípus megfelelő az elemek eléréséhez
Az iterációk hatása viszonylag gyorsabb
28. Mi a különbség a sekélymásolat és a mélymásolat között?
Alább látható táblázatos különbség a sekély másolat és a mély másolat között:

sekély másolat	Deep Copy
A Shallow Copy tárolja az objektumok hivatkozásait az eredeti memóriacímre.   	A Deep copy az objektum értékének másolatait tárolja.
A sekély másolat az új/másolt objektumon az eredeti objektumban végrehajtott változtatásokat tükrözi.	A mélymásolás nem tükrözi az eredeti objektum új/másolt objektumán végrehajtott módosításokat.
A Shallow Copy az eredeti objektum másolatát tárolja, és az objektumokra mutat hivatkozásokat.	A Mélymásolat az eredeti objektum másolatát tárolja, és rekurzív módon másolja az objektumokat is.
Egy sekély másolat gyorsabb.	A mélymásolás viszonylag lassabb.
29. Melyik rendezési technikát használják a python sort() és sorted() függvényei?
A Python a Tim Sort algoritmust használja a rendezéshez. Ez egy stabil rendezés, amelynek legrosszabb esete az O(N log N). Ez egy hibrid rendezési algoritmus, amely az egyesített rendezésből és a beillesztési rendezésből származik, és úgy tervezték, hogy sokféle valós adat esetén jól teljesítsen.

30. Mik azok a dekorátorok?
A dekorátorok hatékony és rugalmas módot kínálnak a funkciók vagy módszerek viselkedésének módosítására vagy kiterjesztésére anélkül, hogy megváltoztatnák a tényleges kódjukat. A dekorátor lényegében egy olyan függvény, amely egy másik funkciót vesz fel argumentumként, és egy új funkciót ad vissza továbbfejlesztett funkcionalitással.

A dekorátorokat gyakran használják olyan forgatókönyvekben, mint a naplózás, a hitelesítés és a memorizálás, lehetővé téve, hogy tiszta, újrafelhasználható módon további funkciókat adjunk a meglévő funkciókhoz vagy módszerekhez.

31. Hogyan lehet Python programot hibakeresni?
1. A pdb (Python Debugger) használata:

A pdb egy beépített modul, amely lehetővé teszi töréspontok beállítását és soronkénti átlépést a kódon. A hibakeresőt az import pdb hozzáadásával indíthatja el; pdb.set_trace() a kódjában, ahol el szeretné kezdeni a hibakeresést.




import pdb
x = 5
pdb.set_trace()  # Debugger starts here
print(x)
Kimenet

> /home/repl/02c07243-5df9-4fb0-a2cd-54fe6d597c80/main.py(4)<modul>()
-> nyomtatás (x)
(Pdb)
2. A naplózó modul használata:

A fejlettebb hibakereséshez a naplózó modul rugalmas módot biztosít a különböző súlyosságú (INFO, DEBUG, WARNING, ERROR, KRITIKUS) üzenetek naplózására.




import logging
logging.basicConfig(level=logging.DEBUG)
logging.debug("This is a debug message")
Kimenet

DEBUG:root:Ez egy hibakeresési üzenet
32. Mik azok az iterátorok a Pythonban?
A Pythonban az iterátorokat elemcsoportok, konténerek, például lista iterálására használják. Az iterátorok elemek gyűjteményei, amelyek lehetnek listák, sorok vagy szótárak. A Python iterator az __itr__ és a next() metódust valósítja meg a tárolt elemek iterálásához. A Pythonban általában ciklusokat használunk a gyűjtemények (lista, sor) iterálására.

33. Mik azok a generátorok a Pythonban?
A Pythonban a generátor az iterátorok megvalósításának módja. Ez egy normál függvény, kivéve, hogy kifejezést ad a függvényben. Nem valósítja meg az __itr__ és a __next__ metódust, és csökkenti az egyéb általános költségeket is.

Ha egy függvény legalább egy hozamkimutatást tartalmaz, akkor generátorrá válik. A hozam kulcsszó szünetelteti az aktuális végrehajtást az állapotok mentésével, majd szükség esetén ugyanebből folytatja.

34. Támogatja a Python a többszörös öröklődést?
Ha egy osztály egynél több alaposztályból származik, többszörös öröklődésnek nevezzük. A származtatott osztály örökli az alapeset összes jellemzőjét.

multipleinh
Többszörös öröklés

A Python támogatja a többszörös öröklődést , ellentétben a Java-val.

35. Mi a polimorfizmus a Pythonban?
A polimorfizmus azt jelenti, hogy többféle formát ölthet. A polimorfizmus lehetővé teszi, hogy a különböző osztályokat egy közös interfészen keresztül úgy kezeljük, mintha ugyanazon osztály példányai lennének. Ez azt jelenti, hogy egy szülőosztályban lévő metódus felülírható egy azonos nevű metódussal egy utódosztályban, de az utódosztály biztosíthatja a saját konkrét megvalósítását. Ez lehetővé teszi, hogy ugyanaz a metódus eltérő módon működjön attól függően, hogy melyik objektum hívja meg. A polimorfizmus a felülbírálásról szól, nem a túlterhelésről; lehetővé teszi, hogy a metódusok különböző osztályú objektumokon működjenek, amelyeknek saját attribútumai és metódusai lehetnek, rugalmasságot és újrafelhasználhatóságot biztosítva a kódban.

36. Határozza meg a tokozást Pythonban?
A beágyazás egy objektum belső állapotának elrejtésének folyamata, és minden interakciót az objektum metódusain keresztül kell végrehajtani. Ez a megközelítés:

Jobb ellenőrzést biztosít az adatok felett.
Megakadályozza az adatok véletlenszerű módosítását.
Elősegíti a moduláris programozást.
A Python nyilvános ,  védett  és  privát  attribútumokon keresztül valósítja meg a beágyazást  .

Beágyazás Pythonban
Beágyazás Pythonban

37. Hogyan történik az adatabsztrakció Pythonban?
A Data Abstraction csak a szükséges részleteket biztosítja, és elrejti a megvalósítást a világ elől. A hangsúly azon van, hogy csak a lényeges funkciókat tárjuk fel, és a komplex megvalósítást egy interfész mögé rejtsük. Pythonban interfészek és absztrakt osztályok használatával érhető el.

38. Hogyan történik a memóriakezelés Pythonban?
A Python saját halomterületét használja a memória kezelésére . Alapvetően az összes objektum és adatstruktúra a privát kupactérben van tárolva. Még a programozó sem férhet hozzá ehhez a privát területhez, mivel a tolmács gondoskodik erről a térről. A Python egy beépített szemétgyűjtővel is rendelkezik, amely újrahasznosítja az összes fel nem használt memóriát, felszabadítja a memóriát, és elérhetővé teszi a halomterület számára.

39. Hogyan lehet törölni egy fájlt Python használatával?
A Python használatával a következő módszerekkel törölhetünk fájlokat:

Python Fájl törlése  az operációs rendszer használatával. távolítsa el
Törölje a fájlt Pythonban a  send2trash modul segítségével
Python Fájl törlése  az os.rmdir használatával
40. Mit jelent a szeletelés Pythonban?
A Python Slicing egy karakterlánc-művelet a karakterlánc egy részének vagy a lista egy részének kinyerésére. Ezzel az operátorral megadható, hogy hol kezdje a szeletelést, hol fejezze be, és adja meg a lépést. A listaszeletelés új listát ad vissza a meglévő listából.

Szintaxis:


részkarakterlánc = s[kezdet : vége : lépés]


41. Mi az a névtér a Pythonban?
A Pythonban a névtér olyan tárolóra utal, ahol a nevek (változók, függvények, objektumok) objektumokhoz vannak leképezve. Egyszerűen fogalmazva, a névtér egy olyan tér, ahol a neveket meghatározzák és tárolják, és segít elkerülni az elnevezési ütközéseket azáltal, hogy biztosítja, hogy a nevek egyediek egy adott hatókörön belül.

type_namespace-1
A névterek típusai

A névterek típusai :

Beépített névtér : Tartalmazza az összes beépített függvényt és kivételt, például print(), int(), stb. Ezek minden Python programban elérhetők.
Globális névtér : A program legfelső szintjén található összes objektum, függvény és változó nevét tartalmazza.
Helyi névtér : Egy függvényen vagy metóduson belüli nevekre utal. Minden függvényhívás új helyi névteret hoz létre.
Python-interjú-kérdések
Python interjú

Speciális Python-interjú kérdések és válaszok 
42. Mi az a PIP?
A PIP a Python Installer Package rövidítése, amely zökkenőmentes felületet biztosít a különféle Python modulok telepítéséhez. Ez egy parancssori eszköz, amely képes csomagokat keresni az interneten, és felhasználói beavatkozás nélkül telepíteni.

43. Mi az a zip függvény?
A Python zip() függvény egy zip objektumot ad vissza, amely több tároló hasonló indexét képezi le. Egy iterálható elemet vesz igénybe, iterátorrá alakítja, és az átadott iterálások alapján összesíti az elemeket. Egy sor iterátort ad vissza.

Szintaxis: 
zip(*iterables) 


44. Mi a pácolás és a leszedés?
Pickling: A pácolás modul bármely Python-objektumot bájtfolyammá alakít (nem karakterlánc-reprezentációvá). Ezt a bájtfolyamot ezután fájlban lehet tárolni, hálózaton keresztül elküldeni vagy elmenteni későbbi használatra. A pácoláshoz használt függvény a pickle.dump().
Kiválasztás: Az eredeti Python-objektum bájtfolyamból való lekérésének folyamatát (melyet a kiválasztás során mentünk), kiválasztásnak nevezzük. A kivonáshoz használt függvény a pickle.load().
45 . Mi a különbség a @classmethod, @staticmethodés a példány metódusai között a Pythonban?
1. A Példány Method az osztály egy példányán működik, és hozzáfér a példány attribútumaihoz, és önmagát veszi fel első paraméterként. Példa:

def módszer (saját):


2. A Class Method közvetlenül magára az osztályra működik, és nem a példányra, a cls-t veszi első paraméterként, és a @classmethod-dal definiálja.

Példa: @classmethod def method(cls):


3. A Static Method nem működik egy példányon vagy az osztályon, és nem vesz self- vagy cls-t argumentumként, és a @staticmethod definíciója.

Példa: @staticmethod def method(): igazítsa be, és ne félkövér semmit, és ne felsoroláspontokat


46. ​​Mi van __init__()a Pythonban, és hogyan selfjátszik szerepet benne?
A Python __init__() metódusa megegyezik a konstruktorokkal az OOP terminológiában. Ez egy fenntartott metódus a Python osztályokban, és automatikusan meghívódik, amikor egy új objektum példányosodik. Ez a módszer az objektum attribútumainak értékekkel történő inicializálására szolgál. Míg az __init__() inicializálja az objektumot, nem foglal le memóriát. Az új objektum memóriafoglalását a __new__() metódus kezeli, amelyet az __init__() előtt hívunk meg. A selfparaméter __init__()a létrehozandó osztály példányára vonatkozik, mivel lehetővé teszi a példány attribútumainak és metódusainak elérését. kifejezetten első paraméterként kell deklarálni minden példánymetódusban, beleértve a .self__init__()




class MyClass:
    def __init__(self, value):
        self.value = value  # Initialize object attribute

    def display(self):
        print(f"Value: {self.value}")

obj = MyClass(10)
obj.display() 

Kimenet
Értéke: 10
47. Írjon kódot a pontos idő megjelenítéséhez?



import time

currenttime= time.localtime(time.time())
print ("Current time is", currenttime)
48. Mik azok a hozzáférési specifikációk a Pythonban?
A Python a „_” szimbólumot használja egy adott adattag vagy egy osztály tagfüggvényének hozzáférés-vezérlésének meghatározására. A Python egyik osztályának háromféle Python hozzáférésmódosítója van :

Nyilvános hozzáférés módosító: Egy osztály nyilvánosnak nyilvánított tagjai könnyen elérhetők a program bármely részéből. Egy osztály összes adattagja és tagfüggvénye alapértelmezés szerint nyilvános. 
Védett hozzáférés-módosító: Egy osztály védettnek nyilvánított tagjai csak az abból származó osztály számára érhetők el. Egy osztály minden adattagját védettnek nyilvánítják úgy, hogy egyetlen aláhúzásjelet „_” adnak hozzá az adott osztály adattagjai elé. 
Privát hozzáférés-módosító: Egy osztály privátnak nyilvánított tagjai csak az osztályon belül érhetők el, a privát hozzáférés-módosító a legbiztonságosabb hozzáférés-módosító. Egy osztály adattagjait úgy nyilvánítják privátnak, hogy dupla aláhúzásjelet adnak hozzá az osztály adattagja elé. 
49. Mik azok az egységtesztek a Pythonban?
Az egységtesztelés a szoftvertesztelés első szintje, ahol a szoftver legkisebb tesztelhető részeit tesztelik. Ez annak ellenőrzésére szolgál, hogy a szoftver minden egysége a tervezettnek megfelelően működik-e. Az egységteszt keretrendszer a Python xUnit stílusú keretrendszere. Az egységteszthez a White Box Testing módszert használják.

50. Python Global Interpreter Lock (GIL)?
A Python Global Interpreter Lock (GIL) egyfajta folyamatzár, amelyet a Python használ, amikor folyamatokkal foglalkozik. A Python általában csak egy szálat használ az írott utasítások halmazának végrehajtására. Az egyszálú folyamat és a többszálú folyamat teljesítménye ugyanaz lesz Pythonban, és ez a Python GIL-jének köszönhető. A Pythonban nem tudjuk elérni a többszálas működést, mert van egy globális értelmezőzárunk, amely korlátozza a szálakat, és egyetlen szálként működik.

51. Mik azok a függvényannotációk a Pythonban?
A Function Annotation egy olyan szolgáltatás, amely lehetővé teszi metaadatok hozzáadását a függvényparaméterekhez és visszatérési értékekhez. Így megadható a függvény paramétereinek bemeneti típusa és a függvény által visszaadott érték visszatérési típusa.

A függvényannotációk tetszőleges Python-kifejezések, amelyek a függvények különböző részeihez kapcsolódnak. Ezek a kifejezések a fordítási időben kerülnek kiértékelésre, és nincs életük a Python futási környezetében. A Python nem tulajdonít jelentést ezeknek a megjegyzéseknek. Életet vesznek, ha harmadik féltől származó könyvtárak értelmezik, például mypy.

52. Mik azok a kivételcsoportok a Pythonban?
A Python 3.11 legújabb funkciója, a kivételcsoportok . Az ExceptionGroup egy új kivétel* szintaxissal kezelhető. A * szimbólum azt jelzi, hogy minden kivétel* záradék több kivételt is kezelhet.

Az ExceptionGroup különböző típusú kivételek gyűjteménye/csoportja. Anélkül, hogy több kivételt hoznánk létre, csoportosíthatjuk a különböző kivételeket, amelyeket később szükség esetén egyenként lekérhetünk, a kivételek tárolási sorrendje a Kivételcsoportban nem számít a hívásuk során.

megpróbál:
raise ExceptionGroup('Example ExceptionGroup', (
TypeError('Example TypeError'),
ValueError('Example ValueError'),
KeyError('Example KeyError'),
AttributeError('Példa AttributeError')
))
kivéve* TypeError:
...
kivéve* ValueError mint e:
...
kivéve* (KeyError, AttributeError), mint e:
...
53. Mi az a Python Switch utasítás?
A 3.10-es verziótól kezdődően a Python megvalósította a „strukturális mintaillesztés” nevű kapcsolótok funkciót. Ezt a funkciót az egyezési és kis- és nagybetűs kulcsszavakkal is megvalósíthatja. Ne feledje, hogy az aláhúzásjelet használja a Python switch utasításának alapértelmezett kis- és nagybetűjének meghatározására.

Megjegyzés : A Python 3.10 előtt a Python nem támogatja a megfelelő nyilatkozatokat.


match term:
   case pattern-1:
   action-1
   case pattern-2:
   action-2
   case pattern-3:
   action-3
   case _:
   action-default
54. Mi az a Walrus Operator?
A Walrus Operator lehetővé teszi, hogy értéket rendeljen egy változóhoz egy kifejezésen belül. Ez akkor lehet hasznos, ha egy értéket többször kell használnia egy ciklusban, de nem szeretné megismételni a számítást.

A Walrus Operatort a `:=` szintaxis képviseli, és számos környezetben használható, beleértve a while ciklusokat és az if utasításokat.

Megjegyzés: A 3.8 előtti Python verziók nem támogatják a Walrus Operatort.




numbers = [1, 2, 3, 4, 5]

while (n := len(numbers)) > 0:
    print(numbers.pop())

Kimenet
5
4
3
2
1
