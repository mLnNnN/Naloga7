# Testni scenariji – SmartWeb Platform

V datoteki so opisani testni scenariji za 3 izmed glavnih funkcionalnosti platforme SmartWeb Platform:  
1. Uporabniška prijava in registracija  
2. Sistem za upravljanje vsebine (CMS)  
3. Napredna iskalna funkcija  

---

## 1. Testni scenarij: Uporabniška prijava in registracija

### Funkcionalnost:
Uporabniška prijava in registracija (prijava z e-pošto)

### Koraki izvedbe:
1. Uporabnik odpre stran za prijavo (/login).
2. Vnese veljaven e-poštni naslov in geslo.
3. Klikne gumb **"Prijava"**.
4. Če uporabnik še nima računa, klikne **"Registracija"**.
5. Vnese podatke (ime, e-pošta, geslo).
6. Klikne **"Ustvari račun"**.

### Pričakovani rezultat:
- Prijava: uporabnik je uspešno prijavljen in preusmerjen na nadzorno ploščo.  
- Registracija: račun je ustvarjen, uporabnik prejme potrditev in je prijavljen v sistem.

---

## 2. Testni scenarij: Sistem za upravljanje vsebine (CMS)

### Funkcionalnost:
Dodajanje, urejanje in brisanje vsebin.

### Koraki izvedbe:
1. Uporabnik se prijavi v sistem kot urejevalec.
2. V meniju izbere modul **"Vsebine"**.
3. Klikne **"Dodaj novo vsebino"**.
4. Vnese naslov, opis in doda sliko.
5. Shrani vsebino.
6. Nato izbere obstoječo vsebino in klikne **"Uredi"**.
7. Spremeni opis in ponovno shrani.
8. Za test brisanja klikne **"Izbriši"** pri eni od vsebin.

### Pričakovani rezultat:
- Nova vsebina je uspešno dodana in prikazana v seznamu.
- Urejena vsebina vsebuje posodobljene podatke.
- Izbrisana vsebina se odstrani iz seznama in ni več dostopna.

---

## 3. Testni scenarij: Napredna iskalna funkcija

### Funkcionalnost:
Iskanje elementov po kategorijah in filtrih.

### Koraki izvedbe:
1. Uporabnik odpre stran z iskalnikom.
2. V iskalno polje vnese ime elementa (npr. "Statistika").
3. Izbere kategorijo (npr. "Poročila").
4. Uporabi filter (npr. datum ustvarjanja, status).
5. Klikne **"Išči"**.

### Pričakovani rezultat:
- Prikazan je seznam rezultatov, ki ustrezajo ključnim besedam, kategoriji in uporabljeni filtraciji.
- Če rezultatov ni, se prikaže sporočilo *"Ni najdenih rezultatov."*.
