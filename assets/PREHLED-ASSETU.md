# Přehled obrázkových souborů — Kastl Studio

Každý soubor nahradíte tak, že do složky `assets/` nahrajete **vlastní soubor se stejným názvem**
(stejná přípona, např. `.jpg`). Web ho pak automaticky použije na správném místě — nic jiného
upravovat nemusíte.

Číslo u každého souboru odpovídá číslu, které vidíte přímo na webu vedle daného obrázku/placeholderu.

---

## Hero fotky (pozadí v horní části stránky)

| # | Soubor | Stránka | Doporučený formát |
|---|--------|---------|--------------------|
| 01 | `HOME_hero_01.jpg` | Home (úvodní stránka) | šířka min. 1600 px, na výšku ořízne CSS |
| 02 | `PROFIL_hero_02.jpg` | Profil | šířka min. 1600 px |
| 03 | `B2B-VYROBA_hero_03.jpg` | B2B & Výroba | šířka min. 1600 px |
| 04 | `HISTORIE-KULTURA_hero_04.jpg` | Historie & Kultura | šířka min. 1600 px |
| 05 | `DOMACNOST-HOBBY_hero_05.jpg` | Domácnost & Hobby | šířka min. 1600 px |
| 06 | `KONTAKT_hero_06.jpg` | Kontakt | šířka min. 1600 px |

Tyto fotky mají přes sebe tmavý poloprůhledný filtr (kvůli čitelnosti bílého textu), takže i tmavší
nebo kontrastnější fotka bude fungovat dobře.

## Fotky vybavení (na stránce Profil)

| # | Soubor | Co na fotce | Doporučený formát |
|---|--------|-------------|---------------------|
| 07 | `PROFIL_sken_07.jpg` | 3D skener | poměr stran 4:3 |
| 08 | `PROFIL_tiskarna_08.jpg` | Tiskárna Bambu Lab X1D | poměr stran 4:3 |
| 09 | `PROFIL_material_09.jpg` | Materiály (cívky PETG/PCTG/PA) | poměr stran 4:3 |

## Velké fotky procesu (na stránkách služeb)

| # | Soubor | Stránka | Co na fotce | Doporučený formát |
|---|--------|---------|-------------|---------------------|
| 10 | `B2B-VYROBA_foto_10.jpg` | B2B & Výroba | sken/tisk průmyslového dílu | široký formát, cca 21:8 |
| 11 | `HISTORIE-KULTURA_foto_11.jpg` | Historie & Kultura | replika nebo skenování exponátu | široký formát, cca 21:8 |
| 12 | `DOMACNOST-HOBBY_foto_12.jpg` | Domácnost & Hobby | zakázkový výtisk | široký formát, cca 21:8 |

## Logo

| # | Soubor | Kde se používá | Poznámka |
|---|--------|-----------------|----------|
| 13 | `VSUDE_logo_13.svg` | Hlavička, všech 7 stránek | **Animované SVG** — pokud chcete upravit animaci, otevřete v textovém editoru (ne grafickém), animace je definovaná na konci souboru v `<animate>` značkách |
| — | `VSUDE_logo_13_zaloha.png` | Záložní statická verze (zatím nikde nepoužitá) | Pro případ, že byste chtěli logo i jako obyčejný obrázek bez animace |

## Ostatní

| # | Soubor | Stránka | Poznámka |
|---|--------|---------|----------|
| 14 | `KONTAKT_qrVizitka_14.png` | Kontakt | QR kód — generuje se z dat vizitky, při změně kontaktních údajů je třeba vygenerovat znovu (dejte vědět) |
| — | `kastl-studio.vcf` | Kontakt (tlačítko "Stáhnout vizitku") | Textový soubor s kontaktními údaji, needituje se jako obrázek — při změně údajů upravte přímo text souboru nebo dejte vědět |

---

## Jak nahradit fotku — krok za krokem

1. Najděte v tabulce výše přesný název souboru (např. `PROFIL_sken_07.jpg`)
2. Vaši novou fotku přejmenujte na **přesně stejný název** (včetně přípony — pokud bude soubor
   `.png` místo `.jpg`, je potřeba upravit i příslušný řádek v HTML, jinak fotka zmizí)
3. Nahrajte/přetáhněte soubor do složky `assets/` tak, aby přepsal ten starý
4. Otevřete `index.html` (nebo příslušnou stránku) v prohlížeči a zkontrolujte výsledek

**Tip:** Pokud si nejste jistí příponou souboru, nejjednodušší je vždy ukládat fotky jako `.jpg`
a zachovat přesně tento formát přípony jako v tabulce.
