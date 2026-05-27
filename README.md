# MotionCare Fyzio – demo web

Demo prezentačný web pre fiktívne fyzioterapeutické štúdio **MotionCare Fyzio**.

Tento projekt slúži ako ukážka balíka **Web s online rezerváciou**. Cieľom je nacvičiť celý proces tvorby webu pre klienta, ktorý potrebuje prezentačnú stránku aj možnosť rezervovať termín cez externý rezervačný systém, napríklad Bookio.

---

## Typ projektu

Web pre fyzioterapiu / rehabilitáciu / športovú starostlivosť s online rezerváciou.

Web je vhodný ako základ pre podobné typy klientov:

- fyzioterapia,
- rehabilitácia,
- masáže,
- osobný tréner,
- pohybové štúdio,
- športová regenerácia,
- konzultácie,
- služby, kde sa pracuje s termínmi.

---

## Cieľ webu

Cieľom stránky je predstaviť službu tak, aby návštevník rýchlo pochopil:

- čo štúdio ponúka,
- s akými problémami pomáha,
- aké služby sú dostupné,
- ako prebieha prvá návšteva,
- aké sú orientačné ceny,
- kde sa štúdio nachádza,
- ako sa dá kontaktovať,
- ako si môže rezervovať termín online.

Web má pôsobiť ako reálna stránka pre klienta, nie ako technická ukážka.

---

## Použité technológie

- HTML
- CSS
- JavaScript
- GitHub Pages
- Bookio ako externý rezervačný systém
- Web3Forms pripravený pre kontaktný formulár
- Google Maps iframe pre mapu
- lokálne obrázky v priečinku `assets/`

---

## Štruktúra projektu

```txt
index.html
styles.css
script.js
README.md
assets/
```

Dôležité: súbor `index.html` musí byť priamo v hlavnom priečinku repozitára.

Správna štruktúra:

```txt
projekt/
  index.html
  styles.css
  script.js
  README.md
  assets/
```

Nesprávna štruktúra:

```txt
projekt/
  nejaky-vnutorny-priecinok/
    index.html
    styles.css
```

---

# Postup tvorby webu

## 1. Vymyslenie typu dema

Ako druhé demo bol zvolený balík:

```txt
Web s online rezerváciou
```

Na rozdiel od jednoduchej landing page má tento web ukázať aj napojenie na externý rezervačný systém.

Pre demo bol zvolený typ firmy:

```txt
Fyzioterapia / rehabilitácia
```

Názov fiktívnej značky:

```txt
MotionCare Fyzio
```

---

## 2. Vygenerovanie prvého návrhu webu

Na začiatku bol vytvorený základný návrh webu podľa požiadaviek:

- typ firmy: fyzioterapia,
- cieľ webu: služby, postup návštevy, cenník, kontakt, mapa, rezervácia,
- štýl: moderný, čistý, zdravotnícky, dôveryhodný,
- farby: biela, tmavá zelenomodrá, teal, mint,
- technológie: HTML, CSS, JavaScript,
- hosting: GitHub Pages,
- rezervácia: externý link na Bookio.

Výstupom bol ZIP súbor so základnými súbormi:

```txt
index.html
styles.css
script.js
README.md
assets/
```

---

## 3. Stiahnutie a rozbalenie ZIP súboru

Po vygenerovaní bol ZIP súbor stiahnutý a rozbalený do samostatného priečinka.

Následne sa skontrolovalo, či je `index.html` priamo v hlavnom priečinku projektu.

---

## 4. Otvorenie projektu vo VS Code

Projekt bol otvorený vo VS Code.

Upravovali sa hlavne tieto súbory:

- `index.html` – štruktúra a texty,
- `styles.css` – farby, layout, responzivita a dizajn,
- `script.js` – mobilné menu, animácie a dynamický rok vo footeri,
- `assets/` – logo, favicon, obrázky a vizuály,
- `README.md` – dokumentácia postupu.

---

## 5. Vytvorenie Git repozitára

V priečinku projektu sa otvoril terminál a spustili sa príkazy:

```bash
git init
git add .
git commit -m "Initial MotionCare Fyzio demo"
```

Potom bol na GitHube vytvorený nový repozitár.

Repozitár sa prepojil s lokálnym projektom:

```bash
git branch -M main
git remote add origin URL_REPOZITARA
git push -u origin main
```

---

## 6. Zapnutie GitHub Pages

Po nahratí projektu na GitHub sa zapol GitHub Pages:

```txt
GitHub repository
→ Settings
→ Pages
→ Deploy from branch
→ Branch: main
→ Folder: /root
→ Save
```

Po chvíli bol web dostupný na testovacej adrese:

```txt
https://pouzivatel.github.io/nazov-repozitara/
```

Táto adresa slúži ako testovacia verzia pred vlastnou doménou.

---

# Bookio setup

## 7. Vytvorenie Bookio účtu

Pre toto demo bol pripravený rezervačný model cez Bookio.

Základný postup:

1. Otvoriť Bookio.
2. Vytvoriť účet.
3. Prihlásiť sa do administrácie.
4. Vytvoriť prevádzku / firmu.
5. Nastaviť základné údaje prevádzky.
6. Pripraviť služby.
7. Nastaviť dostupné termíny.
8. Získať verejný rezervačný link.
9. Vložiť link do tlačidiel na webe.

---

## 8. Nastavenie prevádzky v Bookio

V Bookio sa nastaví fiktívna alebo reálna prevádzka.

Príklad pre demo:

```txt
Názov: MotionCare Fyzio
Typ: Fyzioterapia / rehabilitácia
Mesto: Bratislava
Adresa: Vajnorská 68, Bratislava
```

Pri reálnom klientovi treba doplniť jeho skutočné údaje:

- názov firmy,
- adresa,
- telefón,
- email,
- otváracie hodiny,
- prípadne logo,
- popis prevádzky,
- zamestnanci,
- služby.

---

## 9. Nastavenie služieb v Bookio

V Bookio sa vytvoria služby, ktoré si zákazník môže rezervovať.

Príklad služieb pre MotionCare Fyzio:

```txt
Vstupné vyšetrenie
Fyzioterapia
Rehabilitácia po zranení
Športová masáž
Manuálna terapia
```

Pri každej službe je vhodné nastaviť:

- názov služby,
- krátky popis,
- trvanie,
- cenu,
- dostupnosť,
- osobu, ktorá službu poskytuje,
- prípadné prestávky medzi termínmi.

Príklad:

```txt
Služba: Vstupné vyšetrenie
Trvanie: 60 min
Cena: 45 €
```

```txt
Služba: Fyzioterapia
Trvanie: 45 min
Cena: 39 €
```

```txt
Služba: Športová masáž
Trvanie: 45 min
Cena: 35 €
```

---

## 10. Nastavenie pracovných hodín

V Bookio treba nastaviť dostupné dni a časy.

Príklad:

```txt
Pondelok: 8:00 – 18:00
Utorok: 8:00 – 18:00
Streda: 8:00 – 18:00
Štvrtok: 8:00 – 18:00
Piatok: 8:00 – 18:00
Sobota: zatvorené
Nedeľa: zatvorené
```

Treba skontrolovať:

- či sa termíny zobrazujú verejne,
- či nie sú všetky dni zatvorené,
- či služba má priradenú dostupnosť,
- či sa dá reálne vytvoriť rezervácia.

---

## 11. Nastavenie zamestnanca / poskytovateľa služby

Ak Bookio vyžaduje zamestnanca alebo poskytovateľa služby, treba ho pridať.

Príklad:

```txt
Meno: MotionCare Fyzio
Rola: Fyzioterapeut
Služby: Vstupné vyšetrenie, Fyzioterapia, Športová masáž
```

Pri reálnom klientovi sa nastaví skutočné meno alebo názov pracovníka.

---

## 12. Nastavenie pravidiel rezervácie

V Bookio je vhodné nastaviť základné pravidlá:

- ako dlho dopredu sa dá rezervovať,
- či sa dá rezervácia zrušiť,
- koľko času pred termínom sa dá rezervácia vytvoriť,
- či sú povolené online platby,
- či sa posielajú emailové alebo SMS pripomienky,
- či klient dostane potvrdenie rezervácie.

Pre demo stačí jednoduché nastavenie bez platieb.

Pri reálnom klientovi sa treba dohodnúť, či chce:

- len rezervácie,
- platby vopred,
- zálohy,
- SMS pripomienky,
- emailové pripomienky,
- storno pravidlá.

---

## 13. Získanie rezervačného linku z Bookio

Po nastavení Bookio treba nájsť verejný rezervačný link.

V Bookio administrácii treba hľadať sekcie typu:

```txt
Online rezervácie
Rezervačná stránka
Zdieľať
Rezervačný link
Widget na web
Integrácia na web
Booking page
Public link
```

Najjednoduchší postup:

1. Otvoriť náhľad verejnej rezervačnej stránky.
2. Skontrolovať, že sa dá vybrať služba a termín.
3. Skopírovať URL z prehliadača.
4. Vložiť ju do tlačidiel na webe.

---

## 14. Vloženie Bookio linku do webu

V HTML sa nahradí pôvodný placeholder link:

```html
href="https://www.bookio.com/"
```

reálnym rezervačným linkom.

Príklad:

```html
<a href="TVOJ_BOOKIO_LINK" target="_blank" rel="noopener noreferrer" class="btn btn-primary">
  Rezervovať termín
</a>
```

Treba nahradiť všetky miesta, kde sa používa rezervačný link:

- tlačidlo v navigácii,
- tlačidlo v hero sekcii,
- tlačidlo v rezervačnej sekcii,
- prípadne link vo footeri.

---

## 15. Testovanie Bookio rezervácie

Po vložení linku treba otestovať:

- či sa link otvorí v novej karte,
- či sa otvorí správna rezervačná stránka,
- či sa dá vybrať služba,
- či sú viditeľné voľné termíny,
- či sa dá vyplniť formulár,
- či príde potvrdenie,
- či sa rezervácia zobrazí v Bookio administrácii.

---

# Úprava webu

## 16. Úprava textov na reálnu stránku

Pôvodné technické texty boli upravené tak, aby stránka pôsobila ako reálny web pre klienta.

Odstránili sa formulácie typu:

```txt
Po vytvorení reálneho Bookio účtu sa sem vloží konkrétny rezervačný link.
```

Nahradili sa textami typu:

```txt
Vyberte si službu, voľný termín a odošlite rezerváciu online.
```

Dôležité pravidlo:

Na verejnej ukážke nemajú byť interné poznámky pre tvorcu webu. Texty majú byť písané pre zákazníka danej firmy.

---

## 17. Hero sekcia

Hero sekcia obsahuje:

- hlavný nadpis,
- krátky popis služby,
- CTA tlačidlo na rezerváciu,
- tlačidlo na zavolanie,
- hlavný vizuál,
- malé informačné kartičky.

Príklad CTA:

```html
<a href="TVOJ_BOOKIO_LINK" target="_blank" rel="noopener noreferrer" class="btn btn-primary">
  Rezervovať termín
</a>
```

---

## 18. Služby

Sekcia služieb obsahuje 4 hlavné služby:

- bolesť chrbta a krku,
- rehabilitácia po zranení,
- športová fyzioterapia,
- manuálna terapia.

Každá služba má:

- obrázok alebo ikonu,
- názov,
- krátky popis.

Pri reálnom klientovi sa služby upravia podľa jeho ponuky.

---

## 19. Postup návštevy

Sekcia „Ako prebieha návšteva“ vysvetľuje proces:

1. vstupný rozhovor,
2. pohybové vyšetrenie,
3. terapia a cvičenie,
4. odporúčanie domov.

Táto sekcia pomáha budovať dôveru, hlavne pri zdravotníckych alebo poradenských službách.

---

## 20. Cenník

Cenník je orientačný.

Obsahuje:

- vstupné vyšetrenie,
- fyzioterapiu,
- športovú masáž.

Pri reálnom klientovi treba upraviť:

- názvy služieb,
- ceny,
- dĺžku termínu,
- čo je zahrnuté v cene.

---

## 21. Rezervačná sekcia

Rezervačná sekcia má jasne vysvetliť, že zákazník si vie vybrať termín online.

Text by mal byť jednoduchý:

```txt
Vyberte si službu, voľný termín a odošlite rezerváciu online.
```

Tlačidlá:

- Rezervovať online,
- Mám otázku.

Logika:

```txt
Rezervovať termín → Bookio
Mám otázku → kontaktný formulár
```

---

## 22. Kontaktný formulár

Aj keď je na webe Bookio, kontaktný formulár môže zostať.

Bookio slúži na:

```txt
rezerváciu termínu
```

Kontaktný formulár slúži na:

```txt
otázky pred prvou návštevou
nejasné problémy
odporúčanie vhodnej služby
všeobecný kontakt
```

Preto formulár nie je rezervačný, ale poradenský / kontaktný.

Príklad selectu:

```html
<label>
  S čím potrebujete poradiť?
  <select name="service" required>
    <option value="">Vyberte možnosť</option>
    <option>Bolesť chrbta alebo krku</option>
    <option>Rehabilitácia po zranení</option>
    <option>Športové preťaženie alebo regenerácia</option>
    <option>Potrebujem odporučiť vhodnú službu</option>
    <option>Mám všeobecnú otázku</option>
  </select>
</label>
```

---

## 23. Web3Forms

Formulár je pripravený cez Web3Forms.

V HTML je:

```html
<input type="hidden" name="access_key" value="TVOJ_WEB3FORMS_ACCESS_KEY" />
```

Pre reálne fungovanie treba:

1. vytvoriť Web3Forms access key,
2. vložiť ho do HTML,
3. nastaviť predmet emailu,
4. otestovať odoslanie,
5. skontrolovať doručenie emailu.

Predmet emailu:

```html
<input type="hidden" name="subject" value="MotionCare Fyzio – nový dopyt z webu" />
```

---

## 24. Kontakt a mapa

Kontaktná sekcia obsahuje:

- email,
- telefón,
- adresu,
- otváracie hodiny,
- mapu.

Email:

```html
mailto:
```

Telefón:

```html
tel:
```

Mapa je vložená cez Google Maps iframe.

Príklad:

```html
<div class="map-card">
  <iframe
    src="https://www.google.com/maps?q=Vajnorska%2068,%20Bratislava,%20Slovensko&output=embed"
    width="100%"
    height="320"
    style="border:0;"
    allowfullscreen=""
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>
</div>
```

---

## 25. Sociálne siete

Do navigácie boli pridané ikonky sociálnych sietí:

- Instagram,
- Facebook,
- TikTok.

Externé odkazy musia mať:

```html
target="_blank" rel="noopener noreferrer"
```

Pri reálnom klientovi treba nahradiť demo odkazy skutočnými profilmi.

---

## 26. Testovanie webu

Po úpravách treba otestovať:

- desktop verziu,
- mobilnú verziu,
- navigáciu,
- scrollovanie na sekcie,
- tlačidlo „Späť hore“,
- klik na telefón,
- klik na email,
- sociálne siete,
- mapu,
- kontaktný formulár,
- Bookio rezervačný link,
- favicon,
- logo,
- responzivitu,
- rýchlosť načítania.

---

## 27. Commit a push zmien

Po každej väčšej úprave:

```bash
git add .
git commit -m "Update MotionCare Fyzio website"
git push
```

GitHub Pages následne automaticky aktualizuje verejnú verziu webu.

---

# Podklady od reálneho klienta

Pri reálnom klientovi treba získať:

- názov firmy,
- logo,
- email,
- telefón,
- adresu,
- otváracie hodiny,
- zoznam služieb,
- cenník,
- fotografie,
- sociálne siete,
- preferované farby,
- informáciu, či chce online rezerváciu,
- informáciu, či už má Bookio účet,
- informáciu, či má doménu,
- informáciu, či chce mesačnú správu.

---

# Odovzdanie klientovi

Po dokončení webu:

1. poslať klientovi testovací link,
2. prejsť pripomienky,
3. zapracovať úpravy,
4. skontrolovať mobilnú verziu,
5. otestovať formulár,
6. otestovať Bookio rezerváciu,
7. otestovať odkazy,
8. napojiť doménu,
9. spustiť finálnu verziu,
10. odovzdať web,
11. dohodnúť prípadnú mesačnú správu.

---

# Čo treba riešiť pred ostrým nasadením

- vlastná doména,
- DNS nastavenia,
- HTTPS,
- finálne kontaktné údaje,
- funkčný formulár,
- reálny Bookio rezervačný link,
- reálne fotografie,
- finálne texty,
- SEO title,
- meta description,
- favicon,
- Open Graph obrázok,
- responzívne zobrazenie,
- rýchlosť načítania,
- funkčnosť všetkých odkazov.

---

# Checklist pre ďalší web s online rezerváciou

- [ ] Získať informácie od klienta
- [ ] Zistiť, či klient má rezervačný systém
- [ ] Ak nemá, založiť / nastaviť Bookio alebo iný systém
- [ ] Nastaviť prevádzku v Bookio
- [ ] Nastaviť služby
- [ ] Nastaviť trvanie služieb
- [ ] Nastaviť ceny
- [ ] Nastaviť otváracie hodiny
- [ ] Nastaviť dostupnosť termínov
- [ ] Otestovať verejný rezervačný link
- [ ] Vložiť rezervačný link do webu
- [ ] Získať alebo vytvoriť logo
- [ ] Získať fotky od klienta
- [ ] Pripraviť štruktúru webu
- [ ] Upraviť texty podľa klienta
- [ ] Upraviť farby podľa brandingu
- [ ] Doplniť služby
- [ ] Doplniť cenník
- [ ] Doplniť kontaktné údaje
- [ ] Doplniť sociálne siete
- [ ] Doplniť mapu
- [ ] Nastaviť kontaktný formulár
- [ ] Otestovať klik na telefón
- [ ] Otestovať email
- [ ] Otestovať sociálne siete
- [ ] Otestovať mapu
- [ ] Otestovať formulár
- [ ] Otestovať Bookio rezerváciu
- [ ] Otestovať mobilnú verziu
- [ ] Otestovať desktop verziu
- [ ] Nahrať na GitHub
- [ ] Zapnúť GitHub Pages
- [ ] Poslať klientovi testovací link
- [ ] Zapracovať pripomienky
- [ ] Napojiť doménu
- [ ] Finálne odovzdať web

---

# Poznámky do budúcna

Tento projekt predstavuje druhý balík služieb:

```txt
Web s online rezerváciou
```

Rozdiel oproti jednoduchej landing page:

- web má rezervačné CTA,
- používa externý rezervačný systém,
- návštevník si vie vybrať termín,
- kontaktný formulár slúži iba na otázky,
- web má vyššiu hodnotu pre klienta.

Pri ďalšom podobnom webe sa dá použiť rovnaký základ:

- navigácia,
- hero sekcia,
- služby,
- postup,
- cenník,
- rezervačná sekcia,
- kontakt,
- mapa,
- formulár,
- footer.

Pri každom klientovi sa mení hlavne:

- názov,
- logo,
- farby,
- texty,
- fotky,
- služby,
- ceny,
- kontakty,
- sociálne siete,
- mapa,
- rezervačný link.
