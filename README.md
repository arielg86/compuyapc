# REA y sus proyectos

Este repositorio reúne el proyecto REA como submódulo. REA incluye cinco submódulos de terceros (Binwalk, Ghidra NativeAOT, JADX Headless MCP, Unblob y Wakaru).

Para descargar REA y esos submódulos:

```sh
git clone --recurse-submodules https://github.com/arielg86/compuyapc.git
```

El código de REA queda en `rea/`. Sus dependencias de Node.js se instalan desde el manifiesto bloqueado del proyecto con `npm ci`.

Este repositorio apunta al proyecto original y conserva su historial; no reempaqueta ni altera las licencias de los proyectos incluidos.
