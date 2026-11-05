# HITO 0: Identificación de Objetos Predefinidos 


## 1. El objeto window se considera el objeto global del entorno del navegador (BOM). Explica la diferencia entre este y un objeto nativo global del lenguaje JavaScript como Math o JSON. ¿Por qué no hace falta escribir window.Math?

El objeto window pertenece al Browser Object Model (BOM). Representa la ventana del navegador. Su existencia depende del entorno web.

En cambio, objetos como Math o JSON son objetos nativos de JavaScript. Forman parte del propio lenguaje y pueden ser usado también fuera del navegador (por ejemplo en Node.js).

No es necesario escribir window.Math porque los objetos globales de JavaScript están disponibles directamente en el ámbito global. Aunque internamente son accesibles desde window, JavaScript permite utilizarlos sin indicar dicho objeto.


## 2. Identifica a qué categoría (BOM u objeto nativo de JS) pertenecen las siguientes instrucciones que utilizaremos en la práctica:

| Instrucción | Categoría |
|------------|-----------|
| window.open() | BOM |
| parseFloat() | Objeto nativo de JavaScript |
| Math.floor() | Objeto nativo de JavaScript |
| navigator.userAgent | BOM |