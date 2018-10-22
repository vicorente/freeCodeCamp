---
title: Type Inference
localeTitle: Inferencia de tipos
---
## Inferencia de tipos

Swift usa la inferencia de tipos, es decir, es capaz de elegir el tipo de dato correcto según el contexto. De este modo, si escribe algo como el código del siguiente ejemplo es bastante obvio cuál es el tipo de dato.

#### Ejemplo:

```swift
    let iPhone: String = “iPhone” 
    let yearIntroduced: Int = 2007 
    let isAwesome: Bool = true 
```

Así que podemos limpiar el código para que se vea como el ejemplo a continuación, y Swift puede inferir el tipo de uso.

#### Ejemplo:

```swift
    let iPhone = “iPhone”       // Inferido como String
    let yearIntroduced = 2007   // Inferido como Int 
    let isAwesome = true        // Inferido como Bool
```

#### Más información:

*   [El lenguaje de programación Swift](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html#ID322)
