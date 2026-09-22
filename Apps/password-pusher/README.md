# Password Pusher - ZimaOS

<!-- PORT-VERSION-BEGIN -->
Version: `2.14.0-refugioos.1` - ficha neutral apps/password-pusher/app.yaml
<!-- PORT-VERSION-END -->

Port de RefugioOS para ZimaOS.

- Imagen: ghcr.io/refugioos/password-pusher:2.14.0-refugioos.1 (amd64 + arm64), versionada, nunca `latest`.
- Interfaz web: http://localhost:3481
- Comparte contraseñas, texto y URLs con expiración por vistas o por tiempo.

Para actualizar: `python publicar-zimaos.py --app password-pusher --mode update`
(o regenera la salida con `--mode update --version <nuevo-tag> --force`).

Nota: la instalacion real en ZimaOS se hace desde el App Store apuntando a
este repositorio (estructura Apps/<AppName>/ con docker-compose.yml + icon.png).
