# vue2-bcourse-platzi-challenge-01

A Pen created on CodePen.io. Original URL: [https://codepen.io/jhnemogap/pen/mdqevMO](https://codepen.io/jhnemogap/pen/mdqevMO).

Se prueba de la forma más básica. Agregando el script al HTML de un CDN.

## Consideraciones

La aplicación debe cumplir los siguientes lineamientos:

- Un propiedad courses que sea un _array_ y permita almacenar la lista de cursos.
- Tener una propiedad `title` y otra `time` que se usean para agregar un nuevo curso a la lista, estas propiedades deben estar enlazados a los inputs usando `v-model`.
- Un boton con un metodo `addCourse` (enlazado con `v-on`) que permita agregar un nuevo courso usando los valores de `title` y `time`.
- Una propiedad computada `totalTime` que recorra toda la lista de cursos y retorne la suma del tiempo invertido en educacion.
- Mostrar la lista de cursos tomados, con el titulo de los mismos y las horas de cada uno usando `v-for`.
- Mostrar el total de horas con `totalTime`, en caso que no existan cursos se debe mostrar un mensaje indicandolo.
