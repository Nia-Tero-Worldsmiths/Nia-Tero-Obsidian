---
title: 
NoteType: region
publish: false
tags:
  - WIP
aliases:
  - 
ubicacion: "[[Región]]"
gobernador: "[[Persona]]"
perteneceA: "[[Organización]]"
---

>[!infobox]
># **`=this.title`**
> 
> | Información    ||
> | ---------------- | -------------- |
> | Ubicado en        | `=this.ubicacion` |
> | Gobernado por  | `=this.gobernador` |
> | Pertenece a       | `=this.perteneceA` |

DESCRIPCIÓN


### Ubicaciones de la región 
```dataview
list 
where ubicacion = this.file.link
```
