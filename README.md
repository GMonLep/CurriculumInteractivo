# CurriculumInteractivo
Clase 4 - Tarea 50% Primera Nota. Creación de un Currículum Interactivo en HTML.

1) ¿Qué etiquetas nuevas investigaste?
```html
<label>
<input>
<button popovertarget>

2) ¿Para qué sirven y cómo las aplicaste en tu currículum?
    
Label: el la etiqueta para un elemento en una interfaz de usuario. Te permite indicarle al usuario que tipo de dato le estas pidiendo al completar el formulario.

Input: esta etiqueta especifica un campo donde el usuario puede ingresar datos, asociandole un ID que se puede consultar más tarde haciéndo más fácil el manejo de los datos ingresados.

Button popovertarget: crea un botón que te permite mostrar/esconder un elemento en específico.

3) Ejemplo de código en HTML donde las utilizaste.
```html
<label for="nombre">Nombre:</label> ---> Para especificar el nombre del campo vacío en el cual el usuario debe ingresar información.
<input type="text" id="nombre" nombre="nombre" required><br><br> ---> Determinar que lo ingresado debe ser texto y que no puede ir vacío.
<button popovertarget="info">APRETAME</button> ---> Para "esconder" la información y solo mostrarla cuando el boton 'APRETAME' fuera apretado(en este caso era un gif)
