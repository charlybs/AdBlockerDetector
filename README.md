# AdBlockerDetector
![Dependencies](https://img.shields.io/badge/Dependencies-jQuery-green.svg)

Detecta si AdBlocker esta activo o no en la web.

# Modo de uso
Añade a tu sitio el archivo (en el head) `<script src="advertisement.js"></script>`

Y con este código determinas si AdBlock está o no activo:

```html
$(window).load(function() {
	  if ($("#adblock").length) {
	      //ADBLOCK DESACTIVADO
		}else{
		  //ADBLOCK ACTIVADO
		}
	});
```
