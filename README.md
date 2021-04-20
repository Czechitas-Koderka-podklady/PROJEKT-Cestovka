# Cestovka

Dobrovolný úkol pro kurz Staň se kóderkou od Czechitas.

- [Cíl úkolu](#Cíl-úkolu)
- [Grafické zadání](#Grafické-zadání)
- [Jak si stáhnout podklady](#Jak-si-stáhnout-podklady)

Než začneš s projektem cokoliv dělat, přečti si prosím celý tento text až do konce.

Za úkol máš nakódovat design podle grafického návrhu. Jedná se o úvodní stránku webu, kde se prodávají zájezdy. Na výsledný vzhled projektu se podívej na obrázku *ukazka-vysledku.jpg*.

Tentokrát máš k dispozici opět jenom zadání v podobě grafického návrhu vyexportovaného v módu pro vývojáře z Adobe XD.

![Ukázka výsledku](ukazka-vysledku.jpg)


## Cíl úkolu

Cílem projektu je procvičit si použití různých technik:
- **Vytvoření stránky z nuly**
  - tentokrát nemáš připravený žádný kód
  - udělej si klon repozitáře a v něm si sama vytvoř HTML a CSS soubor, připoj písma, stáhni obrázky
- **Práce s grafickým návrhem**
  - v tomto projektu máš jako podklady [grafický návrh vyexportovaný z Adobe XD](https://xd.adobe.com/view/50cee100-59ff-473d-b34a-cbf85b2a7b04-059d/grid/)
  - v návrhu si sama změříš potřebné rozměry, vyexportuješ si z něho obrázky, zjistíš barvy a použitá písma
  - pokud ještě nevíš jak na to, návod jak pracovat s návrhem, najdeš v [krátkém YouTube videu (20 min)](https://youtu.be/1ih_ZYdmNPU)
  - obrázky jdou z návrhu vyexportovat z mobilního, tabletového i počítačového rozložení, ale stále se jedná o ty stejné obrázky (6 fotek, 4 ikony, 1 logo) - stačí je tedy vyexportovat jednou z jakékoliv verze
- **Responzivní webdesign**
  - stránka je plně responzivní - má mobilní, tabletovou i počítačovou verzi
  - všechny responzivní varianty jsou obsažené v grafickém návrhu
- **Grid a flexbox**
  - stránka je navržená tak, aby byla extrémně jednoduše vyrobitelná pomocí CSS gridu
  - nezapomeň ale na flexbox - jsou místa, kde ho můžeš taky použít (např. rozmístění cenovky a názvu+popisu zájezdu v rámečcích s fotkami na pozadí)
  - nemusíš dělat z celé stránky jeden velký grid. Můžeš mít na stránce sekce, které jsou tvořené samostatnými menšími gridy
- **BEM a komponentové myšlení**
  - snaž se použít konvenci BEM pro pojmenování tříd
  - přemýšlej komponentově - pokud se nějaký prvek používá na stránce opakovaně, zaslouží si být samostatnou komponentou (v terminologii BEMu jim řikáme *blok*)
  - nezapomeň, že bloky mohou obsahovat jiné bloky
- **Sass**
  - pokud si troufáš, použij Sass
  - můžeš si vytvořit proměnné, které můžeš používat skrze celé CSS - barvy, písma, velikosti standardních rozestupů
  - určitě se ti bude hodit i vnořování prvků nebo media query
  - umíš-li už rozdělit CSS pomocí Sassu na více dílčích souborů, toto je ideální úkol, kde si to můžeš vyzkoušet


## Grafické zadání

Všechny potřebné obrázky, rozměry, použitá písma, barvy, apod. najdeš online v [grafickém návrhu vyexportovaném z Adobe XD](https://xd.adobe.com/view/50cee100-59ff-473d-b34a-cbf85b2a7b04-059d/grid/).

Pro případ, že bys chtěla pracovat offline nebo si chtěla s návrhem hrát, ve složce *Adobe-DX-navrh* máš k dispozici soubor *Cestovka.xd*, který si můžeš otevřít v Adobe XD u sebe na počítači (máš-li Adobe XD nainstalované). Pro vypracování úkolu to není nutné - stačí ti online verze, na kterou je odkaz o odstavec výše.

Grafický návrh obsahuje 3 plátna s rozložením webu pro mobil, tablet a počítač a 1 plátno s poznámkami k návrhu.

Nevíš-li, jak s návrhem pracovat, podívej se na [krátké YouTube video (20 min)](https://youtu.be/1ih_ZYdmNPU), kde ti vše ukážeme.


## Jak si stáhnout podklady

1. Udělej si **fork** této repozitáře - tím se ti úkol zkopíruje do tvého GitHub profilu.
2. Forknutou repozitář si naklonuj k sobě na disk.

Pokud nevíš, co je to **fork repozitáře** a jak ho provést, podívej se na [krátké video](https://youtu.be/K7rE3jRCjD4).
