---
nombre: "Organizacion"
NoteType: organizacion
cssclasses:
 - cards
 - cards-cols-3 #Cambiar esta según cuántas tarjetas se quiere por fila
imagen: [[]] #Borrar paréntesis una vez importada la imagen
tags:
  - WIP
aliases:
  - 
personaAlCargo: "[[Sarah]]"
tipoOrg: 
---

>[!infobox]
># **`=this.title`**
> `=embed(link(this.imagen))`
> 
> || Información |
> | -------------- | -------------- |
> | Persona al cargo | `=this.personaAlCargo`  |
> | Tipo de organización | `=this.tipoOrg` |


#Party 
Party de rango filo perdido(C) de las [[Espadas libres de Eris]], basada en [[Faelas]].

**Miembros**
```dataview
TABLE without ID embed(link(imagen, "500x500")) as "Portrait", file.link as "Nombre"
FROM #hojasDeRan //Filtra por tag aquí, ej. #comendador 
SORT title ASC
```


### Historia

#### Fundación

#### Intervenciones relevantes