---
title: Variables
localeTitle: Variables
---
## Variables

Una variable asocia un nombre con un valor de un tipo particular. En Swift hay dos formas principales de crear variables. `let` y `var`. Para declarar constantes se usa la palabra clave `let`. Para declarar variables mutables se usa la palabra clave `var`.

El beneficio de tener dos formas de almacenar variables en Swift es evitar errores de cambio de variables que deberían ser constantes.

 ```Swift
  let diasSemana = 7
  var cantidadDinero = 100

  cantidadDinero = 150
  // cantidadDinero es ahora 150

  diasSemana = 10
  // ¡Devuelve error!

 ```

En este caso la variable `diasSemana` debe ser una constante, porque sólo hay siete días en una semana, mientras que la variable `cantidadDinero` debe ser declarada con 'var' porque la cantidad de dinero en una cuenta puede cambiar.

Los nombres de variables y constantes pueden contener casi cualquier caracter, incluidos los caracteres Unicode:

```Swift
  let π = 3.14159 
  let 你好 = "你好世界" 
  let 🐶🐮 = "perrovaca" 
```

Para probar si sus variables tienen el valor correcto, use `print()`.

```Swift
  let dinero = 50 
 
  print(dinero) 
  // Esto imprime 50 
```

#### Más información:

*   [El lenguaje de programación Swift](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html#ID310)
