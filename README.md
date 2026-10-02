# freeCodeCamp(🔥︎): _Front-End Development Libraries Certification_

Portafolio de talleres, laboratorios y proyectos requeridos para la certificación en bibliotecas de desarrollo front-end de [freeCodeCamp](https://www.freecodecamp.org/learn/front-end-development-libraries-v9/).

Este curso enseña las bibliotecas que los desarrolladores usan para construir páginas web: React, JSX, TypeScript y más.

Para obtener la certificación en bibliotecas de desarrollo front-end se requiere:

* **Completar las lecciones teóricas, talleres y laboratorios de preparación para los proyectos**
* **Completar los cinco proyectos requeridos para calificar para el examen de certificación**
* **Aprobar el examen de certificación en bibliotecas de desarrollo front-end basado en los conocimientos adquiridos de los dos puntos anteriores**

A continuación se desglosará como va a estar compuesto este repositorio.

## 1. Descripción de los talleres y laboratorios

En el directorio `freeCodeCamp/talleres-y-laboratorios` se irán recopilando los diversos retos de desarrollo de código que se nos plantean mientras se estudia la parte teórica del curso con contenido lectivo o Quiz, para consolidar la lectura y los conocimientos adquiridos. 

Son muchos a lo largo de todo el curso, por lo que la descripción, objetivos y pruebas de cada uno se detallarán en el propio directorio del taller o laboratorio al acceder a ellos.

## 2. Descripción de los proyectos finales

En el directorio `freeCodeCamp/proyectos-finales` se irán recopilando los proyectos finales requeridos para la evaluación y posterior acceso al examen de evaluación final del curso.

A continuación, se indicarán las historias de usuario y pruebas de cada uno. También se podrá encontrar en el directorio de cada propio proyecto.

### - Primer proyecto: Construir un convertidor de divisas

Objetivo: Cumplir con las historias de usuario a continuación y pasar todas las pruebas para completar el laboratorio.

Historias de usuario:

* Tu componente CurrencyConverter debería renderizar un elemento input para aceptar el monto a convertir.
* Tu elemento input debería aceptar números.
* Tu componente CurrencyConverter debería renderizar dos elementos select para elegir la moneda a convertir de y a.
* Tu elemento select debe incluir opciones para al menos USD, EUR, GBP y JPY. Puedes usar cualquier tasa de cambio, siempre que no haya una correspondencia uno a uno entre las monedas
* Tu componente CurrencyConverter debería memorizar el cálculo de los montos convertidos para la moneda de manera que un cambio en la opción a select no recalculará los montos convertidos.
* Tu componente CurrencyConverter debería renderizar un elemento mostrando el monto convertido en el formato XX.XX CCC, donde XX.XX es el monto convertido y CCC es el código de la moneda.
* El monto convertido debería redondearse a dos decimales.

Pruebas:

* Deberías exportar un componente CurrencyConverter.
* Deberías tener un elemento input[type="number"] para aceptar el monto a convertir.
* Deberías tener dos elementos select.
* Los elementos select deberían tener opciones para al menos USD, EUR, GBP y JPY.
* Cambiar el valor del primer elemento select debería causar que los montos convertidos sean recalculados.
* Cambiar el valor del segundo elemento select no debería causar recalculación de los montos convertidos.
* Cambiar el valor del primer elemento select debería mostrar la nueva cantidad convertida.
* Cambiar el valor del segundo elemento select debería mostrar la nueva cantidad convertida y la moneda.
* El monto convertido debería mostrarse en el formato XX.XX CCC, donde XX.XX es el monto convertido redondeado a dos decimales y CCC es el código de la moneda.
* El monto convertido debería ser diferente del monto de entrada

### - Segundo proyecto: -

(in progress)
