# AdBlockerDetector
![Dependencies](https://img.shields.io/badge/Dependencies-jQuery-green.svg)

Detecta si AdBlocker esta activo o no en la web.

# Modo de uso
Añade a tu sitio el archivo (head) `<script src="advertisement.js"></script>`

Y con este código (advertisement.js debe de haberse cargado) determinas si AdBlock está o no activo:

```
if (document.getElementById("adblock")!=null) {
        //adblock is OFF
    }else{
        //adblock is ON
}
```
