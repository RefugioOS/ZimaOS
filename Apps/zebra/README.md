# Zebra (Zcash Node) - ZimaOS

<!-- PORT-VERSION-BEGIN -->
Version: `6.3.0-refugioos.2` - upstream `v6.3.0` (commit `f5c5277fe41eba9c74f37098738f93f35dd70d60`)
<!-- PORT-VERSION-END -->

Port PURO del nodo Zcash [Zebra (zebrad)](https://github.com/ZcashFoundation/zebra)
de la Zcash Foundation para ZimaOS.

- Imagen: `ghcr.io/refugioos/zebra:6.3.0-refugioos.2` (amd64 + arm64), binarios oficiales verificados por SHA256.
- Puertos: **8233** P2P Mainnet, **8232** RPC JSON (cookie auth en /data/.cookie),
  **48232** pagina de estado local (estado del nodo y log del sync).
- Requisitos: ~300 GB de disco libre, 4 GB RAM minimo (16 GB recomendado).
- Recursos: RAM limitada a 4 GB por defecto (minimo oficial, suficiente para
  sync; sube con `ZEBRA_MEM_LIMIT`) y logs rotados (20 MB x 3); la pagina
  avisa si el disco libre baja de 25 GB (la cadena no se puede podar).

Al abrir el puerto 48232 veras la pagina de estado del nodo: si zebrad cae se
relanza solo y el error aparece en pantalla, y durante el sync inicial el log
muestra el progreso.

Actualizacion automatica: `python scripts/update-port.py update` regenera esta
salida cuando la Zcash Foundation publica una release oficial nueva.
