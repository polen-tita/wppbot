# WPP Bot

  Bot personal de WhatsApp basado en comandos explícitos, automatización y funciones multimedia.

  > Proyecto en desarrollo. Todavía no es una release final.

  ![WPP Bot en WhatsApp](docs/images/wppbot-chat.png)

  ## ¿Qué es?

  WPP Bot permite interactuar con distintas herramientas directamente desde WhatsApp. El flujo principal es simple:

  ```text
  RECIBE → PROCESA → RESPONDE
  ```

  El bot responde únicamente a comandos y chats autorizados.

  ## Funciones principales

  - Consultas de IA con `/ia`.
  - Análisis de imágenes, audio, video y PDF.
  - Creación de stickers con `/s`.
  - Descarga de contenido público con `/tt`.
  - Búsqueda y envío de audio con `/play`.
  - Consulta del clima con `/clima`.
  - Búsqueda profunda de la web con `/ia web`.
  - Generación de imágenes con `/imagen`.
  - Analizar links para ver si son maliciosos o no.
  - Establecer reglas en los grupos.
  - Seleccionar que grupos y chats van a tener disponible estas funcionalidades.

  ## Ejemplos

  ```text
  /menu
  /ia Explicame qué es TCP
  /ia resumen del chat de hoy
  /clima Buenos Aires
  /s contener
  /play nombre de una canción
  ```

  ## Capturas

  ![Comandos en WhatsApp](docs/images/wppbot-chat.png)

  ![Procesamiento multimedia](docs/images/wppbot-media.png)


  ## Estado del proyecto

  WPP Bot se encuentra en construcción. La arquitectura principal está funcionando y se siguen incorporando mejoras, controles y nuevas funciones.

  Creá esta estructura dentro del repositorio:

  docs/
  └── images/
      ├── wppbot-chat.png
      ├── wppbot-terminal.png
      └── wppbot-media.png
