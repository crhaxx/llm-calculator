Název projektu: LLM CACLULATOR
Odkaz / kontext: Experimentální webový nástroj ve stylu nikolacrhak.cz

O čem to celé bude:
Web pomáhá rychle rozhodnout, jaký typ AI modelu dává nejlepší výsledek pro konkrétní prompt nebo zadání. Místo toho, aby se na všechno bral stejný model, aplikace vyhodnotí složitost zadání (délku, klíčová slova, typ úlohy, požadavky na přesnost, více kroků, strukturovaný výstup nebo větší kontext), spočítá skóre složitosti a doporučí nejvhodnější třídu/model AI spolu s krátkým zdůvodněním a odhadem náročnosti.

Co bude na 5 propojených stránkách:

1. Úvod (index.html) – vysvětlení principu směrování podle složitosti promptu, ukázky situací, obrázky, prvek s prompt() při najetí myší (např. rychlý odhad vlivu délky zadání).
2. Kritéria & Tipy (kriteria.html) – kdy použít rychlý model, kdy reasoning/analýzu a kdy kód/multimodalitu; postupy ladění zadání (<ol>) a znaky náročných promptů (<ul>).
3. Srovnání modelů (srovnani.html) – přehledná tabulka (<table>) tříd/modelů podle rychlosti, ceny a vhodnosti s využitím colspan a rowspan.
4. Analyzátor promptu (analyzator.html) – formulář (<form>) s textem promptu, volbou typu úlohy (radio), doplňkovými požadavky (checkbox), číselným parametrem a tlačítkem (<button>); výpočet složitosti a doporučení v externím script.js (včetně propojení s hodnotou z prompt()).
5. Metodika & Kontakt (metodika.html) – jak výpočet funguje, omezení odhadu, odkaz na nikolacrhak.cz a patička (<footer>).

Technický základ pro zadání:

- 5 propojených HTML stránek se společným menu a patičkou (<footer>).
- Samostatné soubory style.css a script.js (žádné inline styly ani skripty v HTML).
- Všechny povinné HTML značky, CSS vlastnosti a JS funkce (prompt na událost myši, getElementById, výpočet a vrácení výsledku uživateli).
