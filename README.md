# Objetivos
Utilizando los aprendizajes del diseño de UI del trimestre anterior, hay cosas importantes sobre las que iterar y diseñar, quedando a nuestro cargo el diseño del recorrido. Queda sobre nosotros el diseño e implementación de los siguientes elementos:
- **_Controlador de Personaje:_** El usuario debe poseer un XR Rig suficientemente completo para interactuar con su entorno y moverse de manera satisfactoria.
- **_Interfaz de Usuario:_** El interfaz de usuario debe ser construido pensando en VR primero, y plataformas alternativas después. Por ende, este debe ser immersivo dentro de lo posible, y tener el mínimo movimiento necesario, a fin de evitar mareo, problemas de rendering y dificultades de uso.
- **_Plantilla de Interacción:_** Como consecuencia de diseñar el personaje jugable, recae también generar objetos y patrones comunes para diseñar los interactuables. Se logró esto en parte el trimestre anterior con la Sala de Fundadores, pero crear herramientas adicionales ayudaría.
# Definición de Hecho
Para este equipo se considerará como Hecho una meta o elemento siempre y cuando cumpla los siguientes requerimientos:
- Este funciona en su totalidad dentro del simulador de VR.
- No se encuentran fallas apreciables.
- Cumple con un nivel de calidad suficiente para que el usar el elemento se sienta satisfactorio.
- No hay mejoras sustanciales que se puedan hacer sobre el elemento en su fase del desarrollo.

Es posible (y recomendable) revisar un elemento de desarrollo que alcanzó la Definición de Hecho una vez cambie el contexto dentro del que existe (ejemplo: revisar el esquema de controles del personaje jugable durante la fase de diseño de interacciones). Todos los elementos de desarrollo, adicionalmente, deben estar sujetos a pruebas por otros miembros de la ayudantía (incluyendo, idealmente, a los profesores), a fin de lograr aceptación y constancia de trabajo en cada Sprint.
# Distribución del Trabajo
Secuencialmente, se propone el desarrollo de los elementos en el orden de: 
- Interfaz (menú de navegación),
- Personaje Jugable,
- Interfaz (directo sobre el personaje),
- Plantilla de Interacción,
- Interacciones Específicas.

Idealmente se lograría construir al menos tres (3) interacciones clave para utilizar durante el recorrido; sin embargo la infraestructura y funcionalidad es prioridad más que nada. Todos los miembros del equipo deben trabajar en el mismo item de la lista hasta que este cumpla la Definición de Hecho.

Se usará el tablón de GitHub Projects para manejar con mayor precisión los requerimientos puntuales de cada elemento de desarrollo.
# Configuración del Entorno de Desarrollo
Para este proyecto se utilizarán las siguientes dependencias de Unity:
- {}

Esta lista crecerá a medida que progrese el desarrollo propiamente. NO SE DEBE HACER COMMIT SOBRE LAS CARPETAS DE DEPENDENCIA. Unity debe regenerar sus carpetas de dependencias (TextMeshPro, XR Interactor, etc.) localmente, lo cuál se guardará en la configuración del proyecto de Unity. El repositorio solo contendrá los paquetes finalizados, los asserts utilizados y el codigo fuente de los elementos del proyecto.
