# Base de datos NoSQL - Navegación FMCS para aeronave CRJ-200

¡Bienvenido a la documentación de la base de datos NoSQL para la navegación FMCS de la aeronave CRJ-200! En este repositorio, encontrarás información sobre la estructura de la base de datos y ejemplos de datos en formato JSON.

## Descripción

Esta base de datos NoSQL ha sido diseñada para almacenar información relacionada con la navegación de la aeronave CRJ-200. Contiene varias tablas que capturan datos como vuelos, registros de navegación, rutas de vuelo, puntos de navegación, registros de turbulencia, seguimiento de vuelo, información de pistas, aterrizajes de emergencia, condiciones climáticas y fallos del sistema de navegación.

## Estructura de las tablas

Las tablas en esta base de datos NoSQL están diseñadas de la siguiente manera:

    1. Vuelo: Tabla que almacena información sobre los vuelos realizados en la aeronave CRJ-200.
    2. RegistroNavegacion: Tabla que registra los datos de navegación en diferentes momentos durante un vuelo.
    3. RutaVuelo: Tabla que mantiene la información de las rutas de vuelo asociadas a cada vuelo.
    4. PuntoNavegacion: Tabla que almacena los puntos de navegación utilizados en las rutas de vuelo.
    5. RegistroTurbulencias: Tabla que registra los datos de turbulencia durante un vuelo.
    6. PistaVuelo: Tabla que mantiene el seguimiento de la aeronave durante un vuelo.
    7. PistaAterrizaje: Tabla que contiene información sobre las pistas de aterrizaje.
    8. AterrizajeEmergencia: Tabla que registra los aterrizajes de emergencia realizados durante un vuelo.
    9. CondicionesMeteorologicas: Tabla que almacena información sobre las condiciones climáticas durante un vuelo.
    10. FalloSistemaNavegacion: Tabla que registra los fallos del sistema de navegación durante un vuelo.

## Ejemplos de datos

En la carpeta "ejemplosTablas" de este repositorio, encontrarás ejemplos de datos en formato JSON que representan los registros de las 10 tablas mencionadas anteriormente. Estos ejemplos te servirán como referencia para comprender la estructura y el contenido de los registros en la base de datos.

Nota: Los datos y ejemplos proporcionados en este repositorio son ficticios y se utilizan únicamente con fines de demostración.