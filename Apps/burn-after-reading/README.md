# Burn After Reading - ZimaOS

<!-- PORT-VERSION-BEGIN -->
Version: `0.1.6-refugioos.2` - ficha neutral apps/burn-after-reading/app.yaml
<!-- PORT-VERSION-END -->

Port de RefugioOS para ZimaOS.

- Imagen: ghcr.io/refugioos/burn-after-reading:0.1.6-refugioos.2 (amd64 + arm64), versionada, nunca `latest`.
- Interfaz web: http://localhost:3480
- Pastebin efímero para compartir mensajes y archivos con enlaces de un solo uso.

Para actualizar: `python publicar-zimaos.py --app burn-after-reading --mode update`
(o regenera la salida con `--mode update --version <nuevo-tag> --force`).

Nota: la instalacion real en ZimaOS se hace desde el App Store apuntando a
este repositorio (estructura Apps/<AppName>/ con docker-compose.yml + icon.png).
