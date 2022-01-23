# Cabecera H1
## H2
### h3
#### Cabecera h4
##### Cabecera H5
###### H6

Underline 1
_________________

Underline2
===========

Soy un Readme.forma 1 *italica*
soy _italica_ de la 2 forma
formato **bold** o **strong**
Tambien __bold__ o __formato__
formato~~tachado~~

#listas
1. esto
2. eso
3. aquello
- item de lista tambien
- otra

# links
- soporta links html pero tambien: 
- [Esto es link en Markdon](http://www.google.com)

# imagenes
![Logo Github](https://github.com/svg)

# code snippts
## puedo usar hightlights para trabajar aqui:
### pudo ver algunos en siguiendo el link [link](https://highlightjs.org/static/demo/)
### DEbe estar envuelto entre comilla invertida como altGr + } en teclado español(mexico)
en este ejemplo usamos Json por ser mas corta la sintaxis
_________________________
elcodigo en json comienaza:

 ```Json
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
 ```
 - Codigo ahora en JavaScript

 ````Javascript
 function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
 ````
 ####ideal para colocar codigos en el readme

 # Tablas
 |columna| apellido| cabecera|
 |-------|---------|----|
 |maxi|burgo|1223|
 tomas|feerr| 3421


 # Citas
 esto es un texto referente a una cita que ira debajo.
 > Esto es una cita.

 Esto es otro texto no se relaciona con texto anterior.
 > otra cita

 # Lieneas divisoras.
 ## este texto estara dividido por una line -- importante sean solo 3 a usar 3* o 3--, etc
 ---
 este es otro texto dividido **** 

 ***

dividido por guion bajo
___

# Saltos de lineas

Esto es mi primer parrafo.

Esto es nuestro segundo parrafo luego del enter

tercer parrafo luego de un Enter tambien.
