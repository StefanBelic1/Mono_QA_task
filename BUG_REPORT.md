# 🐞 BUG REPORT – Photo Gallery 

## Bug #1 – Nejasna ikona padajućeg izbornika
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

## Bug #2 – Nepotreban dodatni korak za pregled galerija
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

## Bug #3 – Blog name link u podnožju ne reagira
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

## Bug #4 – Otvaranje slike iz vlastitog albuma vodi na 404 stranicu

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






## 💡 Suggestions / Improvements

### Suggestion #1 – Omogućiti pretragu po korisnicima
**Type:** UX Improvement  
**Priority:** Medium  
**Environment:** Chrome, Windows 10  

#### Description
Trenutno je moguće pretraživati samo nazive slika.  
Pretraživanje po korisnicima omogućilo bi lakše pronalaženje slika određenog autora i poboljšalo korisničko iskustvo.
