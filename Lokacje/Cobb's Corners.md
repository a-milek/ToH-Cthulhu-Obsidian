---
typ: location
kampania: Drużyna B
tags:
  - city
lokalizacja: "[[Vermont]]"
---

## Lokalizacje
```dataview 
LIST FROM "Lokacje" WHERE contains(lokalizacja, this.file.link)
SORT file.name ASC
```
## Postacie
```dataview 
LIST FROM "NPC" WHERE contains(lokalizacja, this.file.link)
SORT file.name ASC
```