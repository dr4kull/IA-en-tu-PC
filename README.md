# IA en tu PC — web para GitHub Pages

Web estatica para `dr4kull/IA-en-tu-PC`, adaptada a los instaladores corregidos el 24/11/2026.

## Versiones que deben estar publicadas ANTES de subir esta web

1. **Voice Studio RC2 — Auto + Admin**: etiqueta `voice-studio-v2.0-rc2` y archivo `VoiceStudio_2.0_RC2.zip`.
2. **MuseTalk Studio 1.6.14 — Ruta corta**: etiqueta `musetalk-studio-v1.6.14` y archivo `MuseTalkStudio_1.6.14.zip`.

Los botones enlazan directamente a esas etiquetas y nombres EXACTOS. Si aún no has publicado ambas releases, la web dará error 404.

## Cómo publicar

1. Crea las dos releases en GitHub con las etiquetas exactas anteriores y sube los ZIP corregidos.
2. Comprueba los enlaces de `descargas.html` y los SHA-256 en `versiones.html`.
3. Sube los archivos de este ZIP **a la raiz del repositorio**, NO el ZIP entero.
4. Confirma los cambios en `main` y espera a que se actualice GitHub Pages.
5. Abre la web pública y verifica ambas descargas e instrucciones.

**IMPORTANTE:** la opción «Ejecutar como administrador» NO elimina las alertas de SmartScreen ni convierte un archivo desconocido en confiable. No desactives las protecciones de Windows.

## Dependencias y licencias

Voice Studio descarga automaticamente Python 3.11, Git portatil, PyTorch y modelos de voz. MuseTalk prepara Python 3.10, PyTorch, MuseTalk y modelos en `%LOCALAPPDATA%\IA_PC_MT` para evitar rutas largas de MMPose. Se requiere una NVIDIA compatible con CUDA para estas ediciones.

Revisa las licencias de los componentes de terceros y no subas modelos, entornos virtuales, archivos de audio ni otros datos privados al repositorio.
