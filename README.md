# 2024---TPconsola---G08

1. Describir y/o documentar la funcion Console.log() 
La funcion console.log() es una herramienta de java script que envia mensajes de texto, valores de variables y otros datos a la consola. 
Es útil para depuración, ver el flujo de ejecución y ver el estado de las variables en el código.

2. ¿Qué parametros necesita? 
Para que el console log imprimga algo en la consola se necesita algun tipo de dato. Estos pueden ser cadensa de texto(string), numeros, booleanos, objetos, arrays, funciones, expresiones o 
valores tipo null y undefined. 

¿Que otros parametros puede usar?
Además de todos los parametros básicos como mostrar texto o variantes del código, dentro del console.log también se pueden usar parametros combiados 
usando texto, variantes y objetos en el mismo console.log. Se pueden usar parametros como 'Date.now', que devuelve el dia actual. Por último también 
se pueden hacer cuentas dentro del console, y cuando se ejecuta aparece el resultado. 

3. ejemplos de parametros
javascript
- imprimir un msj

```
console.log("hola, mundo");
```

- imprimir valores variables

```
let num = 25;
console.log("el numero es:", num);
```

- imprimir un objeto

```
let persona = { nombre: "irene", edad: 50 };
console.log("nombre y edad del usuario:", persona);
```

- imprimir un array

```
let numeros = [1, 2, 3, 4, 5];
console.log("listado de numeros:", numeros);
```

- imprimir una expresión

```
console.log("el resultado de 5 + 5 es:", 5 + 5);
```

4. Desarrollar: ¿Que contenido debemos publicar en la consola? 
- Front-end: La consola del navegador se usa principalmente para depuracion en la interfaz del usuario y en la interaccion del usuario con la aplicacion.
Cualquier persona puede acceder a esta por lo que cosas como contraseñas o nombres de usuario (o cualquier dato personal) no deberia verse.
- Back-end:  La consola en el servidor se usa para rastrear el estado del servidor, las solicitudes y respuestas, y manejar la logica del lado del servidor.
Esta consola solamente la puede ver el dueño del programa por lo que podrian aparecer datos que el publico no puede ver.

5. Investigar que otros metodos tiene el objeto console. Elegir 3 metodos diferentes a log y desarrollarlos

console.info : se utiliza para imprimir mensajes informativos en la consola. 
En muchos navegadores la salida es similar a la de console.log(), pero está diseñado para proporcionar una indicación de que el mensaje tiene un propósito informativo. 
En algunos entornos, los mensajes generados por console.info() pueden aparecer con un estilo diferente o en una categoría separada en la consola.
- Ej: console.info("El proceso se completó con éxito");

console.error : se utiliza para imprimir mensajes de error en la consola. 
Los mensajes suelen aparecer con un estilo que indica que se trata de un error, con un icono o un color específico para destacar la gravedad del mensaje. 
Esto facilita la identificación y el diagnóstico de problemas durante el desarrollo.
- Ej: 

```
console.error("Error de conexión con el servidor: ", error);
```

console.warn : se utiliza para imprimir advertencias en la consola. 
Las advertencias son mensajes que indican que algo podría ser un problema, pero no es necesariamente un error. 
En muchos navegadores, los mensajes de advertencia se muestran con un estilo distintivo (como un icono de advertencia o un color diferente) para diferenciar los avisos de otros tipos de mensajes.
- Ej: 

```
console.warn("La variable 'x' no está definida, podría causar problemas en el futuro");
```
