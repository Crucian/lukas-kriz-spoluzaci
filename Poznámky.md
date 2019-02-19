# Poznámky k projektu Spolužáci a nacenění prací

* [Obecné](#Obecné)
* [Desktop](#Desktop)
  * [Homepage](#Homepage) (home_alt.psd)
  * [Škola](#Škola) (skola.psd) 
  * [Školy](#Školy) (skoly_alt.psd)
  * [Třída](#Třída) (trida.psd)
    * [Formulář třída](#Formulář třída) (formular_trida.psd) 
  * [Formulář](#Formulář) (formular.psd)
* [Mobile](#Mobile)
  * [Homepage](#Homepage) (home_mobil.psd)
  * [Škola](#Škola) (skola_mobil.psd) 
  * [Školy](#Školy) (skoly_mobil.psd)
  * [Třída](#Třída) (trida_mobil_2.psd)
  * [Formulář](#Formulář) (formular_mobil.psd)

## Dotazy
1) Co znamená sufix **_alt** v názvech dokumentů **.psd**
2) Existuje nějaké barevné schéma, kterého se budeme držet (manuál), nebo si mám barvy vytahovat kapátkem z daných prvků v **.psd**?

## Obecné
1) Globální prvky (11.5h)
>* Grid (2h)
>* Formuláře (4h)
>* Stavy (0.5h)
>* Tlačítka (1h)
>* Hlášky (1h)
>* Ikonový systém (3h)
2) Lytebox / dialogy (vyvolané ve vrstvě) - login (1h)
3) Loading (částečně již připraven) (1h)
4) Tooltipy (1h)

## Desktop

### Main (vzejde z obecné hlavičky/patičky)

1) Hlavička (0.5h)
2) Patička (0.5h)

### Homepage (home_alt.psd)

1) Základní rozvržení (1h)
2) Hlavní pozadí + animace rukou (dle domluvy loop/delay/stop) (2h)
3) U otevřeného inputu pro **Vyhledávání školy** je jakýsi *našeptávač*, pouze skrze SCSS nepůjde nastylovat. 
   
   > **Dotaz:** 
   Budeš to programovat a simulovat systémové chování, nebo tam bude nějaký modul **autocomplete**?

4) Mapa (celem 4h)
>* Rozdělení na regiony a příprava stavů hover/active a mapy obecně (3h)
>* Seznam ragionů (1h)

   > **Dotaz:** 
   Bude provázaný s mapou? Najetím na text se bude označovat region na mapě a obráceně? Chceš tam připravit nějaká ID do regionů, až to budu kodovat?

### Subpage
1) Rozvržení (1h)
>* Levý sloupec
>* Pravý sloupec

#### Škola (skola.psd) 

1) Logotyp/avatar, název, adresa školy (1h)
2) Blok s formulářem pro *rok ukončení* a jeho výpočet (1h)
3) Blok ročníku + výpis tříd v ročníku (2h)
4) Blok přidání třídy (1h)

#### Školy (skoly_alt.psd)

1) Formulář v levé části (1h)
2) Blok školy (logov, název, adresa) (0,5h)
3) Přihlásit / registrovat (0,5h)
4) Stránkování / donačítání (0,5h)

#### Třída (trida.psd)

1) Avatar, jméno, profil, výběr třídy, navigace (2h)
2) Blok konverzace (obecně) (2h)
>* Hover stav nad avatarem uživatele a slide (1h)
>* Zanoření reakce konverzace (0.25)
>* Ikony (0,5h)
>* Emoticons (dropdown) (1h)

   > **Dotaz:** 
   Máme k dispozici celou sadu, kterou chceme používat, nebo je třeba ji vytvořit? Aktuálně v grafice vidím pouze nástřel toho, kde budeme zobrazovat. Všechny ikony jsou, až na jednu, shodné.

3) Záhlaví (profil/přihlášený uživatel, iconbar)
>* Notifikace (1h)
>* Nastavení

   > **Dotaz:** 
   Vede do stránky profilu?

>* Zámek

   > **Dotaz:** 
   Kam vede/co dělá?
   
#### Formulář

Viz [Formuláře](#Obecné) / nebude potřeba více času

#### Formulář třída (formular_trida.psd) 

Viz [Formuláře](#Obecné) / nebude potřeba více času


---------------------------------
## Mobile
---------------------------------
### Obecné reponsivní chování
1) Globální prvky (celkem 4h)
>* Grid (1h)
>* Formuláře (0.5h)
>* ~~Stavy~~ (0h)
>* ~~Tlačítka~~ (0h)
>* ~~Hlášky~~ (0h)
>* Ikonový systém (1h)
2) Lytebox / dialogy (vyvolané ve vrstvě) - login (0.5h)
3) Loading (částečně již připraven) (0.5h)
4) Tooltipy (0.5h)

### Main (vzejde z obecné hlavičky/patičky)

1) Hlavička (0.25h)
2) Patička (0.25h)

### Homepage (home_mobil.psd)

1) Základní rozvržení (1h)
2) Hlavní pozadí + animace rukou (dle domluvy loop/delay/stop) (1h)
3) Mapa (1h)

### Subpage
1) Rozvržení (0.25h)
>* Levý sloupec
>* Pravý sloupec

#### Škola (skola_mobil.psd) 

1) Logotyp/avatar, název, adresa školy (0.5h)
2) Blok s formulářem pro *rok ukončení* a jeho výpočet (1h)
3) Blok ročníku + výpis tříd v ročníku (1h)
4) Blok přidání třídy (0.25h)

#### Školy (skoly_mobil.psd)

1) Formulář/filtr v levé části (0.5h)
2) Blok školy (logo, název, adresa) (0,5h)
3) Přihlásit (0,25h)
4) ~~Stránkování / donačítání~~ (0h)

#### Třída (trida_mobil_2.psd)

1) Avatar, jméno, profil, výběr třídy, navigace (0.5h)
2) Blok konverzace (obecně) (0.25h)
>* ~~Hover stav nad avatarem uživatele a slide~~ (0h)
>* ~~Zanoření reakce konverzace~~ (0h)
>* Ikony (0.25h)
>* Emoticons (dropdown) (0.25h)
3) Záhlaví (profil/přihlášený uživatel, iconbar)
>* Notifikace (0.5h)
>* ~~Nastavení~~ (0h)
>* ~~Zámek~~ (0h)

#### formular_mobil (formular.psd)

Viz [Formuláře](#Obecné) / nebude potřeba více času
