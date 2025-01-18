---
title: "Región de Tambler"
NoteType: region
draft: false
tags:
  - WIP
aliases:
  - Tambler
ubicacion: "[[Teocracia Magna]]"
gobernador: "[[Conde Lucán de Tambler]]"
perteneceA: "[[Gobierno de la Teocracia Magna]]"
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

>[!infobox]
># **`=this.title`**
> 
> | Información    ||
> | ---------------- | -------------- |
> | Ubicado en        | `=this.ubicacion` |
> | Gobernado por  | `=this.gobernador` |
> | Pertenece a       | `=this.perteneceA` |

La región de Tambler es el territorio más externo de la Teocracia Magna, situado en el Noreste de la misma.

### Historia
La región de Tambler fue la última en ser anexionada al país en sus campañas expansionistas, antes de que estas quedaran estancadas hace siglos. La conquista de este territorio fue posible gracias al Marqués Tambler de la época, quien en agradecimiento recibió el título elevado de Conde y el gobierno de la misma.

### Sociopolítica
#### Demografía


#### Gobierno


#### Núcleos de poder


### Geografía
Tambler es una región de terreno heterogéneo donde abundan tanto las planicies y llanuras como las colinas y sierras poco escarpadas. Esto favorece diversos tipos de industria, por lo que en esta región se realiza minería, ganadería, tala de árboles y, en menor medida, agricultura.

Las zonas verdes de la región se localizan enteramente en los dos tercios Oeste de la misma, ya que debido a la influencia de Rond-Fort en el ecosistema a su alrededor, la zona este de la región es un pantanal inhabitable.

### Turismo
Existen dos tipos de turismos fácilmente diferenciables en la región. Primeramente está el turismo interno de peregrinaje que se puede encontrar en [[Montelegro]], ciudad de alta importancia religiosa. [[Velmonte]], la capital, es una de las escasas ciudades de la Teocracia en las que existe turismo internacional, gracias a su famoso puerto comercial.

### Ubicaciones de la región 
```dataview
list 
where ubicacion = this.file.link
```
