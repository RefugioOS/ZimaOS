# Zebra (Zcash Node) - ZimaOS

<!-- PORT-VERSION-BEGIN -->
Version: `6.3.0-refugioos.1` - upstream `v6.3.0` (commit `f5c5277fe41eba9c74f37098738f93f35dd70d60`)
<!-- PORT-VERSION-END -->

Port PURO del nodo Zcash [Zebra (zebrad)](https://github.com/ZcashFoundation/zebra)
de la Zcash Foundation para ZimaOS.

- Imagen: `ghcr.io/refugioos/zebra:6.3.0-refugioos.1` (amd64 + arm64), binarios oficiales verificados por SHA256.
- Puertos: **8233** P2P Mainnet, **8232** RPC JSON (cookie auth en /data/.cookie),
  **8080** health /healthy y /ready.
- Requisitos: ~300 GB de disco libre, 4 GB RAM minimo (16 GB recomendado).

Actualizacion automatica: `python scripts/update-port.py update` regenera esta
salida cuando la Zcash Foundation publica una release oficial nueva.
