---
typ: location
tags: 
lokalizacja:
---
## Występowanie
```dataview 

LIST FROM "sesje" WHERE contains(file.outlinks, this.file.link) AND !contains(file.name, "questy")
```