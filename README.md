# Dev# 📱 Twitch Mobile Studio (Android)

Una aplicación de alto rendimiento para el seguimiento y gestión de streams de Twitch, diseñada para usuarios avanzados y creadores que realizan **multistreaming**.

---

## 🚀 Características Principales

- **📺 Stream Player**: Reproductor de video integrado mediante WebView optimizado con aceleración de hardware.
- **💬 Smart Chat**: Cliente IRC vía WebSockets con soporte para colores de usuario, emotes y tags de Twitch.
- **🗣️ Voice Engine (TTS)**: Lectura de chat inteligente con limpieza de URLs/Spam y controles de velocidad/tono.
- **🔐 Secure Auth**: Sistema de autenticación OAuth2 con almacenamiento cifrado (AES-256) y autorenovación de tokens.
- **📊 Network Monitor**: Monitoreo de ancho de banda en tiempo real para asegurar estabilidad durante multistreaming.
- **🏠 Room Database**: Persistencia local para favoritos y categorías preferidas.
- **🔔 Firebase Alerts**: Notificaciones push para cuando tus streamers favoritos inician directo.

---

## 🛠️ Stack Tecnológico

- **Lenguaje:** Kotlin + Coroutines (Flujos asíncronos).
- **Red:** Retrofit 2 + OkHttp 4 (Retry Interceptor Exponencial).
- **Base de Datos:** Room Persistence Library.
- **UI:** Material Design 3 + Animaciones de escala y transición.
- **Arquitectura:** MVVM (Model-View-ViewModel) + Clean Architecture.

---

## 📂 Estructura del Proyecto

- `data/`: Repositorios, APIs, Autenticación y Base de Datos (Room).
- `ui/`: Fragments, Activities y Adapters (RecyclerView con DiffUtil).
- `services/`: Notificaciones Firebase y Motor TTS.
- `utils/`: Interceptores de red, limpieza de texto y monitores de conectividad.

---

## ⚙️ Configuración del Entorno

1. Clona el repositorio.
2. Crea un archivo `secrets.properties` y añade tus credenciales de [Twitch Developers](https://dev.twitch.tv/):
   ```properties
   TWITCH_CLIENT_ID="tu_client_id"
   TWITCH_CLIENT_SECRET="tu_client_secret"
shackrepo
꧁༒𝓐𝓷𝓰𝓮𝓵𝓪𝓽𝓽𝓸 𝓓𝓮𝓿𝓼𝓱𝓪𝓬𝓴𝓮𝓻༒꧂
