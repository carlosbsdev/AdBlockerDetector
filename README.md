# AdBlockerDetector

Detecta si AdBlocker esta activo o no en la web.

# Modo de uso
Añade a tu sitio el archivo (justo antes del </body>) `<script src="advertisement.js"></script></body>`

Y con este código (advertisement.js debe de haberse cargado) determinas si AdBlock está o no activo:

```
//Script insertado dentro del <head>.
window.onload = function(){
    if (document.getElementById("adblock")!=null) {
            //adblock is OFF
        }else{
            //adblock is ON
    }
}
```
