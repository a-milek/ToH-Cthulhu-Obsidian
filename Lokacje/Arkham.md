---
typ: location
tags:
  - city
lokalizacja:
---

## Lokalizacje
```dataview 
LIST FROM "Lokacje" WHERE contains(lokalizacja, [[Arkham]])
SORT file.name ASC
```
## Postacie
```dataview 
LIST FROM "NPC" WHERE contains(lokalizacja, [[Arkham]])
SORT file.name ASC
```