# Platzom

Platzom es un idioma inventado en js

## Descripcion del idioma

- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o mas letras,se debe partir a la mitad y unir con un guion del medio
- Si la palabra original es un palindromo,ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayusculas y minusculas

## Instalacion

```
npm install platzom
```

## Uso

```
import platzom from "platzom"

platzom("Programar") //Program
platzom("Zorro") // Zorrope
platzom("Zarpar"))// Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Creditos
- [Diego Marvid](https://facebook.com/diegomarvid)

## Licencia

[MIT](https://opensource.org/licenses/MIT)