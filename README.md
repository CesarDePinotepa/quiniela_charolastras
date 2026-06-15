# Quiniela Mundial 2026 ⚽

Página para llevar el tracking de la quiniela familiar: ranking automático, captura de marcadores y tarjeta del próximo partido descargable como imagen para WhatsApp.

## Archivos
- `index.html` — la página (no necesitas tocarla).
- `data.js` — los datos: participantes, partidos, pronósticos y resultados.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub (ej. `quiniela-mundial`).
2. Sube `index.html`, `data.js` y este `README.md` a la raíz del repo.
3. Ve a **Settings → Pages**.
4. En **Source** elige la rama `main` y la carpeta `/ (root)`. Guarda.
5. En 1–2 minutos tu página estará en `https://TU-USUARIO.github.io/quiniela-mundial/`.

## Cómo usarla
1. **Pronósticos**: captura una vez lo que predijo cada primo (pestaña *Pronósticos*).
2. **Marcadores**: conforme termina cada partido, escribe el resultado real. El ranking se actualiza solo.
3. **Próximo**: muestra los pronósticos de todos para el siguiente partido sin jugar; el botón *Descargar imagen* genera el PNG para WhatsApp.

## Publicar cambios para todos
Tus capturas se guardan **solo en tu dispositivo** (borrador local). Para que tus primos vean los cambios en la web:
1. Pulsa **Descargar data.js**.
2. Reemplaza el `data.js` de tu repositorio con el descargado y haz commit.
3. GitHub Pages se actualiza en ~1 minuto.

Solo quien edita necesita hacer esto; el resto solo abre el enlace.

## Reglas de puntos
- **3 pts** — marcador exacto.
- **1 pt** — acertar al ganador (o al empate) sin el marcador exacto.
- Desempate en el ranking: más marcadores exactos.
