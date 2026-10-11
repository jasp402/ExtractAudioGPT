<p align="center">
  <img src="assets/extractaudiogpt-icon.png" width="128" alt="ExtractAudioGPT">
</p>

<h1 align="center">ExtractAudioGPT</h1>

<p align="center"><strong>Descarga los audios de ChatGPT con un clic.</strong></p>

<p align="center">
  Convierte la función «Leer en voz alta» de ChatGPT en archivos que puedes guardar, escuchar y reutilizar cuando quieras.
</p>

<p align="center">
  <a href="https://github.com/jasp402/ExtractAudioGPT/releases"><strong>Descargar extensión</strong></a>
  ·
  <a href="https://github.com/jasp402/ExtractAudioGPT/issues/new/choose">Solicitar soporte</a>
  ·
  <a href="PRIVACY.md">Privacidad</a>
</p>

> **Estado:** versión de prueba. La distribución pública y la publicación en Chrome Web Store están en preparación; las funciones todavía requieren validación completa en Chrome.

## Tu audio, a tu manera

| Función | Qué puedes hacer |
| --- | --- |
| **Descarga con un clic** | Utiliza el botón junto a «Leer en voz alta» para guardar el audio de una respuesta. |
| **Descarga automática** | Activa **YES** y la extensión intentará descargar los nuevos audios cuando los reproduzcas. |
| **MP3 opcional** | Convierte el audio localmente a MP3 para escucharlo en más dispositivos. |
| **Conserva el original** | Desmarca la conversión para guardar el formato recibido, sin recodificar. |
| **Control inmediato** | Desactiva la descarga automática con **NO** sin perder la opción manual. |

**Sin subir tus audios a servidores propios.** El procesamiento y la conversión se realizan en tu navegador; los archivos se guardan mediante las descargas de Chrome. Las preferencias se almacenan en `chrome.storage.sync`.

## Cómo empezar

**Mientras se habilita la distribución pública**, puedes instalar la versión de desarrollo:

1. Descarga el ZIP de este repositorio y descomprímelo.
2. Abre `chrome://extensions` en Chrome y activa **Modo desarrollador**.
3. Selecciona **Cargar descomprimida** y elige la carpeta que contiene `manifest.json`.
4. Abre `https://chatgpt.com/` y reproduce una respuesta mediante **Leer en voz alta**.
5. Usa el botón de descarga junto al mensaje, o abre el popup de la extensión y selecciona **YES** para habilitar la descarga automática.

Los archivos se guardan en `Descargas/ExtractAudioGPT`. Si eliges MP3 y el navegador no puede convertir el audio, la extensión conserva el formato original.

## ¿Necesitas ayuda?

¿La descarga no aparece, falla la conversión o ChatGPT cambió su interfaz? **Abre un Issue** y describe qué ocurrió:

**[Reportar un problema o proponer una mejora →](https://github.com/jasp402/ExtractAudioGPT/issues/new/choose)**

Incluye la versión de la extensión, la versión de Chrome y los pasos para reproducir el error. **No compartas conversaciones privadas, cookies ni tokens de sesión.**

## Privacidad y transparencia

ExtractAudioGPT está diseñada para procesar el audio localmente, sin servicios externos de conversión ni analítica propia. Consulta la [política de privacidad](PRIVACY.md) para conocer el tratamiento del audio y de las preferencias sincronizadas.

## Estado del proyecto

**Versión 1.0.5 (pruebas).** La compatibilidad con cambios de la interfaz de ChatGPT, la descarga manual y la conversión MP3 necesitan pruebas E2E antes de considerarse estables.

- [Informe de QA](QA_REPORT.md)
- [Proceso de publicación](PUBLISHING.md)
- [Licencia](LICENSE)

*ExtractAudioGPT es un proyecto independiente; no está afiliado a OpenAI.*
