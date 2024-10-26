# Proyecto API de Spotify 🎶

Este proyecto permite realizar consultas a la API de Spotify mediante un sistema automatizado para gestionar el token de acceso, garantizando la autenticación continua. Incluye una función principal para obtener el token y utilidades adicionales para interactuar eficazmente con los datos de Spotify.

## Descripción

El proyecto está diseñado para:

- **Gestionar la autenticación**: Solicita y renueva automáticamente el token de acceso para la API de Spotify, asegurando que las consultas no se vean interrumpidas debido a la expiración del token.
- **Facilitar la conexión con la API de Spotify**: Permite realizar llamadas a la API y recuperar información detallada sobre artistas, álbumes, playlists, y más.

## Funcionalidades Principales

### 1. `get_token()`
Función principal para obtener el token de acceso. La función revisa la validez del token existente y, si es necesario, solicita un nuevo token a la API de Spotify, evitando la necesidad de una solicitud continua.

- **Ventajas**: Permite un acceso continuo y sin interrupciones, minimizando el riesgo de expiración del token durante las solicitudes a la API.
- **Duración del token**: Cada token es válido por una hora (3600 segundos), después de lo cual es necesario renovarlo.

### 2. Interacción con la API
El proyecto también incluye métodos para interactuar con diversos endpoints de la API de Spotify, facilitando consultas y extracciones de datos, como:

- **Búsqueda de Artistas, Canciones y Álbumes**.
- **Recuperación de Datos de Playlists**.
- **Obtención de Información de Usuarios**.

### 3. Configuración de Salida en Consola
El proyecto ofrece un formato de salida en colores para la consola, mejorando la claridad en la interpretación de los resultados y diferenciando los tipos de respuestas.






