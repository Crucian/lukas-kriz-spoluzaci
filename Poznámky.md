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
1) Globální prvky (3h)
>* Grid (2h)
>* Formuláře (2h)
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

### Školy (skoly_alt.psd)

1) Formulář v levé části (1h)
2) Blok školy (logov, název, adresa) (0,5h)
3) Stránkování / donačítání (0,5h)

### Třída (trida.psd)

1) Avatar, jméno, profil, výběr třídy, navigace (2h)
2) Blok konverzace (obecně) (2h)
>* Hover stav nad avatarem uživatele a slide (1h)
>* Zanoření reakce konverzace
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
   
---
### Formulář

Viz [Formuláře](#Obecné)

### Formulář třída (formular_trida.psd) 
---------------------------------
## Mobile
---------------------------------
### Homepage (home_mobil.psd)
### Škola (skola_mobil.psd) 
### Školy (skoly_mobil.psd)
### Třída (trida_mobil_2.psd)
---
### formular_mobil (formular.psd)
