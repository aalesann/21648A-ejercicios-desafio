# Ejercicio N°1: Calculadora de Tarifas de Envío
## Descripción:

Imagina que estás desarrollando un software para una compañía de envíos. Dicha compañía tiene diferentes tarifas basadas en el destino y el peso del paquete. Tu tarea es crear una función que calcule el costo del envío.

## Requisitos:

1. Crea cuatro funciones flecha, cada una representando una zona geográfica diferente (Local, Nacional, Internacional, Especial). Cada función debe aceptar un peso en kilogramos y retornar el costo de envío para esa zona.

2. Desarrolla una función principal llamada calcularEnvio. Esta función debe aceptar dos argumentos: el peso del paquete (número) y la zona de envío (string).

3. Utiliza una sentencia switch dentro de calcularEnvio para determinar qué función de tarifa de envío se debe invocar basándose en la zona proporcionada. Invoca esta función con el peso dado y muestra el resultado con console.log.

Ejemplo de Invocación:
```js
calcularEnvio(5, "Nacional");
```

Esperado en Consola:
```js
25 (o cualquier otro número basado en tu lógica de tarifas)
```

Consideraciones:
> Asegúrate de manejar casos en los que se ingresen zonas que no tienes implementado. En tales casos, podrías retornar un mensaje que diga __*"Zona de envío no soportada"*__.


# Ejercicio N°2: Sistema de Evaluación de Empleados
## Descripción:
Supón que estás construyendo un software de recursos humanos que evalúa el rendimiento de los empleados en una empresa. La empresa utiliza varios criterios para evaluar a un empleado, incluyendo productividad, puntualidad y habilidades de comunicación.

Requisitos:
Funciones Base: Crea tres funciones flecha, cada una evaluando un criterio diferente:

**evaluarProductividad(puntos: number): number**
**evaluarPuntualidad(puntos: number): number**
**evaluarComunicacion(puntos: number): number**

Cada función debe tomar un número de puntos (de 0 a 100) y retornar una bonificación salarial correspondiente a esos puntos.

Funciones de Recargo y Descuento: Desarrolla una función adicional que calcule un bono o un recargo basado en el departamento del empleado (por ejemplo, el departamento de ventas podría tener un bono adicional).

Función Principal: Desarrolla una función principal llamada evaluarEmpleado. Esta función debe aceptar cinco argumentos:

- Puntos de productividad (número)

- Puntos de puntualidad (número)

- Puntos de comunicación (número)

- Salario base (número)

- Departamento (string)

Utiliza estas funciones para calcular la bonificación total y, finalmente, el salario final del empleado.

Muestra el salario final con console.log.

Ejemplo de Invocación:
```js
evaluarEmpleado(80, 90, 70, 5000, "Ventas");
```

Esperado en Consola:
```js
5600 (o cualquier otro número basado en tu lógica de evaluación y bonificaciones)
```

Consideraciones:
> Puedes usar operadores ternarios o sentencias if adicionales para aplicar los recargos y descuentos.
> Asegúrate de manejar casos en los que se ingresen departamentos que no has implementado. En tales casos, podrías retornar un mensaje que diga **_"Departamento no reconocido"_**.