---
nombre: "Organizacion"
NoteType: organizacion
cssclasses:
 - cards
 - cards-cols-2 #Cambiar esta según cuántas tarjetas se quiere por fila
imagen: [[]] #Borrar paréntesis una vez importada la imagen
tags:
  - WIP
  - party
aliases:
  - 
personaAlCargo: "[[Persona]]"
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

Texto introductorio

#### Estructura
Descripción de la estructura. Separar en tantas subsecciones como se quiera

###### Miembros
```dataview
TABLE without ID embed(link(imagen, "500x500")) as "Portrait", file.link as "Nombre"
FROM #vigiliaAurea  //Filtra por tag aquí, ej. #comendador 
SORT title ASC
```


### Historia

#### Fundación


#### Intervenciones relevantes