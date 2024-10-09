# Ejercicio sobre XML

## 1. Características propias del lenguaje XML:
- **Estructura basada en etiquetas**: Utiliza una jerarquía donde los datos están contenidos entre etiquetas.
- **Extensible**: Se pueden crear etiquetas personalizadas.
- **Independencia de plataforma**: Funciona en cualquier sistema operativo.
- **Atributos**: Los elementos pueden tener atributos.
- **Legibilidad**: Tanto humanos como máquinas pueden leer XML.

## 2. Estructura de un documento XML y sus reglas sintácticas:
Un documento XML debe seguir estas reglas:
- **Prolog**: `<?xml version="1.0" encoding="UTF-8"?>`.
- **Elemento raíz**: Cada documento debe tener un único nodo raíz.
- **Elementos**: Todos los elementos deben tener etiquetas de apertura y cierre.
- **Atributos**: Los atributos deben estar entre comillas.
- **Anidación**: Las etiquetas deben estar correctamente anidadas.

## 3. Nodo raíz en XML:
El **nodo raíz** es el elemento principal que contiene a todos los demás elementos del documento. Es obligatorio tener un solo nodo raíz para que el documento sea válido.

## 4. Elemento vacío:
Un **elemento vacío** es aquel que no contiene datos entre sus etiquetas. Se puede representar de dos formas:
```xml
<elemento></elemento>
<elemento />
```
## 5. Importancia de un documento XML bien formado:

Un **documento bien formado** es aquel que sigue todas las reglas sintácticas de XML. Esto garantiza la interoperabilidad y que cualquier sistema o aplicación pueda procesarlo correctamente sin errores.

## 6. Espacios de nombres en XML:

Un **espacio de nombres** evita conflictos cuando se usan las mismas etiquetas en diferentes contextos, definiendo un identificador único. Ejemplo de uso:

### ventajas
- Evita colisiones de nombres.
- Claridad en la estructura del documento​(

## 7. Entidades en XML:

Las **entidades** permiten representar caracteres especiales o reservados. Ejemplo de un XML con entidades:
``` xml
<?xml version="1.0" encoding="UTF-8"?>
<productos>
   <nombre precio="12.50&#8364;">Gorro</nombre>
   <nombre precio="15.99&#x20AC;">Guantes</nombre>
</productos>
```

## 8. Comentarios en XML:

Los **comentarios** en XML permiten añadir notas sin que afecten el procesamiento del documento. Se encierran entre ``` <!-- ``` ```-->``` . Ejemplo:


``` xml
<?xml version="1.0" encoding="UTF-8"?>
<!-- Este es un comentario explicativo sobre el código -->
<productos>
   <nombre precio="10.50">Gorro</nombre>
</productos>
```








