# BackstopJS Practice

Este proyecto fue construido para servir de guía utilizando la herramienta backstopJS la cual sirve para realizar pruebas visuales y detectar si se tuvieron cambios a nivel de los objetos del front-end, tiene cuatro escenarios los cuales realiza la validación de: 
- Un solo objeto de la página
- Captura completa de página quitando un objeto de la misma
- Click en un link previo a la captura de pantalla
- Login ingresando usuario - password y haciendo click en el botón de login para posteriormente tomar las imágenes

## backstop_data > bitmaps_reference
Dentro de este folder se encuentran las imagenes contra las que contrastará la ejecución de los casos de prueba

<img width="344" alt="image" src="https://github.com/camhost01/DEMO-BLAZE/assets/39304271/0628cc15-de69-446d-8514-ed92256cc5a8">

## backstop.json
Se encuentran los escenarios de prueba que se ejecutan
<img width="1238" alt="image" src="https://github.com/camhost01/DEMO-BLAZE/assets/39304271/3855a3b2-e341-428e-b4c4-0db85e0eaeb3">


## package.json
Se encuentran los scripts para ejecutar por medio de npm run
<img width="1167" alt="image" src="https://github.com/camhost01/DEMO-BLAZE/assets/39304271/b90a3cb6-7214-49e3-9e7b-267dad8b9174">

### clean
Hace referencia a borrar las carpetas ya sea de test o de reference

### scenarios 
Ejecuta los cuatro escenarios de prueba

### approve_scenarios
Aprueba todas las imágenes de referencia que se tengan

### Si se quiere ejecutar únicamente un escenario de prueba y no todos
Para ejecutar solo un escenario de prueba y no todos basta con añadir


