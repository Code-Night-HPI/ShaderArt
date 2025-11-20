# ShaderArt
* Kunst durch Mathematik  
```
Willkommen zu unserem Vortrag über ShaderArt.   
Er gliedert sich in zwei Teile:
```  
* Shader
* Art
# Shader
* sind Programme, die auf der GPU laufen
* laufen parallel
* sind schnell
* für viele Daten
## Pixel-Shader
* spezieller Typ
* für jedes Pixel
* berechnet Farbe
## Shader als Funktion
* Input
    * Koordinaten
    * optionale Zusätze
* Body
    * Shadercode
* Output
    * RGB-Farbe
## Shadercode
### 0D
* Eine konstante Farbe
* unabhängig von allem
### 1D
* Farbverlauf
* abhängig von uv.x oder uv.y
### 2D
* 2D-Farbverlauf
* abhängig von uv.x und uv.y
## Beispiele
* UI
* Spiele
### Komplexere Shader
* Checkerboard
* Kreis
### Input
* float
    * time
    * sound
* vector
    * mouse position
* Image
    * heightmap
    * noise
    * Texture
### 3D
## Beispiele
* Spiele
* Simulationen
* Architektur
# Art
## SDF
* signed distance function
* Input
    * 2D-Vector postion
* Output
    * float distance
* Fälle
    * Outside: Positive
    * At boder: Zero
    * Inside: negative
## Fractal
