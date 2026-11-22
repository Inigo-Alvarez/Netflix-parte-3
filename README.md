

## Descripción de la práctica
En esta actividad se desarrollará una aplicación web cliente usando las principales tecnologías web (HTML, CSS y JavaScript), siguiendo el patrón de diseño MVC. La aplicación funcionará como una base de datos de películas, donde se guardarán datos como el título, el director y la URL de la carátula de cada película. El usuario podrá ver la información de las películas, añadir películas nuevas, editar las existentes, eliminarlas o restablecer la base de datos. Todas estas acciones se realizarán mediante botones en la interfaz de la aplicación. El objetivo principal de esta actividad es que el alumnado se familiarice con el desarrollo de una aplicación web completa, abarcando desde el diseño de la interfaz hasta la gestión de los datos almacenados en el navegador.

El desarrollo de esta aplicación permitirá al alumnado aprender a trabajar con el patrón MVC (Modelo-Vista-Controlador), muy utilizado en el desarrollo de software moderno. Este patrón facilita la separación entre la lógica de la aplicación, la presentación de los datos y la interacción con el usuario, contribuyendo a un código más limpio y mantenible. Además, se utilizará localStorage para guardar los datos en el navegador, lo que ayudará al alumnado a entender cómo funcionan las opciones de persistencia de datos en el lado del cliente.
Actualmente, el código proporcionado incluye la funcionalidad para listar las películas existentes y editar la información de una película. Como parte de la práctica, el alumnado deberá implementar el resto de funcionalidades: crear nuevas películas, mostrarlas, eliminarlas y restablecer la base de datos. Implementar estas funcionalidades adicionales permitirá comprender mejor cómo interactúan las distintas partes de una aplicación MVC y cómo se gestionan los eventos y el flujo de datos dentro de la aplicación.

## Tareas
El objetivo de esta práctica es completar las funcionalidades que faltan:
Show: Mostrar la información de una película.
New: Mostrar el formulario para añadir una nueva película.
Create: Añadir una nueva película al modelo.
Delete: Eliminar una película del modelo (con confirmación del usuario).
Reset: Restaurar el modelo a su estado inicial.

Para implementar estas funcionalidades, se recomienda seguir estos pasos:
Añadir el botón correspondiente en la vista indicada, incluyendo la clase especificada y los atributos necesarios (por ejemplo, data-my-id).
Configurar el router para capturar el evento y llamar al controlador adecuado, pasando los parámetros necesarios.
Modificar el controlador para realizar las operaciones necesarias sobre el modelo y actualizar la vista.
Modificar la vista para representar correctamente la nueva funcionalidad.

Estos pasos ayudarán a estructurar la implementación y a asegurar que cada funcionalidad se desarrolle de forma correcta y eficiente, ofreciendo una experiencia completa en el desarrollo de una aplicación web funcional.