# aulaycasa-publicador

Robot que publica solo en Instagram (@aulaycasa) y en la página de Facebook de Aula y Casa.

- `calendario.json`: qué se publica y cuándo. Solo sale lo que tiene `"aprobado": true`.
- `media/`: imágenes (JPG) y videos (MP4).
- `data/estado.json`: lo que ya se publicó. `data/estadisticas.json`: métricas de cada post (se actualiza todos los días).
- `diseno/reels/`: herramientas para armar Reels.

Secretos en Settings → Secrets and variables → Actions: `IG_TOKEN` (obligatorio), token de usuario del sistema de Meta que no vence. `FB_PAGE_TOKEN` es opcional.
