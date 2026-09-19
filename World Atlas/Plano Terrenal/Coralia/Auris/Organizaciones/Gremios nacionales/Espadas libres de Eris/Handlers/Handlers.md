---
cssclasses:
 - cards
 - cards-cols-2 
---
Los aventureros que formen parte del gremio tendrán un/una handler encargado de seguirles en las misiones y documentar sus acciones progreso. Su informe tendrá un peso directo en el ranking y en los puntos gremiales que reciben de cada misión.

###### Miembros
```dataview
TABLE without ID embed(link(imagen, "500x500")) as "Portrait", file.link as "Nombre"
FROM #handlers 
SORT title ASC
```



