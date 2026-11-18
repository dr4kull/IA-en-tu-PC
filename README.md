# IA en tu PC — web para GitHub Pages

Web estática para el repositorio `dr4kull/IA-en-tu-PC`.

## Versiones publicadas en la web

- **Voice Studio 2.0 RC2**: etiqueta `voice-studio-v2.0-rc2`; archivo `IA_en_tu_PC_Voice_Studio_v2_0_RC2.zip`. Motor Chatterbox es-ES, guiones largos y reducción de eco opcional.
- **MuseTalk Studio 1.6.14 BETA**: etiqueta `musetalk-studio-v1.6.14`; archivo `MuseTalk_Studio_v1.6.14_COMPLETO_BETA.zip`.

## Cómo publicar

1. Comprueba que ambas versiones existan en GitHub Releases y que cada ZIP tenga el mismo nombre que el enlace de `descargas.html`.
2. Sube **todos los archivos de este ZIP a la raíz del repositorio**, no el ZIP entero ni su carpeta contenedora.
3. Confirma los cambios en la rama utilizada por GitHub Pages (normalmente `main`).
4. Abre la web, pulsa Descargar en ambas aplicaciones y confirma que los archivos se descargan.
5. Comprueba las huellas SHA-256 de los ZIP en `SHA256SUMS.txt` y `versiones.html`.

La descarga directa de Voice Studio RC2 configurada en la web es:

https://github.com/dr4kull/IA-en-tu-PC/releases/download/voice-studio-v2.0-rc2/IA_en_tu_PC_Voice_Studio_v2_0_RC2.zip

**Nota:** si has cambiado el nombre del ZIP adjuntado a GitHub Releases o su etiqueta, actualiza la URL en `index.html`, `descargas.html`, `instalacion-completa.html` y `versiones.html`.

## Dependencias

Voice Studio RC2 requiere Python 3.11, Git y una NVIDIA compatible con CUDA en el instalador actual. Los modelos y bibliotecas se descargan durante la instalación/primer uso. No subas los entornos virtuales, modelos, grabaciones privadas ni archivos de vídeo al repositorio.

Documenta las licencias de cada componente externo, incluidas las del motor Chatterbox y su modelo español es-ES. El ZIP del programa todavía contiene un archivo de instrucciones heredado de RC1: actualízalo antes de publicarlo como versión estable.
