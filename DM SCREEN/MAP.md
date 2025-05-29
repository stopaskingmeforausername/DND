```leaflet  
id: World_Map
lock: true  
recenter: true  
noScrollZoom: false 
image: [[world_map_alpha.png]]  
### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)  
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100)  
bounds: [[0,0], [1008,1294]]  
height: 508px  
width: 80%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 504 
long: 647 
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: -1.5  
### Max zoom is 18.  
maxZoom: 1.5  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: -1  
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: miles  
scale: 1  
darkMode: false  
```


