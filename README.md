**Shrnutí a porovnání**

**Algoritmus 1**: find_number_in_dataset

**Princip**: Prochází seznam prvek po prvku, dokud nenajde hledané číslo nebo nedosáhne konce seznamu.

**Časová složitost**: O(n) – čas potřebný k provedení algoritmu roste přímo úměrně velikosti vstupního seznamu.

**Výhody**: Jednoduchý.

**Nevýhody**: Není efektivní pro velké seznamy, zejména pokud je hledané číslo až na konci nebo se v seznamu vůbec nenachází.


**Algoritmus 2**: binary_search

**Princip**: Opakovaně dělí seřazený seznam na poloviny, dokud nenajde hledané číslo nebo nezjistí, že se v seznamu nenachází.

**Časová složitost**: O(log n) – čas potřebný k provedení algoritmu roste logaritmicky s velikostí vstupního seznamu. To znamená, že i pro velmi velké seznamy bude vyhledávání velmi rychlé.

**Výhody**: Velmi efektivní pro velké seřazené seznamy.

**Nevýhody**: Vyžaduje, aby byl vstupní seznam seřazen.


**Závěr**
Binární vyhledávání je obecně mnohem efektivnější než lineární vyhledávání pro velké seřazené seznamy. Pokud je však seznam malý nebo není potřeba přesná časová složitost, může být lineární vyhledávání jednodušší a dostačující.
