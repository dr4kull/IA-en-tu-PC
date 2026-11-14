# IA en tu PC — web para GitHub Pages

Web estática responsive del proyecto **IA en tu PC**, preparada para publicar en la raíz del repositorio **`IA-en-tu-PC`**.

## Archivos

- `index.html`: portada.
- `descargas.html`: fichas y descarga de las apps.
- `instalacion-completa.html`: guía actualizada para los instaladores automáticos.
- `requisitos.html`: requisitos y licencias.
- `versiones.html`: versiones BETA y hashes SHA-256.
- `styles.css`, `logo.png`, `.nojekyll`: apariencia y recursos.
- `SHA256SUMS.txt`: comprobación de integridad de los dos ZIP.

## Datos de publicación

- Cuenta GitHub vinculada: `dsataciertocom`.
- Repositorio previsto: `https://github.com/dsataciertocom/IA-en-tu-PC` (**debe existir primero**).
- URL prevista de GitHub Pages: `https://dsataciertocom.github.io/IA-en-tu-PC/` (**no está publicada todavía**).
- Releases/archivos: ver `../02_ZIPS_SUBIR_A_RELEASES` dentro del kit.
- Etiqueta Voice: `voice-studio-v1.6.8`; fichero: `IA_en_tu_PC_Voice_Studio_v1_6_8_PRUEBA_FINAL.zip`.
- Etiqueta MuseTalk: `musetalk-studio-v1.6.14`; fichero: `MuseTalk_Studio_v1.6.14_COMPLETO_BETA.zip`.

Los botones enlazan a las URL exactas de GitHub Releases. **Hasta que subas ambos ZIP a esas etiquetas, las descargas devolverán 404**. Publica primero las releases, después la web. Si el repositorio termina en otra cuenta o nombre, sustituye `dsataciertocom/IA-en-tu-PC` en los archivos HTML.

## Publicar

1. Crea (o abre) un repositorio público llamado `IA-en-tu-PC` en GitHub.
2. Sube **el contenido de esta carpeta** a la raíz de `main`, no la carpeta completa ni el ZIP.
3. Crea los dos releases y adjunta el ZIP exacto indicado en cada etiqueta (puedes hacer las releases antes que la web).
4. En **Settings → Pages → Source → Deploy from a branch → main → /(root) → Save**.
5. Revisa `index.html`, `descargas.html` y prueba ambos botones de descarga una vez publicadas las releases.

No incluyas motores, venv, modelos de IA ni vídeos privados en el repositorio. Revisa los términos de uso de los modelos (F5-Spanish es CC BY-NC 4.0) y los ficheros de licencias dentro de cada ZIP.
