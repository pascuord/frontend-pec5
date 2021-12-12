**Ejercicio 1 – Preguntas teóricas sobre formularios
Angular (1.5 puntos)**

*a)¿Cuáles son las principales diferencias entre formularios dirigidos por template y formularios reactivos?*

Los formularios basados ​​en plantillas utilizan el “FormsModule”, mientras que los formularios reactivos se basan en “ReactiveFormsModule”.

Los formularios basados ​​en plantillas son de naturaleza asincrónica, mientras que los formularios reactivos son en su mayoría sincrónicos.

En un enfoque basado en plantillas, la mayor parte de la lógica se basa en la plantilla, mientras que en el enfoque basado en reactivos, la lógica reside principalmente en el componente .

*b)¿Qué son, para qué sirven y cómo se utilizan las directivas ngModel y ngModelChange?*

ngModel se trata de un enlace, entre algo que tienes en la definición del componente con un campo de formulario del template (vista) del componente.

ngModelChange es un evento llamado que se ejecuta cuando cambia el valor en la propiedad asociada a un ngModel, con el que podríamos conseguir un comportamiento para almacenar datos de los formularios cuando canvian.

*c) ¿Qué son, cuáles son y para qué sirven los estados en los formularios dirigidos por templates?*

Los estados dan a conocer si se ha interactuado o no con un elemento de un formulaio en un momento dado.

El control ha sido visitado  ----->  ng-touched - ng-untouched
El valor del control ha cambiado ->  ng-dirty --- ng-pristine
El valor del  control es válido -->  ng-valid --- ng-invalid

*d) ¿Qué ventajas aportan los FormGroup en la composición de formularios?*

Las ventajas que aportan sobre los FormControl es que el FormControl es un objeto qué se usa en los formularios para tener un control sobre su valor y su estado en el formulario. Y el FormGroup

FormGroup es un cojunto de FormControls, el estado de este objeto depende del estado de todos sus objetos, es decir, si uno de los FormControl es inválido, el grupo entero es inválido. 


