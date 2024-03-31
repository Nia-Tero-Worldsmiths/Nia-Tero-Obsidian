---
nombre: 
NoteType: region
tags:
  - WIP
aliases:
  - 
ubicacion: "[[]]"
gobernador: "[[]]"
perteneceA: "[[]]"
---

## Mapa de la región

```leaflet
### Tutorial: https://youtu.be/54EyMzJP5DU
### id must be unique
id: Tambler_Map
### Lock pins so they can't be moved
lock: true
### If true, view of map will recenter as you zoom out. 
recenter: true
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work. 
noScrollZoom: false
image: [[Tambler.jpg]]
### The idea is to calculate how many pixels are equal to 1 unit. Use the excel sheet
bounds: [[0,0], [51.89, 69.19]]
height: 500px
width: 95%
### This sets where the map starts by default. Set it to the middle (half) of your bounds. 
lat: 25.95
long: 34.59
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map. 
minZoom: 3
### Max zoom is 18. 
maxZoom: 4.5
### Hover mouse over the Reset Zoom icon to see your current zoom level. 
defaultZoom: 3.3
### How far it zooms in or out with each step. Can be in decimals. 
zoomDelta: 0.3
### This is a string so can be any text. Change it to match your maps measurement scale. 
unit: km
scale: 1
darkMode: false
```

---

### Use this to calculate the bounds and then delete

<iframe
    height = 400
    width = 100%
    padding = 0 0
    margins = 0 0
    src="https://docs.google.com/spreadsheets/d/1i8GVjEcqn4uZUA5XgPaFlVFbcWwMwAqzY1TeOG2-g9s/edit?usp=sharing"></iframe>

>[!infobox]
># **`=this.nombre`**
> 
> | Información    ||
> | ---------------- | -------------- |
> | Ubicado en        | `=this.ubicacion` |
> | Gobernado por  | `=this.gobernador` |
> | Pertenece a       | `=this.perteneceA` |

TEXTO INTRODUCTORIO

### Geografía



### Historia



### Turismo



### Ubicaciones de la región 
```dataview
list 
where ubicacion = this.file.link
```
