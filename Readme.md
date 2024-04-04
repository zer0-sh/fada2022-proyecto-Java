# Proyecto final FADA
## 2022-2


En este proyecto se debe construir una librería que provea los métodos para trabajar con matrices dispersas.

## Features

- Cargar un archivo con una matriz
- Generar la representación coordenada
- Generar la representación comprimida por filas CSR
- Generar la representación basada en columnas CSC

Se puede instalar intellij para cargar el proyecto y configurarlo correctamente, de lo contrario vía consola ejecutar

### Implementación de Matrices Dispersas en Java

Este proyecto proporciona una implementación en Java para trabajar con matrices dispersas y sus diferentes representaciones: formato coordenado, formato comprimido por fila y formato comprimido por columna. El objetivo es ofrecer operaciones eficientes para crear, manipular y realizar cálculos con matrices dispersas.
Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

    src/: Contiene el código fuente Java.
        SparseMatrixCoordinateFormat.java: Implementación de la representación en formato coordenado.
        SparseMatrixCSC.java: Implementación de la representación en formato comprimido por columna.
        SparseMatrixCSR.java: Implementación de la representación en formato comprimido por fila.

Operaciones Soportadas

Para cada una de las implementaciones, se han desarrollado las siguientes operaciones:
Representación Coordenada

    Crear Representación: Pasa de una matriz a su representación.
    Obtener Elemento: Dada una posición (i,j), imprime el valor en pantalla.
    Obtener Fila: Dada una fila deseada, imprime la fila en pantalla.
    Obtener Columna: Dada una columna deseada, imprime la columna en pantalla.
    Modificar Posición: Dada una posición (i,j) y un elemento, modifica la representación para ingresar este elemento.
    Elevar al Cuadrado: Retorna la representación de la matriz elevada al cuadrado.
    Matriz Transpuesta: Retorna la representación de la matriz traspuesta.

Representación Comprimida por Columnas y Filas

    Crear Representación: Pasa de una matriz a su representación.
    Obtener Elemento: Dada una posición (i,j), imprime el valor en pantalla.
    Obtener Fila: Dada una fila deseada, imprime la fila en pantalla.
    Obtener Columna: Dada una columna deseada, imprime la columna en pantalla.
    Modificar Posición: Dada una posición (i,j) y un elemento, modifica la representación para ingresar este elemento.
    Elevar al Cuadrado: Retorna la representación de la matriz elevada al cuadrado.
    Matriz Transpuesta: Retorna la representación de la matriz traspuesta.

```sh
gradlew build
```

## Desarrollo
Resuelve este reto, para esto debe pasar las pruebas y el procedimiento de construcción.

## License

MIT

**Free Software, Rules!**
