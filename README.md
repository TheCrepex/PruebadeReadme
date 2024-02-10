# Funciones JavaScript

## 1. Alertas y Diálogos
   - `alert(message)`: Muestra un cuadro de alerta con el mensaje especificado.
   - `prompt(message, default)`: Muestra un cuadro de diálogo para que el usuario ingrese información con un mensaje y un valor predeterminado opcional.
   - `confirm(message)`: Muestra un cuadro de confirmación con botones "Aceptar" y "Cancelar" y devuelve un booleano.

## 2. Manipulación de Cadenas de Texto
   - `charAt(index)`: Devuelve el carácter en la posición especificada de una cadena.
   - `concat(string1, string2, ...)`: Combina dos o más cadenas de texto.
   - `indexOf(searchValue, startIndex)`: Devuelve la posición de la primera ocurrencia de un valor especificado en una cadena.

## 3. Manipulación de Arrays
   - `push(element1, element2, ...)`: Agrega uno o más elementos al final de un array.
   - `pop()`: Elimina el último elemento de un array.
   - `join(separator)`: Combina todos los elementos de un array en una cadena usando un separador.
   - `slice(start, end)`: Devuelve una parte de un array.
   - `splice(start, deleteCount, item1, item2, ...)`: Cambia el contenido de un array eliminando, reemplazando o agregando elementos.
   - `indexOf(searchElement)`, `lastIndexOf(searchElement)`: Encuentra la primera/última posición de un elemento en un array.

## 4. Fecha y Tiempo
   - `Date()`: Crea un objeto de fecha.
      - `getMonth()`, `getDate()`, `getFullYear()`: Métodos para obtener componentes específicos de una fecha.

## 5. Matemáticas
   - `Math.random()`: Devuelve un número pseudoaleatorio entre 0 y 1.
   - `Math.round(number)`: Redondea un número al entero más cercano.

## 6. Control de Flujo
   - `if`, `else if`, `else`: Estructuras condicionales.
   - `switch`: Estructura de control de flujo basada en casos.

## 7. Bucles
   - `for(initialization; condition; iteration)`, `while(condition)`, `do-while(condition)`: Estructuras de bucle para la iteración.

## 8. Conversión de Tipo de Datos
   - `parseInt(string, radix)`: Convierte una cadena a un número entero.
   - `parseFloat(string)`: Convierte una cadena a un número de punto flotante.
   - `String(value)`: Convierte un valor a una cadena de texto.

## 9. JSON
   - `JSON.stringify(obj)`, `JSON.parse(jsonString)`: Convierte objetos JavaScript a y desde formato JSON.

## 10. Funciones de Array Avanzadas
   - `map(callback)`, `filter(callback)`, `reduce(callback, initialValue)`: Métodos para manipulación avanzada de arrays.

## 11. Funciones
   - `function name(params)`: Define una función.
   - `setTimeout(callback, delay)`: Ejecuta una función después de esperar un número especificado de milisegundos.
   - `setInterval(callback, interval)`: Ejecuta una función a intervalos regulares.

## 12. Expresiones Regulares
   - `test(regexp)`, `exec(regexp)`: Métodos para trabajar con expresiones regulares.

## 13. Manejo de Errores
   - `try { } catch { } finally { }`: Estructuras para manejar excepciones.

## 14. Manipulación Avanzada de Cadenas de Texto
   - `trim()`: Elimina los espacios en blanco al principio y al final de una cadena.
   - `toUpperCase()`: Convierte una cadena a mayúsculas.
   - `toLowerCase()`: Convierte una cadena a minúsculas.

## 15. Operaciones Numéricas
   - `isNaN(value)`: Determina si un valor no es un número.
   - `isFinite(value)`: Determina si un valor es un número finito.
   - `toFixed(digits)`: Formatea un número usando notación de punto fijo.

## 16. Manipulación de Objetos y Prototipos
   - `Object.create(proto, propertiesObject)`, `Object.assign(target, ...sources)`: Métodos para manipulación avanzada de objetos.

## 17. Fecha y Tiempo Adicional
   - `Date.now()`: Devuelve el número de milisegundos transcurridos desde el 1 de enero de 1970 00:00:00 UTC.
   - `Date.UTC(year, month, day, hours, minutes, seconds, milliseconds)`: Devuelve el tiempo en milisegundos entre una fecha y la medianoche del 1 de enero de 1970.

## 18. Manipulación Avanzada de Funciones
   - `bind(thisArg)`, `call(thisArg, arg1, arg2, ...)`, `apply(thisArg, [argsArray])`: Métodos para manipulación avanzada de funciones.

## 19. Promesas
   - `Promise(executor)`, `Promise.all(iterable)`: Constructor y método para trabajar con promesas.

## 20. Manipulación de Nodos HTML
   - `createElement(tagName)`: Crea un nuevo elemento HTML.
   - `appendChild(newNode)`, `removeChild(node)`: Métodos para manipulación de nodos HTML.

## 21. Manipulación Adicional de Caracteres y Cadenas de Texto
   - `charAt(index)`, `charCodeAt(index)`: Métodos adicionales para manipulación de caracteres y cadenas de texto.

## 22. Manipulación Adicional de Objetos y Prototipos
   - `hasOwnProperty(prop)`: Devuelve un booleano indicando si el objeto tiene la propiedad especificada como propiedad propia.
   - `isPrototypeOf(obj)`, `Object.freeze(obj)`: Métodos adicionales para manipulación de objetos y prototipos.

## 23. Manipulación Adicional de Expresiones Regulares
   - `search(regexp)`, `match(regexp)`: Métodos adicionales para manipulación de expresiones regulares.

## 24. Argumentos de Función y Funciones Adicionales
   - `arguments`: Objeto similar a un array que contiene los valores de los argumentos pasados a una función.
   - `Function(args, body)`: Constructor para crear una nueva función.

## 25. Manejo de Eventos
   - `event.preventDefault()`: Cancela el comportamiento predeterminado del evento si este es cancelable, como enviar un formulario.
   - `event.stopPropagation()`: Detiene la propagación del evento a través de la jerarquía de eventos.

## 26. Manipulación de Cookies
   - `document.cookie`: Proporciona una interfaz para trabajar con cookies.

## 27. Ventanas y Navegadores
   - `window.open(url, name, specs, replace)`: Abre una nueva ventana del navegador.
   - `window.location`: Proporciona información sobre la ubicación del documento actual y permite redirigir a otra página.

## 28. Manipulación de Clases y Valores Booleanos
   - `classList`: Proporciona métodos para agregar, eliminar y cambiar clases en un elemento HTML.
   - `Boolean(value)`: Convierte un valor a su equivalente booleano.

## 29. Propiedades del Documento HTML
   - `document.title`: Obtiene o establece el título del documento.

## 30. Comunicación con el Servidor
   - `XMLHttpRequest`: Objeto para realizar peticiones HTTP asíncronas.

## 31. Navegación del Historial
   - `history.back()`, `history.forward()`, `history.go()`: Métodos para navegar por el historial del navegador.

## 32. Validación de Formularios
   - `form.checkValidity()`, `input.validity`: Métodos y propiedades para validar formularios e inputs.

## 33. Arrastrar y Soltar
   - Eventos como `dragstart`, `dragenter`, `dragleave`, `dragover`, `drop` para implementar funcionalidad de arrastrar y soltar.

## 34. Selección de Elementos HTML
   - `document.querySelector(selector)`, `document.querySelectorAll(selector)`: Métodos para seleccionar elementos HTML.

## 35. Propiedades de Estilo CSS
   - `element.style`: Propiedad para acceder y modificar estilos CSS en un elemento HTML.
