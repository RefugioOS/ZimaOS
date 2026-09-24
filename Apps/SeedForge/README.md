# SeedForge para CasaOS/ZimaOS

Carpeta preparada para el repo publico `RefugioOS/casaos`.

CasaOS/ZimaOS instala esta app desde `docker-compose.yml` y sus metadatos `x-casaos`.

## Antes de publicar

- Publicar la imagen `ghcr.io/refugioos/seedforge-lite:2.5.0-refugioos.1`.
- Revisar credenciales por defecto en `docker-compose.yml`.
- Mantener fuera del repo publico `backend/`, `frontend/`, `Dockerfile`, `.env` y `data/`.

## Conectividad

SeedForge incluye Settings para APIs externas, API keys BTC/ETH y nodos o APIs
propias. Puedes priorizar tu nodo local y dejar APIs externas como respaldo.

## Seguridad

No usar con datos reales hasta cambiar `SF_PASS`, `SF_SECRET` y `SF_DATA_KEY`.
