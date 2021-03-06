# Fórumlehetőség az iskola honlapján
__2019/2020 projektmunka <br>
Kereszthury Péter - Tóth Bálint <br>
mentor: Békefi Gábor__

<h2><details>
<summary>Tartalom</summary>

+ [Projekt Céljai](#projekt-céljai)
+ [A fórumról](#a-fórumról)
  + [Kinézet](#kinézet)
  + [Témakörök](#témakörök)
  + [Moderáció](#moderáció)
+ [Technikai adatok](#technikai-adatok)
  + [Rendszer](#rendszer)
  + [Fórumszoftver](#fórumszoftver)
+ [Elérni kívánt eredmények](#elérni-kívánt-eredmények)
+ [Tervek a következő tanévre](#tervek-a-következő-tanévre)
+ [Napló](#napló)


</details></h2>



## Projekt céljai
Mind a ketten találkoztunk az iskolai tanulás során olyan kérdésekkel, amelyekre csak kevesen (főleg végzős diákok) tudtak válaszolni. Szerettünk volna egy olyan iskolai felületet kialakítani, amely az ezekre a kérdésekre adott információt eltárolva a következő évfolyamok segítségére is lehet. A célunk egy olyan iskolai fórum létrehozása, amelyben a diákok iskolatársaiktól, illetve tanáraiktól tudhatnak meg az iskolával és a tanórákkal kapcsolatos információkat. Ez a fórum nagyobb segítséget nyújthat az érettségizőknek, hiányzóknak vagy a dolgozatok előtt álló diákoknak. Mivel a tanárok is tudnak válaszokat adni, kérdéseket feltenni, javíthatja a tanár-diák kapcsolatot, illetve terhet vehet le az iskolában tanító tanárok válláról.
## A fórumról
### Kinézet
#### Kfg téma <br>
![kfg_téma](/images/kfg.png)
#### Fekete téma <br>
![fekete_téma](/images/dark.png)
#### Mobil téma <br>
![mobil](/images/mobile.png)<br>
A mobiltelefonokon használható téma jelenleg csak mellékes funkcióként van jelen, egyenlőre nem lett rá különösebb energia fordítva, elsősorban a fórum elérhetőségének és használhatóságának a növelésére alkalmas.
### Témakörök
A fórum négy nagyobb részre van tagolva: Tantárgyak, Belső vizsgák, Érettségi és Egyéb opciók közül választhtunk. Ezeken belül tudunk helyet találni kérdésünknek, amire a sok lehetőségnek köszönhetően biztosan találunk megfelelő kategóriát. A különböző tantárgyakhoz minden főbb kategóriában lehet találni saját szekciót így könnyítve a navigálást.
### Moderáció
Az oldal manuálisan moderálható, viszont működik egy alap káromkodásszűrő egy [wordlist](https://github.com/LDNOOBW/List-of-Dirty-Naughty-Obscene-and-Otherwise-Bad-Words) alapján rajta, ami a leggyakkoribb trágár szavakat megfogja és cenzúrázza ezeket. A lista nem teljesen pontos a jövőben egyszerűen bővíthető és módosítható. A fórumot bárki megtekintheti előzetes regisztráció nélkül, viszont a kommentek és kérdések írásához bejelentkezés szükséges. Egyenlőre a regisztráció a moderátorokon keresztül zajlik, új regisztráció esetén a fórum üzenetet küld a hozzá rendelt e-mail címre, amelyben a regisztráló adatainak áttekintése után a moderátorok engedélyezhetik és véglegesíthetik a regisztrációt. Amennyiben a regisztrációs kérés nem lett engedélyezve, 30 nap után automatikusan törlődik. <br>
(A törlés ideje és a regisztráció rendszere módosítható a fórum oldalán található konfigurációs felületen.)
## Technikai adatok
### Rendszer
Próbáltuk teszt keretnek lemodellezni az iskola szerverét, így egy VPS-re telepítettünk Debian-t, rá Apache 2-t PhP-t és MySQL-t, mivel az iskola oldala is ezeket használja, így könnyebben integrálható a weboldalra. 
### Fórumszoftver
Erre a célra a MyBB-t választottuk személyre szabhatóság, modularitás és sokoldalúsága miatt. Magáról a weboldalról lehet a fórum stílusát, beállításait változtatni, valamint több plugint lehet a fórumot üzemeltető cég hivatalos oldaláról letölteni. Felhasználása iskolai keretek között ingyenes.
## Elérni kívánt eredmények
  - Egy rövid használati szabályzat írása
  - Telepítés, átmásolás az iskola szerverére
  - Magyar - angol nyelvű kezelőfelület ✓
  - A weboldal elemeinek optimalizálása a diákok számára ✓
  - Az iskola stílusához igazodó kinézet / téma, illetve 2. téma ✓
  - A mostani diákok és tanárok felhasználóneveinek és jelszavainak átírása
  - Zárt regisztrációs felület ✓
  - Adminisztrátori feladatok minimalizálása ✓
  - A fórum regisztrációjához szükséges e-mail cím létrehozása <br>
A projekt befejezésére szükségünk lett volna az iskolában is dolgozni, azonban a koronavírus járvány miatt az iskolai szerverre való tükrözéssel együtt több dolgot sem tudtunk megoldani, amelyeket így a következő iskolaévre kell halasztanunk.

## Tervek a következő tanévre
+ Telepítés, átmásolás az iskola szerverére
+ A fórum regisztrációjához szükséges e-mail cím létrehozása
+ Adminisztrátori feladatok további, minimalizálása, a káromkodásszűrő bővítése

## Napló
<details>
  <summary></summary>
  
  + "2019. 10. 28.A fórumot futtató szerver megtalálása, felállítása és létrehozása."
  + "2019. 11. 05.: A projektmunka pontos céljainak rendezése, a célokhoz ideális fórumszoftverek keresése"
  + "2019. 11. 10.: A végleges fórumszoftver kiválasztása, technikai adatainak pontosabb megismerése"
  + "2019. 11. 12.: A fórum telepítésének megkezdése a tesztszerverre."
  + "2019. 11. 20.: Kisebb technikai problémák kijavítása, további optimalizálás"
  + "2019. 11. 30.: Magyar fordítás keresése és telepítése"
  + "2019. 12. 29.: A fórum adminisztrátori konfigurálása"
  + "2020. 02. 10.: A fórum újratelepítése"
  + "2020. 02. 15.: [Kfg téma](#kfg-téma-) elkészítése"
  + "2020. 02. 18.: Fórum konfigurálás, teljesítményoptimalizálás"
  + "2020. 02. 19.: Fórum szerkezetének, témaköreinek kialakítása"
  + "2020. 02. 20.: [Fekete téma](#fekete-téma-) elkészítése"
  + "2020. 05. 10.: [Trágár szó szűrés](#moderáció) hozzáadása"
  + "2020. 05. 15.: A fórum felső menü színének módosítás"

</details>
