---
typ: location
tags:
  - univerity
lokalizacja: "[[Arkham]]"
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
