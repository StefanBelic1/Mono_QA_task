# 🐞 BUG REPORT – Photo Gallery 

## ♦️ Bug #1 – Nejasna ikona padajućeg izbornika
**Type:** UI Bug
**Severity:** Low  
**Environment:** Chrome, Windows 10  

### Steps to Reproduce
1. Otvori početnu stranicu  
2. Pogledaj ikonu padajućeg izbornika (screenshots/bug1.png) 

### Expected Result
Padajući izbornik bi trebao biti predstavljen poznatom ikonom poput klasične "hamburger" ikone ili strelice prema dolje (screenshots/hamburger.png)

### Actual Result
Gumb padajućeg izbornika nije jasan, izgleda kao da predstavlja način biranja između tamne i svijetle teme.

---

## ♦️ Bug #2 – Nepotreban dodatni korak za pregled galerija
**Type:** UX Bug
**Severity:** Low
**Environment:** Chrome, Windows 10  

### Steps to Reproduce
1. Otvori početnu stranicu
2. Klikni ikonu koja prikazuje galeriju (screenshots/bug2Gumb)

### Expected Result
Korisnik bi trebao moći odmah listati prema dolje do galerije bez dodatnog klika.

### Actual Result
Klikom na gumb otvara se galerija i tek tada omogućuje korisniku listanje.

---

## ♦️ Bug #3 – Blog name link u podnožju ne reagira
**Type** Frontend Bug
**Severity:** Medium
**Environment:** Chrome, Windows 10  

### Steps to Reproduce
1. Otvori početnu stranicu
2. Listaj prema dolje
3. Klikni na "Blog name" 

### Expected Result
Copyright ima pravi naziv od koga je postavljen i klikom na ime vodi na njihovu stranicu.

### Actual Result
Blog name je prazan link i ne vodi nigdje prilikom klika (screenshots/bug_blog_name.png) 

---

## ♦️ Bug #4 – Otvaranje slike iz vlastitog albuma vodi na 404 stranicu

**Type:** Functional Bug  
**Severity:** High  
**Environment:** Chrome, Windows 10  

### Steps to Reproduce
1. Prijavi se u aplikaciju  
2. Otvori Moj album : "TestAlbum"
3. Klikni na bilo koju sliku unutar svog albuma  

### Expected Result
Odabrana slika se otvara u prikazu s detaljima.  

### Actual Result
Umjesto prikaza slike, otvara se stranica s porukom **"404: Page Missing"** – prazna stranica bez sadržaja. 

---

## ♦️ Bug #5 – Klik na menu unutar profila vraća korisnika na početnu stranicu

**Type:** Functional Bug 
**Severity:** Medium  
**Environment:** Chrome, Windows 10  

### Steps to Reproduce
1. Prijavi se u aplikaciju  
2. Otvori svoj profil  
3. Otvori padajući izbornik
4. Klikni menu 

### Expected Result
Otvara se menu bez povratka na početnu stranicu.  

### Actual Result
Nakon klika menu se otvara i vraća korisnika na početnu stranicu. 

---

## ♦️ Bug #6 – Albumi se na početnoj stranici prikazuju kao pojedinačne slike

**Type:** Functional / UX Bug  
**Severity:** Medium  
**Environment:** Chrome, Windows 10  

### Steps to Reproduce
1. Otvori početnu stranicu aplikacije  
2. Pregledaj prikaz albuma koji se nalaze na stranici  

### Expected Result
Na početnoj stranici trebali bi se prikazivati samo albumi, svaki s naslovnom slikom i nazivom.  
Kada korisnik klikne na album, tada se trebaju prikazati pojedinačne slike unutar tog albuma.  

### Actual Result
Na početnoj stranici prikazuju se i naslovna slika albuma i slike unutar albuma kao da su sve zasebne fotografije.  
Time se gubi struktura albuma i korisnik ne može razlikovati gdje počinje novi album. (screenshots/bug_albumCover_Photos.png)

---
## ♦️ Bug #7 – Broj slika u albumu se ne ažurira odmah nakon brisanja

**Type:** Functional Bug
**Severity:** Low
**Environment:** Chrome, Windows 10

### Steps to Reproduce
1. Otvori album koji sadrži više slika
2. Obriši jednu sliku iz albuma
3. Promatraj prikaz broja slika u albumu bez osvježavanja stranice

### Expected Result
Nakon što korisnik obriše sliku, broj slika prikazan uz album trebao bi se odmah ažurirati i prikazivati točan broj slika.

### Actual Result
Nakon brisanja slike, broj slika u albumu se ne ažurira odmah.
Prikazuje se stari broj (npr. 2 slike) sve dok se stranica ručno ne osvježi, nakon čega se prikazuje točan broj (1 slika).

---

## ♦️ Bug #8 – Ručno uneseni naziv slike se prepisuje imenom datoteke nakon uploada

**Type:** Functional / UX Bug
**Severity:** Medium
**Environment:** Chrome, Windows 10

### Steps to Reproduce
1. Otvori formu za dodavanje nove slike u aplikaciji.​
2. U polje "Photo Name" upiši vlastiti naziv slike (npr. "forest") prije odabira datoteke.​
3. Odaberi i uploadaj datoteku s računala čiji je naziv drugačiji (npr. "IMG_1234.jpg").​
4. Promatraj vrijednost polja "Photo Name" nakon završetka uploada.​

### Expected Result
Ručno uneseni naziv treba ostati nepromijenjen nakon odabira i uploada datoteke, osim ako aplikacija prije uploada eksplicitno upozori da će naziv biti prepisan imenom datoteke.​

### Actual Result
Nakon uploada, vrijednost polja automatski se prepisuje na naziv datoteke s računala (npr. s "forest" na "IMG_1234"), čime se gubi korisnički unos bez jasnog upozorenja ili kontrole.​

---

## ♦️ Bug #9 – Početna poruka je preopćenita i neusklađena s tonom proizvoda

**Type:** UI/Content Bug
**Severity:** Low
**Environment:** Chrome, Windows 10

### Steps to Reproduce
1. Otvori početnu stranicu aplikacije.  
2. Uoči poruku: "We are celebrating the vastness of life."

### Expected Result
Poruka treba biti gramatički ispravna, jasnija i prirodnija, primjerice:  
"We celebrate the vastness of life."

### Actual Result
Trenutna poruka "We are celebrating the vastness of life" zvuči neprirodno i nije u skladu s tonom aplikacije.

---

## ♦️ Bug #10 - Nije moguće postaviti novu lozinku.

**Type:** Functional Bug
**Severity:** High
**Environment:** Chrome, Windows 10

### Steps to Reproduce
1. Otvori početnu stranicu aplikacije
2. Odaberi Menu
3. Klikni na "Login"
4. Klikni na "Forgot Your Password? Recover Your Password Here!"
5. Unesi točan email korisničkog računa
6. Na dobivenom mailu klikni "Set New Password"
   
### Expected Result
Otvara se stranica za unos nove lozinke i omogućuje korisniku da uspješno postavi novu lozinku.

### Actual Result
Umjesto toga otvara se stranica s porukom "404 Not Found".  
Resetiranje lozinke nije moguće dovršiti.  (screenshots/bug_newPassword)

---

## ♦️ Bug #11 – Social login opcije ne rade 

**Type:** Functional Bug  
**Severity:** High  
**Environment:** Chrome, Windows 10  

### Steps to Reproduce
1. Otvori Login stranicu aplikacije.  
2. Klikni na bilo koju opciju pod Social login (Facebook, Google, Twitter ili GitHub).  

### Expected Result
Otvara se prozor za prijavu putem odabrane društvene mreže.  
Korisnik se nakon uspješne prijave vraća u aplikaciju kao autentificirani korisnik.  

### Actual Result
Umjesto toga prikazuje se poruka:  
"undefined: Social login configuration not found."  
Prijava putem društvenih mreža nije moguća.  

---

## ♦️ Bug #12 – Aplikacija prihvaća nevažeće e-mail adrese pri registraciji

**Type:** Validation / Functional Bug  
**Severity:** High  
**Environment:** Chrome, Windows 10  

### Steps to Reproduce
1. Otvori stranicu za registraciju.  
2. Unesi neispravnu e-mail adresu, npr. ""test@gmailc.om".  
3. Dovrši registraciju.  
4. Provjeri mogućnost prijave.  

### Expected Result
Aplikacija bi trebala prikazati poruku o nevažećoj e-mail adresi i spriječiti registraciju.  

### Actual Result
Registracija se uspješno izvrši i aplikacija navodno šalje aktivacijski mail na nepostojeću adresu.  
Korisnik se zatim ne može prijaviti jer nije moguće potvrditi račun.  

---
---


## 💡 Suggestions / Improvements

### Suggestion #1 – Omogućiti pretragu po korisnicima
**Type:** UX Improvement  
**Priority:** Medium  
**Environment:** Chrome, Windows 10  

#### Description
Trenutno je moguće pretraživati samo nazive slika.

#### Expected Benefit

Pretraživanje po korisnicima omogućilo bi lakše pronalaženje slika određenog autora i poboljšalo korisničko iskustvo.
---
### Suggestion #2 – Omogućiti "Drag & Drop" upload slika

**Type:** UX Improvement  
**Priority:** Medium  
**Environment:** Chrome, Windows 10  

#### Description
Trenutno se slike mogu dodavati samo putem standardne opcije **"Browse files"**.  
Predlaže se dodavanje mogućnosti **povlačenja i ispuštanja (drag & drop)** slika unutar područja za upload.  

#### Expected Benefit
Korisnicima bi se omogućilo brže i intuitivnije dodavanje fotografija, što je uobičajeno ponašanje u modernim web aplikacijama.  
Opcija *drag & drop* trebala bi biti dodatak postojećem načinu učitavanja putem dijaloga za datoteke, a ne zamjena.

---

### Suggestion #3 - Unaprijediti upload fotografije 

**Type:** Functional Improvement  
**Priority:** Medium  
**Environment:** Chrome, Windows 10  

#### Description
Trenutno se naziv slika prilikom uploada automatski dodjeli prema nazivu datoteke bez obzira želi li korisnik tu mogućnost.
Ako je polje "Photo Name" već promijenjeno od strane korisnika, ne prepisivati ga nakon uploada; popunjavati ga imenom datoteke samo kada je prazno ili nepromijenjeno.​
Dodati toggle "Koristi naziv datoteke" koji kad je uključen sinkronizira naslov s file.name, a kad je isključen zadržava korisnički unos.​
Jasno validirati i prikazati informativnu poruku ako će aplikacija prepisati naslov, ili primijeniti pravilo da se ime datoteke koristi samo za interni identifikator, dok “Naziv” ostaje korisnički atribut.​

#### Expected Benefit
Korisnik ne mora ponovno unositi naziv slike ukoliko je prije uploada već to učinio.

---
### Suggestion #4 – Zamijeniti beskonačno skrolanje numeracijom stranica (pagination)

**Type:** UX Improvement  
**Priority:** Medium  
**Environment:** Chrome, Windows 10  

#### Description
Trenutno aplikacija koristi beskonačno skrolanje za prikaz slika.  
Predlaže se uvođenje paginacije, prikaz ograničenog broja slika po stranici (npr. 20), uz mogućnost prelaska na sljedeću / prethodnu stranicu.

#### Expected Benefit
- Lakše snalaženje i povratak na prethodne slike  
- Brže učitavanje sadržaja  
- Jasnija struktura galerije i bolja kontrola nad pregledom


