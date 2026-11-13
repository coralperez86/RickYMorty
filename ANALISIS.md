
Análisis - Taller Rick and Morty

Estudiante: Coral D. Pérez Manrique.

##1. Objetivo

Desarrollar una aplicación Android con Kotlin, Jetpack Compose y Retrofit para consumir y 
mostrar datos de la API de Rick and Morty.

##2. Implementación

• Red y Datos: Conexión a la API mediante Retrofit, deserialización de JSON y 
creación del modelo Personaje.
• Arquitectura: Uso de Repository para gestionar las peticiones y ViewModel para administrar 
los estados de la app.
• Interfaz (UI): Pantallas de lista y detalle de personajes conectadas mediante 
navegación en Compose.

##3. Manejo de Errores

Se implementaron los estados Loading, Success y Error. Al probar la app sin Internet, 
inicialmente sufría un cierre inesperado (crash). Esto se solucionó capturando las excepciones 
en el Repository para mostrar un error controlado en pantalla.

##4. Resultados

• Carga correcta del listado y el detalle de cada personaje.
• Mensaje de error visual al perder la conexión a Internet.
• Recuperación exitosa de los datos al presionar el botón Reintentar.

##5. Evidencias

Los respaldos visuales del funcionamiento se encuentran en la carpeta "EVIDENCIAS" del 
directorio principal.

##6. Conclusión

Se comprendió la importancia de manejar excepciones al consumir servicios web y de separar 
responsabilidades usando Repository y ViewModel para lograr una app estable.