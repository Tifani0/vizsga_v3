# Book&Beauty
|Rész | Repository|
|-----|-----|
|Backend | https://github.com/Tifani0/vizsga_backend_v3 |
|Frontend | https://github.com/Tifani0/vizsga_react_v3 |
|Kiindulópont | https://github.com/ni142/Book---Beauty |


💅 Book & Beauty:
-------------------

A Book & Beauty egy modern, webalapú időpontfoglaló rendszer, amelyet kifejezetten szépségápolási szolgáltatók (fodrászat, műköröm, kozmetika) számára fejlesztettünk.

A cél egy olyan platform létrehozása volt, ahol a vendégek egyszerűen tájékozódhatnak a kezelésekről és néhány kattintással időpontot foglalhatnak.


👱‍♀️ Főbb funkcióink:
---------------------
- Széleskörű szolgáltatáskatalógus: A felhasználók böngészhetnek a különböző kezelések (pl. hajvágás, festés, zselés körömépítés, manikűr) között.
- Online időpontfoglalás: Integrált naptárrendszer, amely valós időben mutatja a szabad időpontokat.
- Kategorizált kínálat: A kezelések nemömlesztve jelennek meg, hanem logikus csoportokban (pl. "Hajápolás", "Körömtervezés", "Arckezelések"), így a vendég könnyebben megtalálja, amit keres.
- Részletes adatlapok: Minden szolgáltatáshoz tartozik egy leírás, a várható időtartam (pl. 60 perc) és a pontos ár, segítve a vendég döntését.

📌 Technikai megvalósítás:
----------------------------

✔️ Frontend: React keretrendszer Vite környezetben, amely gyors és reszponzív felhasználói élményt biztosít.

✔️ Backend: Node.js alapú szerver, amely az üzleti logikát kezeli.

✔️ Adatbázis-kezelés: Prisma ORM segítségével kommunikál a rendszer az adatbázissal, biztosítva a stabil adatkezelést (pl. felhasználók, időpontok, kezelések tárolása).

✔️ Stílus: Modern CSS megoldások a letisztult, esztétikus "beauty" megjelenés érdekében.


Miért ezt választottuk❔
-------------------------
A szépségiparban egyre nagyobb igény van a digitalizációra. A fejlesztés során nagy hangsúlyt fektettünk a felhasználóbarát felületre és a biztonságos bejelentkezésre.

🔺 A projekt során a legnagyobb kihívást az aszinkron folyamatok (például a foglalási adatok lekérése a szervertől) és az adatbázis-kapcsolatok (Prisma) megfelelő kezelése jelentette.
