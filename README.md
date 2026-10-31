# Aiuni Juega 🌸

App (PWA) para armar el plan semanal de juegos de estimulación de Aiuni: 29 juegos con dibujo, beneficios, materiales y pasos.

## Publicarla en GitHub Pages

1. En GitHub crea un repositorio nuevo, por ejemplo `aiuni-juega` (público).
2. Sube **todos** los archivos de esta carpeta tal cual (`index.html`, `manifest.webmanifest`, `sw.js` y la carpeta `icons`).
3. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. En 1 o 2 minutos tendrás el enlace: `https://TU-USUARIO.github.io/aiuni-juega/`.

## Instalarla en el celular

- **Android (Chrome):** abre el enlace → menú ⋮ → **Instalar app** o **Agregar a la pantalla principal**.
- **iPhone (Safari):** abre el enlace → botón Compartir → **Agregar a inicio**.

Después de abrirla una vez, funciona sin internet.

## Compartir con tu familia

En la app: botón ⚙️ (arriba a la derecha) → **Crear código familiar**. En el otro celular: ⚙️ → **Unirme con un código**.
Desde ahí los dos ven el mismo plan, los juegos hechos, los favoritos y el diario. Los datos se guardan en la base de datos de Mi Canastita (Supabase), en una tabla aparte.

## Recordatorios

⚙️ → Recordatorios: elige las horas y toca **Agregar avisos a mi calendario**. Se descarga un archivo .ics; al abrirlo, el celular agrega 3 avisos diarios. En iPhone hazlo desde Safari.

## Sobre los datos

Sin código familiar, todo se guarda solo en ese celular.
Cada lunes llega un plan nuevo según su edad y los juegos que le encantan.
